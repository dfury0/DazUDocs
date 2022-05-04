# 41 | Webinar - April 5, 2018
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
          videoId: 'au9i1A5jasE',
        });
      }
    
    function setCurrentTime(slideNum) {
    var object = [135, 475, 1130, 2615, 2935, 3188, 3478]
    player.seekTo(object[slideNum]);
  }
</script>
    
## Timestamps
* Editing Manifest files <a href="javascript:void(0);" onclick="setCurrentTime(0)">(02:15)</a>
* Batch convert (Compressing/uncompressing files) <a href="javascript:void(0);" onclick="setCurrentTime(1)">(07:55)</a>
* Correctly setting up and saving hand props <a href="javascript:void(0);" onclick="setCurrentTime(2)">(18:50)</a>
* Using Transfer Utility for hand props <a href="javascript:void(0);" onclick="setCurrentTime(3)">(43:35)</a>
* Updating hand prop Geometry <a href="javascript:void(0);" onclick="setCurrentTime(4)">(48:55)</a>
* Basic concept of rigging <a href="javascript:void(0);" onclick="setCurrentTime(5)">(53:08)</a>
* Changing node names (including symmetry tips) <a href="javascript:void(0);" onclick="setCurrentTime(6)">(57:58)</a>
