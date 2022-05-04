# 08 | Webinar - September 21, 2017
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
          videoId: 'INASsKMDU1Q',
        });
      }
    
    function setCurrentTime(slideNum) {
    var object = [0, 4035]
    player.seekTo(object[slideNum]);
  }
</script>
    
## Timestamps
* Clothing Rigging Basics <a href="javascript:void(0);" onclick="setCurrentTime(0)">(00:00)</a>
* dForce Wind Nodes <a href="javascript:void(0);" onclick="setCurrentTime(1)">(1:07:15)</a>
