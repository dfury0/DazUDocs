# 07 | Webinar - September 19, 2017
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
          videoId: 'Fc6o9PGXyeo',
        });
      }
    
    function setCurrentTime(slideNum) {
    var object = [0, 927, 1328, 1685, 2340, 2877, 3670]
    player.seekTo(object[slideNum]);
  }
</script>
    
## Timestamps
* HDRIs: exposure values, how to cast shadows on objects <a href="javascript:void(0);" onclick="setCurrentTime(0)">(00:00)</a>
* Q&A Grayscale maps <a href="javascript:void(0);" onclick="setCurrentTime(1)">(15:27)</a>
* Setting up JCMs/MCMs with both positive and negative values <a href="javascript:void(0);" onclick="setCurrentTime(2)">(22:08)</a>
* Fixing morphs on clothing <a href="javascript:void(0);" onclick="setCurrentTime(3)">(28:05)</a>
* Script for listing products used <a href="javascript:void(0);" onclick="setCurrentTime(4)">(39:00)</a>
* Converting clothing from G3 to G8 <a href="javascript:void(0);" onclick="setCurrentTime(5)">(47:57)</a>
* dForce: simulation base shape morphs, resolving poke-through/'explosions' <a href="javascript:void(0);" onclick="setCurrentTime(6)">(01:01:10)</a>
