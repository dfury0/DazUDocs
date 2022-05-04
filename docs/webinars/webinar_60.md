# 60 | Webinar - December 13, 2018
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
          videoId: 'wEzAL5AhBjo',
        });
      }
    
    function setCurrentTime(slideNum) {
    var object = [208, 268, 400, 624, 1285, 1434, 1514, 2320, 4157]
    player.seekTo(object[slideNum]);
  }
</script>
    
## Timestamps
* Smoothing modifier for morphs <a href="javascript:void(0);" onclick="setCurrentTime(0)">(03:28)</a>
* Correcting rigidity <a href="javascript:void(0);" onclick="setCurrentTime(1)">(04:28)</a>
* Smoothing modifier, exporting & loading as a morph <a href="javascript:void(0);" onclick="setCurrentTime(2)">(06:40)</a>
* Using weightmaps to control areas to morph <a href="javascript:void(0);" onclick="setCurrentTime(3)">(10:24)</a>
* Alternative method <a href="javascript:void(0);" onclick="setCurrentTime(4)">(21:25)</a>
* Baked smoothed morph menu option <a href="javascript:void(0);" onclick="setCurrentTime(5)">(23:54)</a>
* Projection morphs <a href="javascript:void(0);" onclick="setCurrentTime(6)">(25:14)</a>
* Post Load script set up for character presets <a href="javascript:void(0);" onclick="setCurrentTime(7)">(38:40)</a>
*  Material preset set  up <a href="javascript:void(0);" onclick="setCurrentTime(8)">(01:09:17)</a>
