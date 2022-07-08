---
layout: page
title: Surfaces with a constant ratio of principal curvatures (CRPC surfaces)
description: Discrete differential geometry, Architectural geometry, Weingarten surface, Characteristic parameterization, Constant ratio of principal curvatures, Principal symmetric net
img: assets/img/paper_2021CRPC.jpg
importance: 1
category: work
---

------
##### <i class='fas fa-folder-open'>**Publication**</i><br/>
Computer Aided Geometric Design

##### <i class='fas fa-laugh-beam'>**Authors**</i><br/>
Hui Wang, Helmut Pottmann

##### <i class='fas fa-file-pdf'>**PDF**</i>
[paper](assets/pdf/2022_crpc.pdf)

<iframe src="/assets/pdf/2022_crpc.pdf#toolbar=0" 
width="100%" height=400 frameborder="0" style="border: none;">
</iframe>

##### <i class='fas fa-align-justify'>**Abstract**</i>
Motivated by applications in architectural geometry, we study and compute surfaces with a constant ratio of principal curvatures (CRPC surfaces) based on their characteristic parameterizations. For negative Gaussian curvature K, these parameterizations are asymptotic. For positive K they are conjugate and symmetric with respect to the principal curvature directions. CRPC surfaces are described by characteristic parameterizations whose parameter lines form a constant angle. We use them to derive characteristic parameterizations of rotational CRPC surfaces in a simple geometric way. Pairs of such surfaces with principal curvature ratio k1/k2=±a can be seen as equilibrium shapes and reciprocal force diagrams of each other. We then introduce discrete CRPC surfaces, expressed via discrete isogonal characteristic nets, and show how to efficiently compute them through numerical optimization. In particular, we derive discrete helical and spiral CRPC surfaces. We provide various ways how these and other special types of CRPC surfaces can serve as a basis for computational design of more general CRPC surfaces. Our computational tools may also serve as an experimental basis for mathematical studies of the largely unexplored class of CRPC surfaces.

------

##### <i class='far fa-images'>**Figures**</i>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/proj1/pos_render95.png" title="example image" class="img-fluid rounded z-depth-1" zoomable=true%}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/proj1/pos_render92.png" title="example image" class="img-fluid rounded z-depth-1" zoomable=true%}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/proj1/pos_render93.png" title="example image" class="img-fluid rounded z-depth-1" zoomable=true%}
    </div>
</div>
Fig.1: Architectural design study exhibiting a structure from planar panels based on a discrete CRPC surface with a = 0.45. The constant node angle (≠π/2) and the principal symmetric arrangement lead to a more interesting visual appearance than a mesh aligned with principal curvature directions would have.


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/proj1/pos_render6.png" title="example image" class="img-fluid rounded z-depth-1" zoomable=true%}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/proj1/pos_render3.png" title="example image" class="img-fluid rounded z-depth-1" zoomable=true%}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/proj1/pos_render7_cut.png" title="example image" class="img-fluid rounded z-depth-1" zoomable=true%}
    </div>
</div>
Fig.2: Gridshells based on CRPC surfaces of positive curvature.


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/proj1/neg_render30.png" title="example image" class="img-fluid rounded z-depth-1" zoomable=true%}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/proj1/neg_render1.png" title="example image" class="img-fluid rounded z-depth-1" zoomable=true%}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/proj1/costa4.png" title="example image" class="img-fluid rounded z-depth-1" zoomable=true%}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/proj1/neg_render2.png" title="example image" class="img-fluid rounded z-depth-1" zoomable=true%}
    </div>    
</div>
Fig.3: Asymptotic gridshells, whose underlying surfaces are negatively curved CRPC surfaces.


------

#### <i class='fas fa-photo-video'>GIF</i>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/proj1/costa_crpc.gif" title="example image" class="img-fluid rounded z-depth-1" zoomable=true%}
    </div>
</div>
Optimization for the CRPC surface starting from a periodically connected Costa surface with several cuts.