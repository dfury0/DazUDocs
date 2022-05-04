# 20 | Webinar - November 7, 2017
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
          videoId: 'vMUwvpZ6mh4',
        });
      }
    
    function setCurrentTime(slideNum) {
    var object = [150, 1218, 1338, 1760, 1920, 3130, 3441, 3560, 4235, 4500]
    player.seekTo(object[slideNum]);
  }
</script>
    
## Timestamps
* Determining the rotation order of a bone <a href="javascript:void(0);" onclick="setCurrentTime(0)">(02:30)</a>
* Packaging HDRIs as presets <a href="javascript:void(0);" onclick="setCurrentTime(1)">(20:18)</a>
* Q&A Aligning bone axis of rotation <a href="javascript:void(0);" onclick="setCurrentTime(2)">(22:18)</a>
* More on HDRI/lights presets <a href="javascript:void(0);" onclick="setCurrentTime(3)">(29:20)</a>
* Transmitting light through transparent objects <a href="javascript:void(0);" onclick="setCurrentTime(4)">(32:00)</a>
* Q&A Underwater renders <a href="javascript:void(0);" onclick="setCurrentTime(5)">(52:10)</a>
* Iray Canvases (quick overview) <a href="javascript:void(0);" onclick="setCurrentTime(6)">(57:21)</a>
* Discussion on canvases/postwork in product promos <a href="javascript:void(0);" onclick="setCurrentTime(7)">(59:20)</a>
* General chat on webinar topic suggestions <a href="javascript:void(0);" onclick="setCurrentTime(8)">(01:10:35)</a>
* dForce Dynamic Surface Addon  <a href="javascript:void(0);" onclick="setCurrentTime(9)">(01:15:00)</a>
