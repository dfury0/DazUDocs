# 15 | Webinar - October 18, 2017
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
          videoId: '59Sowgz8NjA',
        });
      }
    
    function setCurrentTime(slideNum) {
    var object = [117, 285, 364, 465, 965, 1137, 1402, 4443]
    player.seekTo(object[slideNum]);
  }
</script>
    
## Timestamps
* Property slider locations <a href="javascript:void(0);" onclick="setCurrentTime(0)">(01:57)</a>
* Product .PDF load script <a href="javascript:void(0);" onclick="setCurrentTime(1)">(04:45)</a>
* Character morph slider locations <a href="javascript:void(0);" onclick="setCurrentTime(2)">(06:04)</a>
* Shader Mixer: Saving the 3 layer shader sample <a href="javascript:void(0);" onclick="setCurrentTime(3)">(07:45)</a>
* Shader Mixer: Changing connection colors <a href="javascript:void(0);" onclick="setCurrentTime(4)">(16:05)</a>
* Shader Mixer: Hiding unused parameters <a href="javascript:void(0);" onclick="setCurrentTime(5)">(18:57)</a>
* dForce Dynamic Surface Add-on (tips and tricks) <a href="javascript:void(0);" onclick="setCurrentTime(6)">(23:22)</a>
* dForce Simulating clothing in sitting poses, morphs & FBMs <a href="javascript:void(0);" onclick="setCurrentTime(7)">(01:14:03)</a>
