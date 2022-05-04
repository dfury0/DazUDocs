# 33 | Webinar - February 1, 2018
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
          videoId: '7u9zqudGpLQ',
        });
      }
    
    function setCurrentTime(slideNum) {
    var object = [270, 322, 2253, 4523]
    player.seekTo(object[slideNum]);
  }
</script>
    
## Timestamps
* PA Portal sales reports <a href="javascript:void(0);" onclick="setCurrentTime(0)">(04:30)</a>
* Pre-release files <a href="javascript:void(0);" onclick="setCurrentTime(1)">(05:22)</a>
* Daz Promo Requirements <a href="javascript:void(0);" onclick="setCurrentTime(2)">(37:33)</a>
* New Post Denoiser Filter <a href="javascript:void(0);" onclick="setCurrentTime(3)">(01:15:23)</a>
