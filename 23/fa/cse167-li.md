
<h2>UCSD CSE 167 Computer Graphics</h2>

<!-- https://www.w3schools.com/howto/howto_js_slideshow.asp -->
<!-- Slideshow container -->
<div class="slideshow-container">
  <!-- Full-width images with number and caption text -->
  <div class="mySlides" style="display: block;">
    <img src="imgs/hw_1_3.jpg" style="height:400px; display: block; margin-left: auto; margin-right: auto;">
    <div class="text">2D Graphics</div>
  </div>

  <div class="mySlides" style="display: none;">
    <img src="imgs/hw_1_6.jpg" style="height:400px; display: block; margin-left: auto; margin-right: auto;">
    <div class="text">Transparency</div>
  </div>

  <div class="mySlides" style="display: none;">
    <img src="imgs/hw_2_4_two_shapes.jpg" style="height:400px; display: block; margin-left: auto; margin-right: auto;">
    <div class="text">3D Graphics</div>
  </div>

  <div class="mySlides" style="display: none;">
    <img src="imgs/hw_3_3_teapot.jpg" style="height:400px; display: block; margin-left: auto; margin-right: auto;">
    <div class="text">OpenGL</div>
  </div>

  <div class="mySlides" style="display: none;">
    <img src="imgs/hw_3_4_bunny.jpg" style="height:400px; display: block; margin-left: auto; margin-right: auto;">
    <div class="text">Lighting</div>
  </div>

  <div class="mySlides" style="display: none;">
    <img src="imgs/hw_4.jpg" style="height:400px; display: block; margin-left: auto; margin-right: auto;">
    <div class="text">3D modeling in Blender</div>
  </div>

  <div class="mySlides" style="display: none;">
    <img src="imgs/hw_5.gif" style="height:400px; display: block; margin-left: auto; margin-right: auto;">
    <div class="text">Boids animation</div>
  </div>

  <!-- Next and previous buttons -->
  <a class="prev" onclick="plusSlides(-1)">❮</a>
  <a class="next" onclick="plusSlides(1)">❯</a>
</div>
<br>

<!-- The dots/circles -->
<div>
  <span class="dot active" onclick="currentSlide(1)"></span>
  <span class="dot" onclick="currentSlide(2)"></span>
  <span class="dot" onclick="currentSlide(3)"></span>
  <span class="dot" onclick="currentSlide(4)"></span>
  <span class="dot" onclick="currentSlide(5)"></span>
  <span class="dot" onclick="currentSlide(6)"></span>
  <span class="dot" onclick="currentSlide(7)"></span>
</div>

<br>
<h3> Course Description </h3>
<div>
Computer graphics is a field about processing ``visual data'', including images, videos, 2D and 3D shapes, light and reflection, motion, physical properties, and many more. Throughout the course, we will learn about:
<ul>
  <li><b>Modeling</b>: How to describe and edit 2D and 3D shapes.</li>
  <li><b>Rendering</b>: How to turn 2D and 3D shapes into images algorithmically, and how to make it fast using domain-specific hardware.</li>
  <li><b>Animation</b>: How to create motion.</li>
</ul>

