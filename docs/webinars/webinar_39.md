# 38 | Webinar - March 15, 2018
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
          videoId: 'rCqiu43VDug',
        });
      }
    
    function setCurrentTime(slideNum) {
    var object = [77, 164, 360, 750, 1200, 1904, 3130, 3796, 4728, 4940]
    player.seekTo(object[slideNum]);
  }
</script>
    
## Timestamps
* Animation <a href="javascript:void(0);" onclick="setCurrentTime(0)">(01:17)</a>
* The Animation Timeline <a href="javascript:void(0);" onclick="setCurrentTime(1)">(02:44)</a>
* Creating/deleting animation keyframes <a href="javascript:void(0);" onclick="setCurrentTime(2)">(06:00)</a>
* Demonstration animation with dForce <a href="javascript:void(0);" onclick="setCurrentTime(3)">(12:30)</a>
* Controlling animation interpolations <a href="javascript:void(0);" onclick="setCurrentTime(4)">(20:00)</a>
* Keyed ERC animation & poses <a href="javascript:void(0);" onclick="setCurrentTime(5)">(31:44)</a>
* Puppeteer for pose blends and animation <a href="javascript:void(0);" onclick="setCurrentTime(6)">(52:10)</a>
* Rigging – Transferring parts of rigging from one object to another. <a href="javascript:void(0);" onclick="setCurrentTime(7)">(01:03:16)</a>
* Updating UV maps <a href="javascript:void(0);" onclick="setCurrentTime(8)">(01:18:48)</a>
* Creating HD Morphs <a href="javascript:void(0);" onclick="setCurrentTime(9)">(01:22:20)</a>
