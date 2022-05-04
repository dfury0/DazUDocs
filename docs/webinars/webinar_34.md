# 34 | Webinar - February 8, 2018
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
          videoId: 'kyDSj55kFVY',
        });
      }
    
    function setCurrentTime(slideNum) {
    var object = [60, 720, 1494, 1620, 3180, 3506, 4129, 4276]
    player.seekTo(object[slideNum]);
  }
</script>
    
## Timestamps
* Artwork guidelines update <a href="javascript:void(0);" onclick="setCurrentTime(0)">(01:00)</a>
* Iray Post Denoiser Filter <a href="javascript:void(0);" onclick="setCurrentTime(1)">(12:00)</a>
* PASS store page preview <a href="javascript:void(0);" onclick="setCurrentTime(2)">(24:54)</a>
* Creating JCMs for clothing <a href="javascript:void(0);" onclick="setCurrentTime(3)">(27:00)</a>
* dForce: Collision offset values <a href="javascript:void(0);" onclick="setCurrentTime(4)">(53:00)</a>
* dForce: Using older content using weightmaps <a href="javascript:void(0);" onclick="setCurrentTime(5)">(58:26)</a>
* dForce Velocity smoothing for older content <a href="javascript:void(0);" onclick="setCurrentTime(6)">(01:08:49)</a>
* dForce Base shape matching for older content <a href="javascript:void(0);" onclick="setCurrentTime(7)">(01:11:16)</a>
