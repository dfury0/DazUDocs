# 31 | Webinar - January 18, 2018
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
          videoId: 'C4IY55iLckA',
        });
      }
    
    function setCurrentTime(slideNum) {
    var object = [24, 645, 848, 1059, 2444]
    player.seekTo(object[slideNum]);
  }
</script>
    
## Timestamps
* dForce: Tracking down issues causing disappearing/exploding meshes <a href="javascript:void(0);" onclick="setCurrentTime(0)">(00:24)</a>
* dForce: Solving issues with Buckles deforming <a href="javascript:void(0);" onclick="setCurrentTime(1)">(10:45)</a>
* Preventing JCMs from projecting to clothing <a href="javascript:void(0);" onclick="setCurrentTime(2)">(14:08)</a>
* Geografting and rigging a tail <a href="javascript:void(0);" onclick="setCurrentTime(3)">(17:39)</a>
* Rigging a belt buckle <a href="javascript:void(0);" onclick="setCurrentTime(4)">(40:44)</a>

## Note
![type:video](https://www.youtube.com/watch?v=C4IY55iLckA)
During the webinar, through a combination of bugs and human error (mostly human error), we had to attempt to rig the tail a number of times. It was requested that the troubleshooting be shared because some clothing riggers found it useful to see the processes and thinking behind trying to figure out why it was malfunctioning. The troubleshooting steps were moved into another video to make the webinar more bearable to watch and is linked below. The correct process was recorded and inserted into the video above.