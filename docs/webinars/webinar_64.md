# 64 | Webinar - February 22, 2019
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
          videoId: 'tZtTJeKvV-c',
        });
      }
    
    function setCurrentTime(slideNum) {
    var object = [0, 15, 244, 570, 695, 930, 1157, 1573, 1778]
    player.seekTo(object[slideNum]);
  }
</script>
    
## Timestamps
* Mesh Resolution settings <a href="javascript:void(0);" onclick="setCurrentTime(0)">(00:00)</a>
* Subdivision Algorithm <a href="javascript:void(0);" onclick="setCurrentTime(1)">(00:15)</a>
* Weightmapping Subdivision <a href="javascript:void(0);" onclick="setCurrentTime(2)">(04:04)</a>
* Edge Interpolation <a href="javascript:void(0);" onclick="setCurrentTime(3)">(09:30)</a>
* Subdivision Normals <a href="javascript:void(0);" onclick="setCurrentTime(4)">(11:35)</a>
* dForce Strand Based Hair <a href="javascript:void(0);" onclick="setCurrentTime(5)">(15:30)</a>
* Reset styling, saving states, max length (Strand hair interface) <a href="javascript:void(0);" onclick="setCurrentTime(6)">(19:17)</a>
* Saving for redistribution <a href="javascript:void(0);" onclick="setCurrentTime(7)">(26:13)</a>
* Converting hair created in other software (LAMH example) <a href="javascript:void(0);" onclick="setCurrentTime(8)">(29:38)</a>
