<!------------------------------------------------------------>
<!--      GISDay UW 2014 - Getting into UAV’s for under $700--> 
<!--      and having fun every step of the way!             -->
<!--      Target talk time - 20 min + 5 min questions       -->
<!------------------------------------------------------------>


<!------------------------------------------------------------>
<!-- Topic: Title slide -->

<iframe width="640" height="480" src="https://sketchfab.com/models/6ea595564fcc4b82b372015c7a06e81b/embed" frameborder="0" allowfullscreen mozallowfullscreen="true" webkitallowfullscreen="true" onmousewheel=""></iframe>

<!--img style="max-height: 300px;" src="images/quadcopter_cover.png"-->
<h2>Getting into UAV’s for under $700</h2>
<h4>...and having fun every step of the way!</h4>
<p>
    <small>Aaron Racicot - <a href="mailto:aaronr@z-pulley.com">aaronr@z-pulley.com</a>
<br>
<a href="http://reprojected.com">reprojected.com</a> / <a href="http://twitter.com/reprojected">@reprojected</a> 
<br>
<a href="https://github.com/aaronr">github.com/aaronr</a>
<br><br>
<a href="http://aaronr.github.io/uw-gisday-2014">aaronr.github.io/uw-gisday-2014</a>
</small>
</p>

<!------------------------------------------------------------>
--SLIDE--
<!-- Topic: Introduce myself -->

  <h3>Computer Science (UW Alum!)</h3>
  <h2><span style="color:#ff0000;">Bridging the Gap</span></h2>
  <h3>Environmental Science</h3>

--SUBSLIDE--

<img src="images/whoami.png">


<!------------------------------------------------------------>
--SLIDE--
<!-- Topic: How did we get here ... -->

How did we get here?

--SUBSLIDE--

<img style="max-height: 450px;" src="images/shean.png">
<br>
David Shean "Ice Man"
<br>
<small>http://psc.apl.washington.edu/wordpress/people/students/david-shean/</small>

--SUBSLIDE--

<img style="max-height: 450px;" src="images/google_quad.png">
<br>
CUGOS "Google Guys"

--SUBSLIDE--

<img style="max-height: 450px;" src="images/jumpline_90.png">
<br>
Video the bikes!


<!------------------------------------------------------------>
--SLIDE--
<!-- Topic: Hardware setup ... -->

Hardware options...

--SUBSLIDE--

<img style="max-height: 450px;" src="images/hack_quad.jpg">
<br>
Fully DIY

--SUBSLIDE--

<img style="max-height: 450px;" src="images/big_drone.jpg">
<br>
Big Crazy Scary

--SUBSLIDE--

I choose low cost RTF (Ready To Fly) and then Hack It!

--SUBSLIDE--

<img style="max-height: 450px;" src="images/phantom_fc40.jpg">
<br>
Phantom FC40 (~$450)

--SUBSLIDE--

<img style="max-height: 450px;" src="images/fc40_camera.jpg">
<br>
FPV camera (FC40)(720p)

--SUBSLIDE--

<img style="max-height: 450px;" src="images/canon.jpg">
<br>
Canon (elph 130 16MP) downward facing (CHDK) (~$130)

--SUBSLIDE--

<img style="max-height: 450px;" src="images/flytrex.jpg">
<br>
Flytrex Data Logger (~$50)

--SUBSLIDE--

<img style="max-height: 450px;" src="images/chdk.png">
<br>
CHDK

--SUBSLIDE--

<img style="max-height: 450px;" src="images/extra.jpg">
<br>
Prop Guards + Extra battery + Camera mount(~$50)

--SUBSLIDE--

<img style="max-height: 450px;" src="images/z-pulley_phantom.jpg">
<br>
"The Rig"

--SUBSLIDE--

<img style="max-height: 450px;" src="images/gimbal.jpg">
<br>
Gimbal

--SUBSLIDE--

<img style="max-height: 450px;" src="images/hack.jpg">
<br>
Hack

