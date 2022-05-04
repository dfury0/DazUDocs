# 12 | Webinar - October 6, 2017
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
          videoId: 'DrYJ6l_dvb8',
        });
      }
    
    function setCurrentTime(slideNum) {
    var object = [0, 293, 745, 880, 1585, 1645, 1585, 1745, 2085, 2234, 4404, 4704, 4803]
    player.seekTo(object[slideNum]);
  }
</script>
    
## Timestamps
* Emissive property masks <a href="javascript:void(0);" onclick="setCurrentTime(0)">(00:00)</a>
* Iray Surface Subdivision <a href="javascript:void(0);" onclick="setCurrentTime(1)">(04:53)</a>
* Base/High Resolution levels <a href="javascript:void(0);" onclick="setCurrentTime(2)">(12:25)</a>
* Q&A: Surface SubD and GoZ <a href="javascript:void(0);" onclick="setCurrentTime(3)">(14:40)</a>
* dForce <a href="javascript:void(0);" onclick="setCurrentTime(4)">(26:25)</a>
* dForce with smoothing & SubD <a href="javascript:void(0);" onclick="setCurrentTime(5)">(27:25)</a>
* dForce Collision offset <a href="javascript:void(0);" onclick="setCurrentTime(6)">(26:25)</a>
* dForce Polygon count <a href="javascript:void(0);" onclick="setCurrentTime(7)">(29:05)</a>
* dForce Edge rest length morphs <a href="javascript:void(0);" onclick="setCurrentTime(8)">(34:45)</a>
* dForce New features (Dynamic Surface Add-On, Velocity Smoothing) <a href="javascript:void(0);" onclick="setCurrentTime(9)">(37:14)</a>
* dForce Q&A: skirts, texture distortion, JCM's, <a href="javascript:void(0);" onclick="setCurrentTime(10)">(01:13:24)</a>
* Q&A: Height FBM's <a href="javascript:void(0);" onclick="setCurrentTime(11)">(01:18:24)</a>
* dForce Q&A: Shape effect on simulation, edge rest length morphs, <a href="javascript:void(0);" onclick="setCurrentTime(12)">(01:20:03)</a>
