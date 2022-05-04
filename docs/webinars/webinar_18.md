# 18 | Webinar - October 31, 2017
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
          videoId: 'qlbq4Kz6CvQ',
        });
      }
    
    function setCurrentTime(slideNum) {
    var object = [0, 580, 1160, 1540, 1713, 2235, 2417, 2935, 3150, 3445]
    player.seekTo(object[slideNum]);
  }
</script>
    
## Timestamps
* Hexagon announcement <a href="javascript:void(0);" onclick="setCurrentTime(0)">(00:00)</a>
* Diffuse Overlay <a href="javascript:void(0);" onclick="setCurrentTime(1)">(09:40)</a>
* Diffuse overlay compared to LIE & Geometry Shells <a href="javascript:void(0);" onclick="setCurrentTime(2)">(19:20)</a>
* Quick LIE demonstration <a href="javascript:void(0);" onclick="setCurrentTime(3)">(25:40)</a>
* Iray Iray Decal nodes <a href="javascript:void(0);" onclick="setCurrentTime(4)">(28:33)</a>
* Interactive Lessons samples <a href="javascript:void(0);" onclick="setCurrentTime(5)">(37:15)</a>
* Conditional Grafts <a href="javascript:void(0);" onclick="setCurrentTime(6)">(40:17)</a>
* Wearable presets issue (fixed) & QA guideline <a href="javascript:void(0);" onclick="setCurrentTime(7)">(48:55)</a>
* Q&A: Geometry switching <a href="javascript:void(0);" onclick="setCurrentTime(8)">(52:30)</a>
* Upcoming build & dForce fixes <a href="javascript:void(0);" onclick="setCurrentTime(9)">(57:25)</a>
