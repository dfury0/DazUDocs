# 50 | Webinar - June 21, 2018
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
          videoId: '2KGei7ocYjM',
        });
      }
    
    function setCurrentTime(slideNum) {
    var object = [0, 345, 1145, 1298, 1585, 1843, 2220]
    player.seekTo(object[slideNum]);
  }
</script>
    
## Timestamps
* Publishing Build update <a href="javascript:void(0);" onclick="setCurrentTime(0)">(00:00)</a>
* Silent OBJ Export script for symmetrical Genesis exports <a href="javascript:void(0);" onclick="setCurrentTime(1)">(05:45)</a>
* Zelara update <a href="javascript:void(0);" onclick="setCurrentTime(2)">(19:05)</a>
* Using surface horizontal offset to display numbers on an object (Maclean tutorial) <a href="javascript:void(0);" onclick="setCurrentTime(3)">(21:38)</a>
* Script samples to help animate in a similar way <a href="javascript:void(0);" onclick="setCurrentTime(4)">(26:25)</a>
* Shader preset to change offsets <a href="javascript:void(0);" onclick="setCurrentTime(5)">(30:43)</a>
* PASS update - new layout and features <a href="javascript:void(0);" onclick="setCurrentTime(6)">(37:00)</a>
