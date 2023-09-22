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

```mermaid
graph LR
    B[1 family] --> E[Ex.: smooth on cylinder]
    B --> F[Ex.: level-set on a triangle mesh]
    B --> G[Ex.: one isoline of a quad mesh]
    B --> H[App.: shading system]
```

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/proj11/gif_pg_cylinder1.gif" title="example image" class="img-fluid rounded z-depth-1" zoomable=true%}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/proj11/gif_pg_cylinder2.gif" title="example image" class="img-fluid rounded z-depth-1" zoomable=true%}
    </div>
</div>
<div class="caption">
    A smooth pseugo-geodesic on a rotational cylinder.
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
    A family of pseudo-geodesics on a mesh. Left: A family of pseudo-geodesic of tilt angle $60^o$ as level-sets are constructed from a triangle mesh. Right: A family of pseudo-geodesics of angle $45^o$ are optimized from geodesics of the quad mesh.
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
    Shading facade with time changing from morning to after. Left: outside. Right: inside view with focal lenth=10.
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
    Four shading facades. Left: shading effect with changing light directions at different time. Center-Right: turn-table views.
</div>




```mermaid
graph LR
    C[2 families] --> I[Ex.: quad mesh isolines]
    C --> J[App.: gridshell]
    C --> K[App.: torsion-free structure]
```

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



```mermaid
graph LR
    D[3 families] --> L[AAG-webs]
    D --> M[AGG-webs]
    D --> N[PPG-webs]
```

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/proj11/AAG.png" title="example image" class="img-fluid rounded z-depth-1" zoomable=true%}
    </div>
</div>
<div class="caption">
    AAG-web.
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/proj11/AGG.png" title="example image" class="img-fluid rounded z-depth-1" zoomable=true%}
    </div>
</div>
<div class="caption">
    AGG-web.
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/proj11/gif_teaser_0.1s.gif" title="example image" class="img-fluid rounded z-depth-1" zoomable=true%}
    </div>
</div>
<div class="caption">
    PPG-web.
</div>



------

#### <i class='fas fa-photo-video'>Video</i>

TBD...

#### <i class='fa-solid fa-code'>Code</i>
Level-sets code see [here](https://github.com/wangbolun300/RectifyingStripPatterns).

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/proj11/levelset.gif" title="example image" class="img-fluid rounded z-depth-1" zoomable=true%}
    </div>
</div>


Quad mesh optimization code see (TBD....)




