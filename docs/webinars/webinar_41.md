# 40 | Webinar - March 29, 2018
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
          videoId: 'RCHip4VSgto',
        });
      }
    
    function setCurrentTime(slideNum) {
    var object = [24, 338, 835, 1597, 2152, 2760, 2975, 3195, 3412]
    player.seekTo(object[slideNum]);
  }
</script>
    
## Timestamps
* Rigidity Maps <a href="javascript:void(0);" onclick="setCurrentTime(0)">(00:24)</a>
* Iray Surface Weighted Mode <a href="javascript:void(0);" onclick="setCurrentTime(1)">(05:38)</a>
* Push Modifiers <a href="javascript:void(0);" onclick="setCurrentTime(2)">(13:55)</a>
* Color Picker <a href="javascript:void(0);" onclick="setCurrentTime(3)">(26:37)</a>
* Control Bones <a href="javascript:void(0);" onclick="setCurrentTime(4)">(35:52)</a>
* Saving SubD weighted imported objects <a href="javascript:void(0);" onclick="setCurrentTime(5)">(46:00)</a>
* Rigid Follow Nodes & material presets <a href="javascript:void(0);" onclick="setCurrentTime(6)">(49:35)</a>
* Rigidity Group as an alternative to Rigid Follow Nodes <a href="javascript:void(0);" onclick="setCurrentTime(7)">(53:15)</a>
* Following JCMs <a href="javascript:void(0);" onclick="setCurrentTime(8)">(56:52)</a>