<!------------------------------------------------------------>
--SLIDE--
<!-- Topic: Why is this so interesting now ... -->

Why is this so interesting now...
<p><img style="max-height: 450px;" src="images/price_drop.jpg"></p>
<p>$$$$$ Cheap $$$$$</p>

--SUBSLIDE--

<img style="max-height: 450px;" src="images/maps_fun.jpg">
<br>
Technology is easy to use

--SUBSLIDE--

<h1>FUN!</h1>

<!------------------------------------------------------------>
--SLIDE--
<!-- Topic: Is it legal ... -->

<iframe width="100%" height="500px" frameBorder="0" src="https://www.mapbox.com/drone/no-fly/#10/45.4818/-122.6658"></iframe>
Where is it OK to fly
<br>
https://www.mapbox.com/drone/no-fly/

--SUBSLIDE--

<img style="max-height: 450px;" src="images/dos-and-donts.png">

<!------------------------------------------------------------>
--SLIDE--
<!-- Topic: Example captured before talk ... -->

<iframe width="560" height="315" src="//www.youtube.com/embed/8q7gg41LHik?list=UU1gRk1Hq5i97tCpto0E7Reg" frameborder="0" allowfullscreen></iframe>
<br>
Video taken a few minutes before talk...

<!------------------------------------------------------------>
--SLIDE--
<!-- Topic: Interesting workflows ... -->

<h2><span style="color:#ff0000;">Workflow #1</span></h2>
Panoramic image stitching

--SUBSLIDE--

<img style="max-height: 450px;" src="images/google.png">
<br>
... as good as Google gets

--SUBSLIDE--

<img style="max-height: 450px;" src="images/single.jpg">
<br>
200 of these

--SUBSLIDE--

<img style="max-height: 450px;" src="images/ice.png">
<br>
ICE

--SUBSLIDE--

<img style="max-height: 450px;" src="images/2ndstreet_stitch_small.jpg">

--SUBSLIDE--

<img style="max-height: 450px;" src="images/agisoft_stitch.png">
<br>
AgiSoft

--SUBSLIDE--

<img style="max-height: 450px;" src="images/photoscan_stitch_180_small.jpg">

<!------------------------------------------------------------>
--SLIDE--
<!-- Topic: Interesting workflows ... -->

<h2><span style="color:#ff0000;">Workflow #2</span></h2>
OSM data creation / Web Maps

--SUBSLIDE--

<img style="max-height: 450px;" src="images/qgis.png">
<br>
QGIS Warper

--SUBSLIDE--

<img style="max-height: 450px;" src="images/mapknitter1.png">
<br>
MapKnitter
http://mapknitter.org/

--SUBSLIDE--

<img style="max-height: 450px;" src="images/mapknitter2.png">
<br>

--SUBSLIDE--

<pre><code>
nearblack -of GTiff -setalpha -o outfile infile
</code></pre>

--SUBSLIDE--

<pre><code>
gdal2tiles.py --profile=mercator -z 1-22 yourmap.tif outputfolder
</code></pre>

--SUBSLIDE--

<pre><code>
git checkout gh-pages
git add outputfolder
git commit -m "Yes... TILE DATA"
git push
</code></pre>

--SUBSLIDE--

http://langleywa.github.io/gisdata/tiles/langley-2nd-street-2014/21/335500/1368498.png
<br>
<img style="max-height: 450px;" src="images/tile.png">

--SUBSLIDE--

<img style="max-height: 450px;" src="images/langley_test_app_stitch.png">
<br>
Tiles into your App!

--SUBSLIDE--

<img style="max-height: 450px;" src="images/id.png">
<br>
Edit in OSM
http://ideditor.com/
https://www.openstreetmap.org/edit?editor=id#map=19/48.03979/-122.40668
<small>http://langleywa.github.io/gisdata/tiles/langley-2nd-street-2014-tms/{z}/{x}/{y}.png</small>


