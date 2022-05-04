# 05 | Webinar - September 12, 2017
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
          videoId: 'zU-Ta_lrURU',
        });
      }
    
    function setCurrentTime(slideNum) {
    var object = [0, 605, 778, 1105, 1192, 1541, 2015, 2565, 2778, 2983, 3080, 3260, 3490, 3645, 3817, 4149, 4210, 4635, 4789]
    player.seekTo(object[slideNum]);
  }
</script>
    
## Timestamps
* dForce. Demonstration of simulation on a rigged dress including: <a href="javascript:void(0);" onclick="setCurrentTime(0)">(00:00)</a>
* Goals for clothing content creation <a href="javascript:void(0);" onclick="setCurrentTime(1)">(10:05)</a>
* Comment on QA standards <a href="javascript:void(0);" onclick="setCurrentTime(2)">(12:58)</a>
* Q&A comment on workflow to create a dForce garment <a href="javascript:void(0);" onclick="setCurrentTime(3)">(18:25)</a>
* Surfaces Tab simulation settings <a href="javascript:void(0);" onclick="setCurrentTime(4)">(19:52)</a>
* dForce Modifier Weights <a href="javascript:void(0);" onclick="setCurrentTime(5)">(25:41)</a>
* Edge length morphs <a href="javascript:void(0);" onclick="setCurrentTime(6)">(33:35)</a>
* Q&A goal of dForce in content creation for end user <a href="javascript:void(0);" onclick="setCurrentTime(7)">(42:45)</a>
* Q&A JCMs and dForce <a href="javascript:void(0);" onclick="setCurrentTime(8)">(46:18)</a>
* Hiding geometry in a simulation <a href="javascript:void(0);" onclick="setCurrentTime(9)">(49:43)</a>
* Q&A on creating two product versions <a href="javascript:void(0);" onclick="setCurrentTime(10)">(51:20)</a>
* Chatbox Q&A (displayed) <a href="javascript:void(0);" onclick="setCurrentTime(11)">(54:20)</a>
* *Cloth density <a href="javascript:void(0);" onclick="setCurrentTime(12)">(58:10)</a>
* Q&A on testing with poses <a href="javascript:void(0);" onclick="setCurrentTime(13)">(01:00:45)</a>
* *Example of modification on a material zone <a href="javascript:void(0);" onclick="setCurrentTime(14)">(01:03:37)</a>
* Q&A Shrinking versus reducing stretchiness <a href="javascript:void(0);" onclick="setCurrentTime(15)">(01:09:09)</a>
* Q&A Weightmaps for fabric density <a href="javascript:void(0);" onclick="setCurrentTime(16)">(01:10:10)</a>
* Q&A on including Tris <a href="javascript:void(0);" onclick="setCurrentTime(17)">(01:17:15)</a>
* Q&A Using the GoZ plugin <a href="javascript:void(0);" onclick="setCurrentTime(18)">(01:19:49)</a>

## Note
*Examples being shown live of results in render pane are not showing in recording*.
In this webinar we talked about QA standards for dForce cloth. Specifically, the question of Triangles versus Quads came up. We stated that our official line is that we prefer meshes that are mostly quads and any dForce content that DAZ is commissioning or buying out cannot be primarily made up of tris. We have decided to revise that statement. There are cases where meshes made of tris will work as well as or even better than quads and that our proposed policy of saying that we will accept only quads for Daz originals is probably too narrow. Therefore, we are revising our policy to be based strictly on results. While we recognize that triangulated meshes won't support shear functionality, they will support draping and bends for certain fabric simulation types better than quads. Bottom line...we are backing off of saying we will not accept triangulated meshes... and we ARE saying that the mesh makeup must be consistent with the cloth or material type being simulated. Sometimes that will be tris.. .and sometimes it will be quads... or a combination of the two. 