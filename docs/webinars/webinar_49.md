# 49 | Webinar - June 14, 2018
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
          videoId: 'qgQAI9VXtVw',
        });
      }
    
    function setCurrentTime(slideNum) {
    var object = [100, 982, 2515, 3180, 3582]
    player.seekTo(object[slideNum]);
  }
</script>
    
## Timestamps
* Commercial 3D printing license proposal (guest speaker DAZ Brian ) <a href="javascript:void(0);" onclick="setCurrentTime(0)">(01:40)</a>
* Methods and tips for reusing custom morphs <a href="javascript:void(0);" onclick="setCurrentTime(1)">(16:22)</a>
* Daz Studio Instances <a href="javascript:void(0);" onclick="setCurrentTime(2)">(41:55)</a>
* Character presets: How to set Post Load settings correctly <a href="javascript:void(0);" onclick="setCurrentTime(3)">(53:00)</a>
* Using Decal Nodes to apply Iray textures to both sides of a mesh <a href="javascript:void(0);" onclick="setCurrentTime(4)">(59:42)</a>
