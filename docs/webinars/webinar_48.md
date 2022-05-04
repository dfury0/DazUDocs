# 47 | Webinar - May 31, 2018
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
          videoId: 'O0_OQhPE2v8',
        });
      }
    
    function setCurrentTime(slideNum) {
    var object = [0, 1540, 2360, 3387]
    player.seekTo(object[slideNum]);
  }
</script>
    
## Timestamps
* How to create a morph on a figure to drive a morph on a parented prop <a href="javascript:void(0);" onclick="setCurrentTime(0)">(00:00)</a>
* How to set up morphs on a figure to control morphs on a prop/follower when figure is selected <a href="javascript:void(0);" onclick="setCurrentTime(1)">(25:40)</a>
* Projecting morphs from a figure to a prop (Transfer utility, rigidity groups, control bones) <a href="javascript:void(0);" onclick="setCurrentTime(2)">(39:20)</a>
* dForce hair updates in Publishing build <a href="javascript:void(0);" onclick="setCurrentTime(3)">(56:27)</a>
