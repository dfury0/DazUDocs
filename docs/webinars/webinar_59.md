# 59 | Webinar - November 29, 2018
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
          videoId: 'Sqf16uL2CT8',
        });
      }
    
    function setCurrentTime(slideNum) {
    var object = [95, 507, 870, 1845, 2845]
    player.seekTo(object[slideNum]);
  }
</script>
    
## Timestamps
* Update Base Geometry feature <a href="javascript:void(0);" onclick="setCurrentTime(0)">(01:35)</a>
* comparison with Transfer Utility for updating geometry <a href="javascript:void(0);" onclick="setCurrentTime(1)">(08:27)</a>
* New method to convert material presets to hierarchical presets <a href="javascript:void(0);" onclick="setCurrentTime(2)">(14:30)</a>
* Examples of other presets that can be converted <a href="javascript:void(0);" onclick="setCurrentTime(3)">(30:45)</a>
* Correct location for pJCMs <a href="javascript:void(0);" onclick="setCurrentTime(4)">(47:25)</a>
