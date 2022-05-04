# 09 | Webinar - September 26, 2017
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
          videoId: 'eWZcKgl5z0Y',
        });
      }
    
    function setCurrentTime(slideNum) {
    var object = [0, 350, 1900, 2946, 3198, 3368, 4154]
    player.seekTo(object[slideNum]);
  }
</script>
    
## Timestamps
* Foot pose differences between G3F and G8F <a href="javascript:void(0);" onclick="setCurrentTime(0)">(0:00)</a>
* Long hair issues around neck (projection templates, turning off JCMs) <a href="javascript:void(0);" onclick="setCurrentTime(1)">(5:50)</a>
* Rigidity on long hair to fix morph issues <a href="javascript:void(0);" onclick="setCurrentTime(2)">(31:40)</a>
* Adding bones to followers (hair/clothing) <a href="javascript:void(0);" onclick="setCurrentTime(3)">(49:06)</a>
* Setting extra bones to follow rigidity <a href="javascript:void(0);" onclick="setCurrentTime(4)">(53:18)</a>
* Weightmaps from scratch <a href="javascript:void(0);" onclick="setCurrentTime(5)">(56:08)</a>
* Shaders and MDL <a href="javascript:void(0);" onclick="setCurrentTime(6)">(1:09:14)</a>
