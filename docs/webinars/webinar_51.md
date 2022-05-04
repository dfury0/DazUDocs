# 51 | Webinar - June 28, 2018
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
          videoId: 'FhDYFK7NfaQ',
        });
      }
    
    function setCurrentTime(slideNum) {
    var object = [0, 295, 659, 730, 793, 1005, 1520, 1931, 2053, 2145, 2770, 3005, 3723]
    player.seekTo(object[slideNum]);
  }
</script>
    
## Timestamps
* Publishing Build update <a href="javascript:void(0);" onclick="setCurrentTime(0)">(00:00)</a>
* Tips and discussion on keeping file sizes small <a href="javascript:void(0);" onclick="setCurrentTime(1)">(04:55)</a>
* Texture compression for smaller files <a href="javascript:void(0);" onclick="setCurrentTime(2)">(10:59)</a>
* SubD on items for smaller files <a href="javascript:void(0);" onclick="setCurrentTime(3)">(12:10)</a>
* 8bit/16bit maps, .png/.jpg maps for smaller files <a href="javascript:void(0);" onclick="setCurrentTime(4)">(13:13)</a>
* HD morphs, removing morph vertices by changing tolerance in Morph Loader Pro for smaller files <a href="javascript:void(0);" onclick="setCurrentTime(5)">(16:45)</a>
* Scene files for smaller files <a href="javascript:void(0);" onclick="setCurrentTime(6)">(25:20)</a>
* Product file compression for smaller files <a href="javascript:void(0);" onclick="setCurrentTime(7)">(32:11)</a>
* Shader Definition Assets (should be saved whenever you customize in Shader Mixer)  <a href="javascript:void(0);" onclick="setCurrentTime(8)">(34:13)</a>
* .djl files, Postload script, data folder for smaller files <a href="javascript:void(0);" onclick="setCurrentTime(9)">(35:45)</a>
* .tip.png sizes <a href="javascript:void(0);" onclick="setCurrentTime(10)">(46:10)</a>
* dForce hair updates <a href="javascript:void(0);" onclick="setCurrentTime(11)">(50:05)</a>
* dForce hair UV maps <a href="javascript:void(0);" onclick="setCurrentTime(12)">(01:02:03)</a>
