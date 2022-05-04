# 04 | Webinar - September 8, 2017
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
          videoId: 'iW28abZgLNI',
        });
      }
    
    function setCurrentTime(slideNum) {
    var object = [370, 665, 720, 1230, 2795, 2880, 2915, 3350, 3517, 3590, 3615, 3672]
    player.seekTo(object[slideNum]);
  }
</script>
    
## Timestamps
* Q&A Hiding tiling on textures (not very clear what's been asked in this section) <a href="javascript:void(0);" onclick="setCurrentTime(0)">(06:10)</a>
* Comment on vertex shading <a href="javascript:void(0);" onclick="setCurrentTime(1)">(11:05)</a>
* Iray multiple layer shader demo <a href="javascript:void(0);" onclick="setCurrentTime(2)">(12:00)</a>
* Scripting in Daz Studio <a href="javascript:void(0);" onclick="setCurrentTime(3)">(20:30)</a>
* Including Readme files and helper icon <a href="javascript:void(0);" onclick="setCurrentTime(4)">(46:35)</a>
* Accessing Scripting documentation via the IDE <a href="javascript:void(0);" onclick="setCurrentTime(5)">(48:00)</a>
* Multi rotation JCMs script <a href="javascript:void(0);" onclick="setCurrentTime(6)">(48:35)</a>
* Comment on rigging long dresses <a href="javascript:void(0);" onclick="setCurrentTime(7)">(55:50)</a>
* Q&A on the Iray multiple layer shader tiling <a href="javascript:void(0);" onclick="setCurrentTime(8)">(58:37)</a>
* Q&A removing shadows in Iray <a href="javascript:void(0);" onclick="setCurrentTime(9)">(59:50)</a>
* Q&A on tiling in 3DL <a href="javascript:void(0);" onclick="setCurrentTime(10)">(01:00:15)</a>
* How to create clothing templates <a href="javascript:void(0);" onclick="setCurrentTime(11)">(01:01:12)</a>

## Note
In this webinar we spoke about an Iray shader preset that provides a base layer and 3 additional layers. The files can be [downloaded by clicking here.](https://d59663a0-3d2c-4bbc-bdfd-eb519f5c38a3.filesusr.com/archives/d9745d_3bf429ef8dba48698303f8604ab1486c.zip?dn=3LayerSample.zip) Feel free to use the preset in your products.