<section>
                <h2>Information</h2>
                <center>
                    <img src="img/banner.jpg" width="100%">
                </center>
            </section>
            <section>
                <h3>Prerequisites</h3>
                <p>
CSE 168 is intended as a follow-on to CSE 167, and as such CSE 167 or
the equivalent is a pre-requisite (you should have taken 167 or
equivalent at another university, found the material interesting and
done well in the course). The course has no overlap with other advanced
computer graphics courses, such as CSE 165 and CSE 169 in winter; you are
encouraged to take this course if you enjoyed those classes last quarter.
CSE 168 is
            intended to teach advanced topics in computer graphics
            rendering, which have recently become standard in
            industry.  As such, it is a must-have course for students
            seeking further opportunities in computer graphics in
            graduate school or industry.  The course is intended to be
            of interest to MS and PhD students in graphics, vision or
            robotics, in addition to advanced undergraduates.  If you
            like this course, I would highly recommend also registering for
            the advanced graduate courses like CSE 272, 273, 274 and 291, which will be
            taught next year.
                </p>
            </section>
            <section>
                <h3>Course Format and Requirements</h3>
                <p>
            This is a regular lecture course, consisting of lectures
            on the relevant topics by the instructor. As
            opposed to CSE 167, this course is intended to have a more
            intimate feel, with a smaller class size, more in-class
            discussions and more independence and creative leeway in
            projects.  We expect you to create websites to turn in
            your work in some cases, especially if extra credit is
            involved (a new innovation is the use of UCSD Online to
            submit your images in most cases). We also do not provide
            skeleton code apart from a basic framework for those
            seeking to do real-time raytracing in OptiX.  More
            information is available in the schedule and assignments page.
                </p>
                <p>
                    Grading will be based entirely on 5 large
            programming projects. The last of these is a final project that
            provides wide flexibility in design to students to produce
            the best images. The projects will teach you how to build
            a modern path tracer for rendering, to produce realistic
            computer graphics images.  We will also cover more
            advanced topics.  For those of you adventurous enough to
            try a real-time raytracing system based on OptiX, you will
            also be able to speed up and run some of the homeworks in
            real-time.  (An Embree skeleton may also be provided after homework 1 is submitted to enable high-performance for those of you who cannot develop in OptiX).
                </p>
                <p>
                    Students are required to do all the assignments
            (this may be in groups of 2; the requirements remain
            unchanged if working alone, although we may at our
            discretion consider to a marginal extent in assigning the final
            grade.)
                    <strong>
                        Programs must be implemented entirely by
              students themselves; You may not copy source code
              from previous instances of this or a similar class,
              other students, or other online etc. resources.  <em>Please bear
              this in mind, we unfortunately have had to deal with
              cheating in previous classes where students copied from
              online resources.</em>
              You may also not post your source code publicly,
              including to github or other public repositories.
              (There are a number of online resources and softwares
              on path tracing and global illumination rendering; you
              may look at them for inspiration, but definitely not copy code.)
              AI agents like chatGPT may be used only as a search engine for example for explaining the way specific commands are used, but you should not copy code from them (and indeed, they may just be regurgitating code from previous students in any case that will expose you to to plagiarism).
                    </strong>
                </p>

<p>

To repeat, you may not copy solutions or code from other students, or students who previously took this or a similar class at a university or online. You must clearly declare any code and ideas that came directly from others, as opposed to what you created yourself. If you fail to do so, we can only assume you are presenting your own work. Of course, presenting other people's work as your own is academic dishonesty. Note also that in group assignments (if you choose to work in a group of two), you are collectively responsible for your project; both you and your partner can be held liable (just as you both receive credit for) the resulting assignment. <b> Students who engage in dishonest activities, with an intent to alter their grade, will receive an F for the course and be reported to the University for further action. Note that you will also be held liable for publicly posting your code on github or other public websites, if another student subsequently copies from it (please do not post your code on github, website or any other publicly accessible location, nor copy from any such resources you find online).</b>

To detect instances of academic integrity violations in programming assignments, we will use 3rd party software. We recommend you only include your class lab account ID (not your name or PID) in your submission codes (program files). Including your name and/or PID will disclose that information to the 3rd party.

