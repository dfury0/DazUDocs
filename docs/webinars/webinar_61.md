# 61 | Webinar - January 10, 2019
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
          videoId: '5lHNiTzAfT0',
        });
      }
    
    function setCurrentTime(slideNum) {
    var object = [0, 17, 180, 215, 260, 782, 929, 1170, 1748]
    player.seekTo(object[slideNum]);
  }
</script>
    
## Timestamps
* Poses controls in content creation <a href="javascript:void(0);" onclick="setCurrentTime(0)">(00:00)</a>
* Poses included in DAZ base figures <a href="javascript:void(0);" onclick="setCurrentTime(1)">(00:17)</a>
* Pose controls and included Poses <a href="javascript:void(0);" onclick="setCurrentTime(2)">(03:00)</a>
* Pose controls and shoes <a href="javascript:void(0);" onclick="setCurrentTime(3)">(03:35)</a>
* Custom pose controls <a href="javascript:void(0);" onclick="setCurrentTime(4)">(04:20)</a>
* Hiding foot geometry <a href="javascript:void(0);" onclick="setCurrentTime(5)">(13:02)</a>
* Foot morphs for footwear <a href="javascript:void(0);" onclick="setCurrentTime(6)">(15:29)</a>
* How to create projection morphs for footwear <a href="javascript:void(0);" onclick="setCurrentTime(7)">(19:30)</a>
* How to create a twist bone <a href="javascript:void(0);" onclick="setCurrentTime(8)">(29:08)</a>
