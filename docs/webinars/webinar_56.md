# 56 | Webinar - August 30, 2018
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
          videoId: 'NuoFUcFOxNc',
        });
      }
    
    function setCurrentTime(slideNum) {
    var object = [0, 795, 975, 1850, 2310, 2812, 3106]
    player.seekTo(object[slideNum]);
  }
</script>
    
## Timestamps
* dForce: Generate Polyline Dynamic Surface AddOn Script <a href="javascript:void(0);" onclick="setCurrentTime(0)">(00:00)</a>
* Shoe Creation <a href="javascript:void(0);" onclick="setCurrentTime(1)">(13:15)</a>
* QA requirements for shoe morphs & pose presets <a href="javascript:void(0);" onclick="setCurrentTime(2)">(16:15)</a>
* Creating shoe JCMs <a href="javascript:void(0);" onclick="setCurrentTime(3)">(30:50)</a>
* Fixing shoe shape morphs using Rigidity Groups & Weights <a href="javascript:void(0);" onclick="setCurrentTime(4)">(38:30)</a>
* Hiding feet geometry <a href="javascript:void(0);" onclick="setCurrentTime(5)">(46:52)</a>
* Hiding feet geometry <a href="javascript:void(0);" onclick="setCurrentTime(6)">(51:46)</a>
