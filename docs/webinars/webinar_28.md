# 28 | Webinar - December 14, 2017
## Video
<div class="responsive-container"><div id="player"></div></div>
<script>
      var tag = document.createElement('script');
      tag.src = "https://www.youtube.com/iframe_api";
      var firstScriptTag = document.getElementsByTagName('script')[0];
      firstScriptTag.parentNode.insertBefore(tag, firstScriptTag);
      var player;
      function onYouTubeIframeAPIReady() {
        player = new YT.Player('player', {
          videoId: 'kSKZNfjWjQo',
        });
      }
    
    function setCurrentTime(slideNum) {
    var object = [50, 660, 694, 1120, 1180, 1640, 2000, 2128, 2398, 2648, 3084, 3367, 3584, 3870, 4084, 4509, 4618, 4962, 5587]
    player.seekTo(object[slideNum]);
  }
</script>
    
## Timestamps
* Restricting pose movement for clothing <a href="javascript:void(0);" onclick="setCurrentTime(0)">(00:50)</a>
* Buttons in dForce simulation <a href="javascript:void(0);" onclick="setCurrentTime(1)">(11:00)</a>
* Issue with morph being called when saving Character preset <a href="javascript:void(0);" onclick="setCurrentTime(2)">(11:34)</a>
* Sakura update <a href="javascript:void(0);" onclick="setCurrentTime(3)">(18:40)</a>
* Including D-Formers in content <a href="javascript:void(0);" onclick="setCurrentTime(4)">(19:40)</a>
* Exporting & importing a D-Form as a morph <a href="javascript:void(0);" onclick="setCurrentTime(5)">(27:20)</a>
* DS HeadSplit DFormer <a href="javascript:void(0);" onclick="setCurrentTime(6)">(33:20)</a>
* Saving D-Formers in clothing <a href="javascript:void(0);" onclick="setCurrentTime(7)">(35:28)</a>
* D-Formers affecting more than one figure <a href="javascript:void(0);" onclick="setCurrentTime(8)">(39:58)</a>
* Iray Surfaces Tags & Material ID <a href="javascript:void(0);" onclick="setCurrentTime(9)">(44:08)</a>
* Using tags to select Iray surfaces <a href="javascript:void(0);" onclick="setCurrentTime(10)">(51:24)</a>
* Forward and Inverse Kinematics <a href="javascript:void(0);" onclick="setCurrentTime(11)">(56:07)</a>
* Hidden nodes <a href="javascript:void(0);" onclick="setCurrentTime(12)">(59:44)</a>
* Bake Figure IK to FK option <a href="javascript:void(0);" onclick="setCurrentTime(13)">(01:04:30)</a>
* DForce: Rigid Follow Nodes tips <a href="javascript:void(0);" onclick="setCurrentTime(14)">(01:08:04)</a>
* DForce: Dynamic Surface Addon Visible in Viewport <a href="javascript:void(0);" onclick="setCurrentTime(15)">(01:15:09)</a>
* Group nodes and visibility <a href="javascript:void(0);" onclick="setCurrentTime(16)">(01:16:58)</a>
* Script samples (Simple Composite Image Dialog) <a href="javascript:void(0);" onclick="setCurrentTime(17)">(01:22:42)</a>
* Character material presets: Post Load Settings <a href="javascript:void(0);" onclick="setCurrentTime(18)">(01:33:07)</a>
