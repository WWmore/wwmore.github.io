---
layout: page
title: Rectifying Strip Patterns
description: Computational design and fabrication, Shading system, Gridshell,Pseudo-geodesic, Developable strips

img: assets/img/proj11/teaser.png
importance: 1
category: work
---

------
##### <i class='fas fa-folder-open'>**Publication**</i><br/>
ACM Transactions on Graphics; 
Accepted by the **SIGGRAPH Asia 2023** conference (Dec.12-15, Sydney, Australia).

##### <i class='fas fa-laugh-beam'>**Authors**</i><br/>
Bolun Wang, Hui Wang, Eike Schling, Helmut Pottmann

##### <i class='fas fa-align-justify'>**Abstract**</i>
Straight flat strips of inextensible material can be bent into curved strips aligned with arbitrary space curves. The large shape variety of these socalled rectifying strips makes them candidates for shape modeling, especially in applications such as architecture where simple elements are preferred for the fabrication of complex shapes. In this paper, we provide computational tools for the design of shapes from rectifying strips. They can form various patterns and fulfill constraints which are required for specific applications such as gridshells or shading systems. The methodology is based on discrete models of rectifying strips, a discrete level-set formulation and optimization-based constrained mesh design and editing. We also analyse the geometry at nodes and present remarkable quadrilateral arrangements of rectifying strips with torsion-free nodes.

##### <i class='fas fa-file-pdf'>**PDF**</i>
[paper](/assets/pdf/2023SIGA.pdf)

<iframe src="/assets/pdf/2023SIGA.pdf#toolbar=0" 
width="100%" height=400 frameborder="0" style="border: none;">
</iframe>

------

##### <i class='far fa-images'>**Figures**</i>

Pseudo-geodesic curves of a surface was first studied by Walter Wunderlich in 1950. They are the curves whose osculating planes have a constant angle \\(\theta\\) with the tangent planes of the surface. 
When \\(\theta=90^o\\), they are geodesic;
when \\(\theta=0^o\\), they are asymptotic curves.


<img src="/assets/img/proj11/diagram1.png" alt="image" width="300" height="auto">


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/proj11/gif_pg_cylinder1.gif" title="example image" class="img-fluid rounded z-depth-1" zoomable=true%}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/proj11/gif_pg_cylinder2.gif" title="example image" class="img-fluid rounded z-depth-1" zoomable=true%}
    </div>
</div>
<div class="caption">
    A smooth pseugo-geodesic on a rotational cylinder can be explicitly represented by \\(x = \cos(t); y= \sin(t); z = \tan(\theta) ch(t/\tan(\theta))\\) with parameter \\(t\\).
    Left: changing interval \\(t\\). Right: changing tilt angle \\(\theta\\).
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/proj11/levelset.png" title="example image" class="img-fluid rounded z-depth-1" zoomable=true%}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/proj11/roof10_1ps45.gif" title="example image" class="img-fluid rounded z-depth-1" zoomable=true%}
    </div>
</div>
<div class="caption">
    A family of pseudo-geodesics on a mesh. Left: A family of pseudo-geodesic with \\(\theta=60^o\\) are constructed as level-sets from a triangle mesh. Right: A family of pseudo-geodesics with \\(\theta=45^o\\) are optimized from geodesics (\\(\theta=90^o\\)) of the quad mesh, where the binormals along the pseudo-geodesics form the so-called **Rectifying Strips** that are developable.
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/proj11/gif_boiler_outside_1s.gif" title="example image" class="img-fluid rounded z-depth-1" zoomable=true%}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/proj11/gif_boiler_inside_len=10_fram0-16_0.5s.gif" title="example image" class="img-fluid rounded z-depth-1" zoomable=true%}
    </div>
</div>
<div class="caption">
    The rectifying strips, materialized by metal or wodden sheets,  along the designed pseudo-geodesics on a free-form surface can be functioned as shading facades.
    Light and shadow effects with time changing from morning to afteroon. Left: outside. Right: inside view with focal lenth 10.
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/proj11/gif_soumaya_day_0.1s.gif" title="example image" class="img-fluid rounded z-depth-1" zoomable=true%}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/proj11/gif_soumaya_top.gif" title="example image" class="img-fluid rounded z-depth-1" zoomable=true%}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/proj11/gif_soumaya_outside_0.1s.gif" title="example image" class="img-fluid rounded z-depth-1" zoomable=true%}
    </div>
</div>
<div class="caption">
    Four facades of an architecture function differently. Left: lighting and shading effects with changing sunlight directions at different time. Center-Right: turn-table views.
</div>


<img src="/assets/img/proj11/diagram2.png" alt="image" width="300" height="auto">

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/proj11/gif_M2_0.1s.gif" title="example image" class="img-fluid rounded z-depth-1" zoomable=true%}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/proj11/gif_eq47.gif" title="example image" class="img-fluid rounded z-depth-1" zoomable=true%}
    </div>
</div>
<div class="caption">
    Pseudo-geodesic gridshells. Right: torsion-free rectifying strip structures.
</div>



<img src="/assets/img/proj11/diagram3.png" alt="image" width="300" height="auto">


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/proj11/AAG.png" title="example image" class="img-fluid rounded z-depth-1" zoomable=true%}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/proj11/AGG.png" title="example image" class="img-fluid rounded z-depth-1" zoomable=true%}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/proj11/gif_teaser_0.1s.gif" title="example image" class="img-fluid rounded z-depth-1" zoomable=true%}
    </div>
</div>
<div class="caption">
    Left: AAG-web. Center: AGG-web. Right: PPG-web. (Note: A = Asymptotic (blue), G = Geodesic (red), P= Pseudo-geodesic.)
</div>


------

#### <i class='fas fa-photo-video'>Video</i>

TBD...

#### <i class='fa fa-code'>Code</i>
Level-sets code see [here](https://github.com/wangbolun300/RectifyingStripPatterns).

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/proj11/levelset.gif" title="example image" class="img-fluid rounded z-depth-1" zoomable=true%}
    </div>
</div>


Quad mesh optimization code see (TBD....)




