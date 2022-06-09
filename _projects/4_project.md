---
layout: page
title: Principal Symmetric Meshes (S-nets)
description: Discrete differential geometry, Architectural geometry, Computational fabrication, Paneling, Sphere geometries, Curvature adaptive milling
img: assets/img/paper_2020SIG.png
importance: 4
category: work
---

------
##### **Publication**
ACM Transactions on Graphics

##### **Authors**
Davide Pellis∗, Hui Wang∗, Florian Rist, Kilian Martin, Helmut Pottmann, Christian Müller
(∗Joint first authors)

##### **Downloads**
[paper](https://www.geometrie.tuwien.ac.at/geom/ig/publications/snets/snets.pdf)

<!-- <object data="https://www.geometrie.tuwien.ac.at/geom/ig/publications/snets/snets.pdf#toolbar=0" type="application/pdf" width="100%" height="100%">
</object> -->

<iframe src="https://www.geometrie.tuwien.ac.at/geom/ig/publications/snets/snets.pdf#toolbar=0" 
width="100%" height=400 frameborder="0" style="border: none;">
</iframe>

##### **Abstract**
The isolines of principal symmetric surface parametrizations run symmetrically to the principal directions. We describe two discrete versions of these
special nets/quad meshes which are dual to each other and show their usefulness for various applications in the context of fabrication and architectural
design. Our discretization of a principal symmetric mesh comes naturally
with a family of spheres, the so-called Meusnier and Mannheim spheres. In
our representation of principal symmetric meshes, we have direct control
over the radii of theses spheres and the intersection angles of the parameter
lines. This facilitates tasks such as generating Weingarten surfaces including constant mean curvature surfaces and minimal surfaces. We illustrate
the potential of Weingarten surfaces for paneling doubly curved freeform facades by significantly reducing the number of necessary molds. Moreover,
we have direct access to curvature adaptive tool paths for cylindrical CNC
milling with circular edges as well as flank milling with rotational cones.
Furthermore, the construction of curved support structures from congruent
circular strips is easily managed by constant sphere radii. The underlying
families of spheres are in a natural way discrete curvature spheres in analogy
to smooth Möbius and Laguerre geometry which further leads to a novel
discrete curvature theory for principal symmetric meshes.


------

##### **Figures**
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/paper_2020SIG.png" title="example image" class="img-fluid rounded z-depth-1" zoomable=true%}
    </div>
</div>
Fig.: Architectural design of a modern mountain leisure and tourism center. The geometric shape of the hull is a discrete principal symmetric parametrization
(an S-net) of a Weingarten surface of type aκ1 + bκ2 = c. The big advantage lies in the fabrication of its doubly curved panels by a substantial
reduction of necessary molds, as the same mold can be used along curves of constant curvature illustrated by isolines (b). Panels with identical molds are
clustered together and highlighted by the same color (a). The network of this S-net assumes constant intersection angles which contributes to its aesthetic.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/proj4/snet_fig16.png" title="example image" class="img-fluid rounded z-depth-1" zoomable=true%}
    </div>
</div>
Fig.1: Re-render of the Fig.16 in the paper.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/proj4/snet_fig19.png" title="example image" class="img-fluid rounded z-depth-1" zoomable=true%}
    </div>
</div>
Fig.2: Re-render of the Fig.19 in the paper.

------

#### **Video**

Presentation video is [here](https://dl.acm.org/doi/10.1145/3386569.3392446).