<!------------------------------------------------------------>
--SLIDE--
<!-- Topic: Interesting workflows ... -->

<h2><span style="color:#ff0000;">Workflow #3</span></h2>
3D from Structure from Motion (SFM)

--SUBSLIDE--

<img style="max-height: 450px;" src="images/image_load.jpg">
<br>
Load image batches

--SUBSLIDE--

<img style="max-height: 450px;" src="images/match.png">
<br>
Matching

--SUBSLIDE--

<img style="max-height: 450px;" src="images/vsfm_sparse.png">
<br>
Visual SFM
<br>
Sparse Point Cloud

--SUBSLIDE--

<img style="max-height: 450px;" src="images/vsfm_dense.png">
<br>
Dense Point Cloud

--SUBSLIDE--

<img style="max-height: 450px;" src="images/meshlab_ply.png">
<br>
MeshLab

--SUBSLIDE--

<img style="max-height: 450px;" src="images/meshlab_texture.png">

--SUBSLIDE--

<img style="max-height: 450px;" src="images/photoscan_image_sparse.png">
<br>
AgiSoft
<br>
Sparse Point Cloud

--SUBSLIDE--

<img style="max-height: 450px;" src="images/photoscan_image_dense.png">
<br>
Dense Point Cloud

--SUBSLIDE--

<img style="max-height: 650px;" src="images/photoscan_image_texture.png">
<br>
Textured Mesh


<!------------------------------------------------------------>
--SLIDE--
<!-- Topic: Examples ... -->

<h2><span style="color:#ff0000;">More Examples</span></h2>

--SUBSLIDE--

<img style="max-height: 450px;" src="images/pipes1.jpg">
<br>
Flying Brightwater Treatment Plant

--SUBSLIDE--

<img style="max-height: 450px;" src="images/pipes2.jpg">
<br>
Flight Paths

--SUBSLIDE--

<img style="max-height: 450px;" src="images/pipes3.jpg">
<br>
Photoscan SFM Rendering

--SUBSLIDE--

<img style="max-height: 450px;" src="images/chewy_textured.png">
<br>
Chewy

--SUBSLIDE--

<img style="max-height: 450px;" src="images/school.png">
<br>
School

--SUBSLIDE--

<img style="max-height: 450px;" src="images/farm.png">
<br>
Farm

--SUBSLIDE--

<img style="max-height: 450px;" src="images/ps_vsfm_compare.png">
<br>
Compare (PhotoScan vs VSFM)


<!------------------------------------------------------------>
--SLIDE--
<!-- Topic: Future ... -->

<h2><span style="color:#ff0000;">The Future</span></h2>
Automation, DEM's, 3D printing, etc

--SUBSLIDE--

<img style="max-height: 450px;" src="images/opendronemap.png">
<br>
Automation (OpenDroneMap)

--SUBSLIDE--

<img style="max-height: 450px;" src="images/opendronemap_workinghard.png">
<br>
OpenDroneMap working hard!

--SUBSLIDE--

<img style="max-height: 450px;" src="images/dem.png">
<br>
DEM's

--SUBSLIDE--

<img style="max-height: 450px;" src="images/chris_building.jpg">
<br>
3D Print Example (Chris Schmidt)

--SUBSLIDE--

<img style="max-height: 450px;" src="images/chris_building_point.jpg">
<br>
Point Cloud

--SUBSLIDE--

<img style="max-height: 450px;" src="images/chris_building_mesh.jpg">
<br>
Mesh

--SUBSLIDE--

<img style="max-height: 450px;" src="images/chris_building_preprint.jpg">
<br>
Print Prep

--SUBSLIDE--

<img style="max-height: 450px;" src="images/chris_building_print.jpg">
<br>
Print!

<!------------------------------------------------------------>
--SLIDE--
<!-- Topic: Thank You -->

<img style="max-height: 150px;" src="images/z-pulley.png"><h1>Thank You !!!</h1><img style="max-height: 150px;" src="images/cugos.png">

