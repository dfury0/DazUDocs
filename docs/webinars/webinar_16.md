# 16 | Webinar - October 24, 2017
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
          videoId: 'KDoaRT9Os-0',
        });
      }
    
    function setCurrentTime(slideNum) {
    var object = [131, 363, 760, 859, 982, 1357, 1545, 2283]
    player.seekTo(object[slideNum]);
  }
</script>
    
## Timestamps
* Property Hierarchy, bake to transforms & pose mirroring <a href="javascript:void(0);" onclick="setCurrentTime(0)">(02:11)</a>
* Dynamic Tube Add-on recap <a href="javascript:void(0);" onclick="setCurrentTime(1)">(06:03)</a>
* Q&A: Adding comments in .DUF files <a href="javascript:void(0);" onclick="setCurrentTime(2)">(12:40)</a>
* Q&A: Auto hide in shaders <a href="javascript:void(0);" onclick="setCurrentTime(3)">(14:19)</a>
* dForce Damping feature <a href="javascript:void(0);" onclick="setCurrentTime(4)">(16:22)</a>
* dForce Visible in Simulation for bones <a href="javascript:void(0);" onclick="setCurrentTime(5)">(22:37)</a>
* dForce Clothing Seam issues <a href="javascript:void(0);" onclick="setCurrentTime(6)">(25:45)</a>
* dForce Simulation Base/Base Shape morphs <a href="javascript:void(0);" onclick="setCurrentTime(7)">(38:03)</a>
