# 03 | Webinar - September 6, 2017
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
          videoId: 'zm2rMe1rPd8',
        });
      }
    
    function setCurrentTime(slideNum) {
    var object = [150, 750, 1735, 2618, 3835, 4115, 4401]
    player.seekTo(object[slideNum]);
  }
</script>
    
## Timestamps
* New Diffuse Overlay settings in Iray <a href="javascript:void(0);" onclick="setCurrentTime(0)">(02:30)</a>
* Geografting <a href="javascript:void(0);" onclick="setCurrentTime(1)">(12:30)</a>
* HD Morphs <a href="javascript:void(0);" onclick="setCurrentTime(2)">(28:55)</a>
* Morphs: Adjusting rigging to shape <a href="javascript:void(0);" onclick="setCurrentTime(3)">(43:38)</a>
* Transfer Utility (Use Near Verts, Adaptive Tolerance) <a href="javascript:void(0);" onclick="setCurrentTime(4)">(01:03:55)</a>
* Skeletons: Transferring JCMs from G3 to G8 <a href="javascript:void(0);" onclick="setCurrentTime(5)">(01:08:35)</a>
* Transfer Utility for clothing (G3 to G8) <a href="javascript:void(0);" onclick="setCurrentTime(6)">(01:13:21)</a>
