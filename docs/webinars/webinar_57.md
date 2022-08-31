# 57 | Webinar - September 20, 2018
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
          videoId: 'Trl8UZAuwuE',
        });
      }
    
    function setCurrentTime(slideNum) {
    var object = [0, 110, 222, 370, 654, 1298, 1890]
    player.seekTo(object[slideNum]);
  }
</script>
    
## Timestamps
* OnSync Update <a href="javascript:void(0);" onclick="setCurrentTime(0)">(00:00)</a>
* New Save Filter Templates <a href="javascript:void(0);" onclick="setCurrentTime(1)">(01:50)</a>
* how to create a ‘Save’ template <a href="javascript:void(0);" onclick="setCurrentTime(2)">(03:42)</a>
* The ‘Apply’ template <a href="javascript:void(0);" onclick="setCurrentTime(3)">(06:10)</a>
* Hierarchical presets <a href="javascript:void(0);" onclick="setCurrentTime(4)">(10:54)</a>
* The ‘Batch’ template, converting files <a href="javascript:void(0);" onclick="setCurrentTime(5)">(21:38)</a>
* dForce: Dynamic Surface Add-On script update and ways of adding buttons or other rigid items <a href="javascript:void(0);" onclick="setCurrentTime(6)">(31:30)</a>

Scripts linked in this webinar:

* [Saving Template](http://docs.daz3d.com/doku.php/public/software/dazstudio/4/referenceguide/scripting/api_reference/samples/file_io/savefilter_template_save/start)
* [Applying Template](http://docs.daz3d.com/doku.php/public/software/dazstudio/4/referenceguide/scripting/api_reference/samples/file_io/savefilter_template_apply/start)
* [Batch Applying Template](http://docs.daz3d.com/doku.php/public/software/dazstudio/4/referenceguide/scripting/api_reference/samples/file_io/savefilter_template_batch/start)