<div>You can take a look at previous CSE 167 web pages (either <a href="https://cseweb.ucsd.edu/~alchern/teaching/cse167_fa22/" target="_blank">Albert Chern's version</a> or <a href="https://cseweb.ucsd.edu/~viscomp/classes/cse167/wi23/index.html" target="_blank">Ravi Ramamoorthi's version</a>) to have a better sense of what the course is about. This course is also offered on MOOC and UCSD Online by Ravi Ramamoorthi. You are free to look at Ravi's lectures, but my lecturing style would be slightly different. While I will cover most contents covered by Albert and Ravi, the order and details might be different. </div>
<br>
<div>This course is only the tip of an iceburg of a fascinating field. If you are interested in computer graphics, you should look the more advanced materials in CSE 168 for rendering (either <a href="https://cseweb.ucsd.edu/~tzli/cse168/" target="_blank">my version</a> or <a href="https://cseweb.ucsd.edu/~viscomp/classes/cse168/sp21/168.html" target="_blank">Ravi's version</a>), <a href="https://cseweb.ucsd.edu/classes/wi20/cse169-a/index.html">CSE 169</a> for animation, <a href="http://ivl.calit2.net/wiki/index.php/CSE190S2021">CSE 191 B</a>: for virtual reality and <a href="http://ivl.calit2.net/wiki/index.php/CSE165W2021">CSE 165</a> for user interaction. </div>
<br>
<div>
For graduate students, <a href="https://cseweb.ucsd.edu/~tzli/cse272/">CSE 272</a>, <a href="https://cseweb.ucsd.edu/classes/wi22/cse273-a/">CSE 273</a>, <a href="https://cseweb.ucsd.edu/~viscomp/classes/cse274/fa21/274.html">CSE 274: Sampling and Reconstruction of Visual Appearance</a>, <a href="https://cseweb.ucsd.edu/~alchern/teaching/cse274_wi22/">CSE 274: Discrete Differential Geometry</a>, <a href="https://haosulab.github.io/ml-meets-geometry/FA23/index.html">CSE 275</a>, and <a href="https://cseweb.ucsd.edu/~alchern/teaching/cse291_sp23">CSE 291</a> are all relevant and super cool courses.
UCSD has one of the largest faculty on graphics!
</div>

<h3> Prerequisites </h3>
(Modern) C++. Matrices and vectors.

<h3> Logistics </h3>
<div> <b>Instructor</b>: <a target="_blank" href="https://cseweb.ucsd.edu/~tzli/">Tzu-Mao Li</a> </div>
<div> <b>TA</b>: <a target="_blank" href="https://www.linkedin.com/in/trevor-hedstrom-9abb6362">Trevor Hedstrom</a> (tjhedstr-at-ucsd.edu), <a target="_blank" href="https://www.linkedin.com/in/randaldong/en">Randal Dong</a> (rudong-at-ucsd.edu), and <a target="_blank" href="https://www.linkedin.com/in/baichuan-wu-584871142/">Baichuan (Peter) Wu</a> (bwu-at-ucsd.edu) </div>
<div> <b>Lectures</b>: Monday/Wednesday/Friday 11:00am-11:50pm Pacific time. Location: PCYNH 109.</div>
<div> <b>Dicussion</b>: Friday noon-12:50pm Pacific time. Location: PCYNH 109.</div>
<div> <b>Instructor office hour</b>: Friday 3pm-4pm. Location: CSE 4116. </div>
<div> <b>TA office hour</b>: B275 Mon 3-4pm (Trevor), B275 Fri 4-5pm (Randal), B270A Thu 1-2pm (Baichuan). </div>
<div> We will do most of the online discussions on <a target="_blank" href="https://piazza.com/ucsd/fall2023/cse167_fa23_a00/home">Piazza</a>. </div>
<div> <b>Course recording</b>: We will record the class if the equipment is available. However, the class will be very interactive and you might be missing a lot of context if you are not in the classroom yourself. Please try to join us in person and let's have fun together! </div>

<h3> Grading, Homeworks and Projects </h3>

<div> There will be 5 programming homeworks (each 20%). </div>

<div>The homeworks involve quite a bit of programming and can be tough for inexperienced. Start early and ask questions!</div>
<br>
<div> <b>Late penalty</b>: score * clamp(1 - (seconds passed after midnight of the deadline day) / 86400, 0, 1) </div>
<div> (this means that after 1 day your score becomes 0! start early! no negotiation unless you get a letter from the dean.) </div>
<div> We will use the time on Canvas to determine how many seconds have passed. </div>
<br>
<div> Homeworks 1-4 will be based on the <a target="_blank" href="https://github.com/BachiLi/balboa_public">balboa</a> codebase. </div>
<br>
<div> <b>Homework 1</b> (20%): <a target="_blank" href="homework1.pdf"> 2D Graphics </a> (due 10/16) </div>
<div> <b>Homework 2</b> (20%): <a target="_blank" href="homework2.pdf"> 3D Software Rendering </a> (due 11/1) </div>
<div> <b>Homework 3</b> (20%): <a target="_blank" href="homework3.pdf"> 3D OpenGL Rendering </a> (due 11/17) </div>
<div> <b>Homework 4</b> (20%): <a target="_blank" href="homework4.pdf"> 3D Modeling </a> (due 11/29) </div>
<div> <b>Homework 5</b> (20%): <a target="_blank" href="homework5.pdf"> Boids Animation </a> (due 12/12) </div>

<br>

<div> <b> Collaboration policy: </b> You are expected to do the homeworks alone (feel free to discuss between peers!). </div>

<div> <b> ChatGPT/Co-pilot/machine generated text/code policy: </b> We do not encourage or discourage you for using ChatGPT or Co-pilot or other similar software. Pick the way you feel is the best for learning computer graphics. </div>

<h3> Readings </h3>

<div>All of these are optional.</div> <br>

<div><a href="http://15462.courses.cs.cmu.edu/fall2021/home">CMU 15-462/662</a>: a very nice (but intense) computer graphics course from Keenan Crane.</div>
<div><a href="http://immersivemath.com/ila/index.html">Immersive Linear Algebra</a>: linear algebra tutorials with interactive figures.</div>
<div><a href="https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab">Essence of Linear Algebra</a>: video tutorials of linear algebra from 3Blue1Brown</div>
<div><a href="https://www.amazon.com/Fundamentals-Computer-Graphics-Steve-Marschner/dp/1482229390">Fundamentals of Computer Graphics</a> from Steve Marschner and Peter Shirley is the standard textbook.</div>
<div><a href="https://www.amazon.com/Computer-Graphics-Principles-Practice-3rd/dp/0321399528">Computer Graphics: Principles and Practice</a> from John Hughes, Andy van Dam, Morgan McGuire, David Sklar, James Foley, Steven Feiner, and Kurt Akeley is another standard textbook.</div>
<div><a href="https://www.pbr-book.org/"> Physically-based Rendering: from Theory to Implementation</a> contains a comprehensive reference to many topics we talk about. It might be a dense read though.</div>
<div><a href="http://kesen.realtimerendering.com/">Ke-Sen's webpage</a> is where you find all the (recent) cool graphics papers!</div>

<h3> Schedule (tentative) </h3>

<h4> 9/29/2023 (Fri): Introduction. (HW 1 out) [<a href="lectures/01_why_graphics.pdf">slides</a>] </h4>
<div> Why computer graphics? Course overview.  </div>

<h4> 10/2/2023 (Mon): Vector graphics. [<a href="lectures/02_vector_graphics.pdf">slides</a>] </h4>
<div> Rasterizing 2D graphics. Antialiasing. Transparency. Bezier curves. </div>

<h4> 10/4/2023 (Wed): Linear transformation. [<a href="lectures/03_linear_transformation.pdf">slides</a>] </h4>
<div> Basic linear algebra. 2D linear transformation. Affine transformation. </div>

<h4> 10/6/2023 (Fri): Cameras. [<a href="lectures/04_cameras.pdf">slides</a>] </h4>
<div> Pinhole cameras. Field of view vs focal length. Perspective and orthographic projection. </div>

<h4> 10/9/2023 (Mon): Rasterization. [<a href="lectures/05_rasterization.pdf">slides</a>] </h4>
<div> Triangle meshes. Depth interpolation. Z buffer. Perspective-corrected interpolation. Frustrum culling. Occlusion culling. </div>

<h4> 10/11/2023 (Wed): Ray tracing vs rasterization. [<a href="lectures/06_ray_tracing.pdf">slides</a>] </h4>
<div> Z culling vs acceleration structures. </div>

<h4> 10/13/2023 (Fri): 3D transformation. [<a href="lectures/07_3d_transformation.pdf">slides</a>] </h4>
<div> Homogeneous coordinates. Scene graphs. </div>

<h4> 10/16/2023 (Mon): 3D rotation. (HW1 due, HW2 out) [<a href="lectures/08_3d_rotation.pdf">slides</a>] </h4>
<div> Euler angles. Axis-angle representation. Quaternion/Rotors. </div>

<h4> 10/18/2023 (Wed): Programmable graphics pipelines. [<a href="lectures/09_graphics_pipeline.pdf">slides</a>] </h4>
<div> GPU architecture. Fixed-function pipeline. Vertex shaders. Fragment shaders. </div>

<h4> 10/20/2023 (Fri): Textures. [<a href="lectures/10_textures.pdf">slides</a>] </h4>
<div> Image textures. Procedural textures. UV mapping. Mipmapping. </div>

<h4> 10/23/2023 (Mon): Lighting. [<a href="lectures/11_lighting.pdf">slides</a>] </h4>
<div> Ambient/diffuse/specular lighting. Shading normals. Gouraud/Phong/Deferred. </div>

<h4> 10/25/2023 (Wed): Materials. [<a href="lectures/12_materials.pdf">slides</a>] </h4>
<div> Measured BRDFs. Blinn-Phong. Microfacet BRDFs.  </div>

<h4> 10/27/2023 (Fri): Colors. [<a href="lectures/13_colors.pdf">slides</a>] </h4>
<div> Color spaces. Gamma. </div>

<h4> 10/30/2023 (Mon): Global illumination. [<a href="lectures/14_global_illumination.pdf">slides</a>] </h4>
<div> Path tracing. Radiosity. </div>

<h4> 11/1/2023 (Wed): Shadow mapping and shadow volume. (HW2 due, HW3 out) [<a href="lectures/15_shadow.pdf">slides</a>]  </h4>

<h4> 11/3/2023 (Fri): Antialiasing. [<a href="lectures/16_antialiasing.pdf">slides</a>] </h4>
<div> MSAA. FXAA. TAA. </div>

<h4> 11/6/2023 (Mon): Non-photorealistic rendering. [<a href="lectures/17_nonphotorealistic_rendering.pdf">slides</a>] </h4>
<div> Toon shading. Contours. Line drawing. </div>

<h4> 11/8/2023 (Wed): Procedural modeling. [<a href="lectures/18_procedural_modeling.pdf">slides</a>] </h4>
<div> Fractal surfaces. L-systems. Grammars. SDFs. </div>

<h4> 11/10/2023 (Fri): Veterans Day Holiday </h4>

<h4> 11/13/2023 (Mon): Geometry processing. [<a href="lectures/19_geometry_processing.pdf">slides</a>] </h4>
<div> Surface reconstruction. Mesh smoothing. Mesh simplification. Remeshing/Parameterization. </div>

<h4> 11/15/2023 (Wed): Curves and smooth surfaces. [<a href="lectures/20_curves_and_surfaces.pdf">slides</a>] </h4>
<div> Bezier cuves. B-splines. NURBS. Catmull-Clark and Loop subdivision. </div>

<h4> 11/17/2023 (Fri): Animation. (HW3 due, HW4 out) [<a href="lectures/21_animation.pdf">slides</a>] </h4>
<div> Newtonian mechanics. ODEs. Numerical integration. Forward and inverse kinematics. </div>

<h4> 11/20/2023 (Mon): Particle systems and mass-spring systems. [<a href="lectures/22_particles_and_mass_spring.pdf">slides</a>] </h4>
<div> Boids. Cloth simulation. Constrained dynamics. </div>

<h4> 11/22/2023 (Wed): Rigging, skinning, and blendshapes. [<a href="lectures/23_rigging_skinning_blendshapes.pdf">slides</a>] </h4>

<h4> 11/24/2023 (Fri): Thanksgivings holiday. </h4>

<h4> 11/27/2023 (Mon): Rigid-body simulation. [instructor was sick -- class canceled] </h4>

<h4> 11/29/2023 (Wed): Graphics systems and domain-specific languages. [<a href="lectures/25_graphics_dsl.pdf">slides</a>] </h4>

<h4> 12/1/2023 (Fri): Point-based graphics. (HW4 due, HW5 out) [instructor was sick -- class canceled] </h4>

<h4> 12/4/2023 (Mon): Transparency and volumes. [<a href="lectures/27_volume_rendering.pdf">slides</a>] </h4>
<div> Alpha compositing. Volume rendering. Ray marching. </div>

<h4> 12/6/2023 (Wed): Neural networks. [<a href="lectures/28_neural_networks.pdf">slides</a>] </h4>
<div> Representation. Inverse problems. </div>

<h4> 12/8/2023 (Fri): Sneak peak of other graphics classes. [<a href="lectures/29_sneak_peak.pdf">slides</a>] </h4>
<div> CSE 168/169 and more. </div>

<h4> 12/12/2023 (Tue): HW5 due. </h4>



</div>
