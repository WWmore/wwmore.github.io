---
layout: page
title: Origami shell
description: Origami model built in AAG2023 workshop
img: assets/img/proj12/3.png
importance: 2
category: work
---

------

During the first two days of the [Advances in Architectural Geometry (AAG2023)](http://aag2023.com) conference held from 4-7 Oct. in Stuggart, I attent the Structural Origami workshop, which was led by Tomohiro Tachi, Rupert Maleczek and Yves Klett, and finished this Origami shell model.


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/proj12/1.png" title="example image" class="img-fluid rounded z-depth-1" zoomable=true%}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/proj12/4.png" title="example image" class="img-fluid rounded z-depth-1" zoomable=true%}
    </div>
</div>
<div class="caption">
    Left: The flat patterns show the 'periodic' trends of the curves. After folding along these curved creases, the model presents the montains and valleys in the convex '凸' and concave '凹' ways, which shows more interesting characteristics compared with the common  <a href="https://www.archdaily.com/881743/paneum-center-coop-himmelb-l-au" target="\_blank"> Curved Pleat Structures</a>.
    Right: There is a lot of degrees of freedom to transform the model isometrically. Here is one state, which shows higher stiffness and stability.
</div>


##### Design

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/proj12/ani_compress_20panel_2D.gif" title="example image" class="img-fluid rounded z-depth-1" zoomable=true%}
    </div>
</div>
<div class="caption">
    The 2D pattern is designed in a parametric way. Starting from two scaled ellipses, we can adjust the position and size of the central ellipse, then the corresponding designed curved patterns follow. Export the file from Rhino to be a .svg file. 
</div>



##### Simulation

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/proj12/ani_compress_20panel_3D.gif" title="example image" class="img-fluid rounded z-depth-1" zoomable=true%}
    </div>
</div>
<div class="caption">
    The curved folding process can be simulated by the online algorithm <a href="https://origamisimulator.org/" target="\_blank"> 'Origami Simulator'</a> . The converged result shows the similarity to the model.
</div>


A research paper will be discussed in the near future.