We did have a number of cases of cheating we caught in previous offerings of this course, and we do have a listing of common online resources. Even those who used "contract cheating" found the "contract" themselves cheated from other online resources. As such, there is a high chance that cheating/copying from other students (not in your group) or online sources will be detected. <b> Similarly, you should only submit images to the grader that you have created yourself.  Efforts to maliciously interfere with grader operations will be logged and will have the sternest penalties. </b> </p>
                <p>
                    <i>
                        Please note that there is minimal hand-holding
              on the projects. They are large assignments for which
                        you are given about 2 weeks, and they cannot be done at the last moment. You will need to start early and
                        work steadily. No late days will be given except in exceptional circumstances. Since you are supposed
                        to be working steadily, turn in what you have by the deadline, even if it is not perfect. If you do have
                        extraordinary circumstances, please contact the instructor well *before* the assignment is due.<br>

              To avoid ambiguity, we will enforce a very strict late policy as follows.  There will be a 10% deduction (of your total score) for the first hour late (this will mostly just be upload and internet issues), a 25% deduction for the first 12 hours late (which will cover any last minute submissions), 50% for the first 24 hours late, and no credit if the submission is more than 24 hours late.  The reason is to encourage you to work steadily on the homework and submit what you have by the deadline.  The policy is intentionally a good deal stricter than what is typically used in 167.
                    </i>
                </p>
            </section>
            <section>
                <h3>Topics</h3>
                <p>
Topics include key aspects of computer graphics rendering, in
particular the tools to build a full path tracer.  We also discuss
            some other topics in rendering. Specifically topics include:
               </p>
                <ul>
                    <li>
                        Review of Ray Tracing
                    </li>
                    <li>
                        Global Illumination and Rendering Equation
                    </li>
                    <li>
                        Monte Carlo Integration for Direct Lighting
                    </li>
                    <li>
                        Monte Carlo Path Tracing for Global Illumination
                    </li>
                    <li>
                        (Multiple) Importance Sampling
                    </li>
                    <li>
                        Recent Advances in High Quality Rendering
                    </li>
                    <li>
                        Real-Time and Precomputation-Based Rendering
                    </li>
                    <li>
                        Image-Based Rendering and Light Fields
                    </li>

                </ul>
            </section>
            <section>
                <h3>Resources</h3>
                <p>
                    There are no books specifically required for this
            class. Readings including book chapters and papers are
            provided where needed for each lecture. Optionally, a
            comprehensive computer graphics rendering book such as
            <i> Principles of Digital Image Synthesis </i> by Andrew
            Glassner or <i> <a href="http://www.pbrt.org">PBRT</a>
            </i> (fourth edition; this book is now free in an online
            edition along with the code, and its impact in industry
            has been recognized by a technical academy award, the only
            book ever to be so recognized).
                </p>
                <p>
                    For resources on basic math, see
                    <a target="_blank" href="http://joshua.smcvt.edu/linearalgebra/">linear algebra Free Text</a>. For resources
                    on Fourier analysis, the
                    <a target="_blank" href="http://www.dspguide.com">DSP Guide</a> may be useful (for example, chapters 8-13 on
                    discrete fourier transforms). There are many other online links if you search the web.
                </p>
            </section>
            <section>
                <h3>Final Projects</h3>
                <p> See some of the best projects submitted for Spring 2021.
These include photon mapping (Yutong Zhang and separately Jesus Gutierrez), a
a recreation of Elsa's palace (Baichuan Wu and Vincent Li), and subsurface scattering (Jeremy Lin).  You can click
to access project websites (if still available), and save or bring up the images for higher resolution.   <br>
<a href="https://tonyzyt2000.github.io/en/CSE168-Final-Project/"><img src="projects/yutongzhang_PM.png" height="240"></a>
<a href="https://www.notion.so/CSE-168-Final-Project-41f19eabc15746e480b61ae3fa56c0d4"><img src="projects/jesusg_dragonPM10mill.png" height="240"></a>
<a href="https://sites.google.com/ucsd.edu/cse168-ice-castle"><img src="projects/baichuan_vincent_castle.jpg" height="240"></a>
<a href="https://serpantttine.wordpress.com/cse-168-final-project/"><img src="projects/jeremy-dragonss.png" height="185"></a>
</p>
                <p>
                    To close, I include a brief summary of the best final projects submitted for Spring 2020.  Click on the images for descriptions of the projects.  From left to right, from students Winston Durand, Karl Wang, Xuezheng Wang and Yiming Zhao.  Many of these projects involve volumetric scattering, photon mapping, depth of field and refraction. You can save or bring up the images for higher resolutions.  <br>
<a href="https://r167.github.io/embree-raytracer"><img src="projects/winstondurand.png" height="240"></a>
<a href="https://cse168.blogspot.com/2020/06/final-project-single-scattering.html"><img src="projects/karlwanghero.png" height="240"></a>
<a href="https://www.notion.so/CSE-168-Final-Project-0846e4b59b0044e591c44411ee2cc9d5"><img src="projects/xuezhenghero.png" height="240"></a>
                </p>
            </section>
