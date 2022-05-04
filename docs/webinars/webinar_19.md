# 19 | Webinar - November 2, 2017
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
          videoId: 'oe6vnm1HkEI',
        });
      }
    
    function setCurrentTime(slideNum) {
    var object = [0, 330, 587, 1535, 1682, 2147, 2214, 2596, 3496]
    player.seekTo(object[slideNum]);
  }
</script>
    
## Timestamps
* Hexagon testing <a href="javascript:void(0);" onclick="setCurrentTime(0)">(00:00)</a>
* Q&A: Using non-PA promo artist <a href="javascript:void(0);" onclick="setCurrentTime(1)">(05:30)</a>
* Subdivision weights <a href="javascript:void(0);" onclick="setCurrentTime(2)">(09:47)</a>
* Tips for speeding up viewport drawing <a href="javascript:void(0);" onclick="setCurrentTime(3)">(25:35)</a>
* Viewport Group Nodes and Nulls <a href="javascript:void(0);" onclick="setCurrentTime(4)">(28:02)</a>
* Viewport Preferences options <a href="javascript:void(0);" onclick="setCurrentTime(5)">(35:47)</a>
* Viewport sectional planes     <a href="javascript:void(0);" onclick="setCurrentTime(6)">(36:54)</a>
* Daz Studio scripting samples <a href="javascript:void(0);" onclick="setCurrentTime(7)">(43:16)</a>
* New Hierarchical materials preset script <a href="javascript:void(0);" onclick="setCurrentTime(8)">(58:16)</a>
