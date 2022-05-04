# 14 | Webinar - October 12, 2017
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
          videoId: 'zh0lRCjvM4E',
        });
      }
    
    function setCurrentTime(slideNum) {
    var object = [30, 438, 1350, 1370, 2117, 2270, 2679, 3213, 3389, 3481, 3668, 4292, 4820]
    player.seekTo(object[slideNum]);
  }
</script>
    
## Timestamps
* How to set up a boolean property morph <a href="javascript:void(0);" onclick="setCurrentTime(0)">(00:30)</a>
* Enum property <a href="javascript:void(0);" onclick="setCurrentTime(1)">(07:18)</a>
* D-formers and weight maps (transferring to a different mesh) <a href="javascript:void(0);" onclick="setCurrentTime(2)">(22:30)</a>
* Customizing navigation to match other programs <a href="javascript:void(0);" onclick="setCurrentTime(3)">(22:50)</a>
* Shader mixer: creating texture rotation <a href="javascript:void(0);" onclick="setCurrentTime(4)">(35:17)</a>
* Shader mixer: Q&A: Distributing shaders (Iray Uber/MDL licensing) <a href="javascript:void(0);" onclick="setCurrentTime(5)">(37:50)</a>
* Shader mixer: Shader Mixer overview <a href="javascript:void(0);" onclick="setCurrentTime(6)">(44:39)</a>
* Shader mixer: Meaning of node lettering <a href="javascript:void(0);" onclick="setCurrentTime(7)">(53:33)</a>
* Shader mixer: Changing input types <a href="javascript:void(0);" onclick="setCurrentTime(8)">(56:29)</a>
* Shader mixer: Bulk adding properties <a href="javascript:void(0);" onclick="setCurrentTime(9)">(58:01)</a>
* Shader mixer: How to set up the rotating texture <a href="javascript:void(0);" onclick="setCurrentTime(10)">(01:01:08)</a>
* Shader mixer: How to import your own custom MDL, and layering materials <a href="javascript:void(0);" onclick="setCurrentTime(11)">(01:11:32)</a>
* Shader mixer: Q&A creating mappable properties <a href="javascript:void(0);" onclick="setCurrentTime(12)">(01:20:20)</a>
