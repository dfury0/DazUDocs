# 22 | Webinar - November 14, 2017
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
          videoId: '8VuwOKC6zmU',
        });
      }
    
    function setCurrentTime(slideNum) {
    var object = [0, 300, 437, 676, 721, 907, 965, 1291, 1652, 3045, 3926, 3959, 4255]
    player.seekTo(object[slideNum]);
  }
</script>
    
## Timestamps
* Script sample updates <a href="javascript:void(0);" onclick="setCurrentTime(0)">(00:00)</a>
* Iray Canvases Alpha option <a href="javascript:void(0);" onclick="setCurrentTime(1)">(05:00)</a>
* Turning off the ground <a href="javascript:void(0);" onclick="setCurrentTime(2)">(07:17)</a>
* Q&A on canvasses <a href="javascript:void(0);" onclick="setCurrentTime(3)">(11:16)</a>
* DForce animation: moving a chair under a figure <a href="javascript:void(0);" onclick="setCurrentTime(4)">(12:01)</a>
* DzMessageBox script <a href="javascript:void(0);" onclick="setCurrentTime(5)">(15:07)</a>
* dForce animation: moving a chair under a figure (continued) <a href="javascript:void(0);" onclick="setCurrentTime(6)">(16:05)</a>
* Overview of Puppeteer <a href="javascript:void(0);" onclick="setCurrentTime(7)">(21:31)</a>
* dForce: Using bones for more control <a href="javascript:void(0);" onclick="setCurrentTime(8)">(27:32)</a>
* Merging fitted figures <a href="javascript:void(0);" onclick="setCurrentTime(9)">(50:45)</a>
* dForce: Dealing with floating vertices in mesh <a href="javascript:void(0);" onclick="setCurrentTime(10)">(01:05:26)</a>
* Splitting geometry <a href="javascript:void(0);" onclick="setCurrentTime(11)">(01:05:59)</a>
* Making icons for pose controls <a href="javascript:void(0);" onclick="setCurrentTime(12)">(01:10:55)</a>
