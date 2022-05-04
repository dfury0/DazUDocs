# 10 | Webinar - September 28, 2017
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
          videoId: 'zRGpSozh8Xk',
        });
      }
    
    function setCurrentTime(slideNum) {
    var object = [16, 500, 800, 1200, 1255, 1975, 2130, 3129]
    player.seekTo(object[slideNum]);
  }
</script>
    
## Timestamps
* Rigging long dresses: Control Bones <a href="javascript:void(0);" onclick="setCurrentTime(0)">(00:16)</a>
* Long dress rigging: Removing unnecessary bones <a href="javascript:void(0);" onclick="setCurrentTime(1)">(08:20)</a>
* Long dress rigging: Making bend pose controls/morphs <a href="javascript:void(0);" onclick="setCurrentTime(2)">(13:20)</a>
* Long dress rigging: Comment on using Auto Follow Transforms <a href="javascript:void(0);" onclick="setCurrentTime(3)">(20:00)</a>
* Long dress rigging: Creating control bones <a href="javascript:void(0);" onclick="setCurrentTime(4)">(20:55)</a>
* How to create bones <a href="javascript:void(0);" onclick="setCurrentTime(5)">(32:55)</a>
* Q&A dForce ( JCMs, clothing distance, surface smoothing, stiffness, tris/quads) <a href="javascript:void(0);" onclick="setCurrentTime(6)">(35:30)</a>
* dForce: How to deal with buttons <a href="javascript:void(0);" onclick="setCurrentTime(7)">(52:09)</a>
