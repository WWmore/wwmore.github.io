---
layout: page
title: Origami shell
description: Origami model built in AAG2023 workshop
img: assets/img/proj12/3.png
importance: 2
category: work
---

------

During the first two days of the [Advances in Architectural Geometry (AAG2023)](http://aag2023.com) conference held from October 4-7 in Stuggart, I attended the Structural Origami workshop led by Tomohiro Tachi, Rupert Maleczek and Yves Klett. I completed an Origami shell model together with Xinye Li during the workshop.
[![Twitter URL](https://img.shields.io/twitter/url/https/twitter.com/LabOrigami.svg?style=social&label=Follow%20%40LabOrigami)](https://twitter.com/LabOrigami/status/1710041520827462083)

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/proj12/1.png" title="example image" class="img-fluid rounded z-depth-1" zoomable=true%}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/proj12/4.png" title="example image" class="img-fluid rounded z-depth-1" zoomable=true%}
    </div>
</div>
<div class="caption">
    Left: The flat patterns reveal the 'periodic' trends of the curves. When folded along these curved creases, the model takes on montains and valleys in the convex '凸' and concave '凹' ways, which showcases more interesting characteristics compared to the common  <a href="https://doi.org/10.1145/3355089.3356540" target="\_blank"> Curved Pleat Structures</a>.
    Right: There are multiple degrees of freedom to transform the model isometrically. This particular state demonstrates higher stiffness and stability.
</div>


##### Design

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/proj12/ani_compress_20panel_2D.gif" title="example image" class="img-fluid rounded z-depth-1" zoomable=true%}
    </div>
</div>
<div class="caption">
    The 2D pattern is designed using a parametric approach. We begin with two scaled ellipses, and then adjust the position and size of the central ellipse. As a result, the corresponding curved patterns are designed accordingly. To export the file, we use Rhino and save it as a .svg file.
</div>



##### Simulation

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/proj12/ani_compress_20panel_3D.gif" title="example image" class="img-fluid rounded z-depth-1" zoomable=true%}
    </div>
</div>
<div class="caption">
    The curved folding process can be simulated using the online algorithm <a href="https://origamisimulator.org/" target="\_blank"> 'Origami Simulator'</a>. The results of the simulation are similar to the physical model.
</div>


A research paper on this topic will be discussed in the near future.
