---
layout: page
title: Designing Asymptotic Geodesic Hybrid Gridshells
description: mesh optimization, asymptotic curves, geodesic curves, construction-aware design, elastic gridshells
img: assets/img/paper_2022AGG.png
importance: 1
category: work
---

------
##### <i class='fas fa-folder-open'>**Publication**</i><br/>
CAD

##### <i class='fas fa-laugh-beam'>**Authors**</i><br/>
Eike Schling∗, Hui Wang∗, Sebastian Hoyer, Helmut Pottmann 
(∗Joint first authors)

##### <i class='fas fa-align-justify'>**Abstract**</i>
Fabrication and assembly of freeform shells can be simplified significantly when controlling the curvature of structural elements during the design phase. This approach has produced fundamental insights to bending-active construction, using the elastic property of elements to form efficient load-bearing structures. This paper is focused on gridshells that are built from straight and flat slats. The slats are combined in two orientations, tangential and normal to the design surface, to create robust and versatile triangulated grids. For this purpose, we generate hybrid webs of asymptotic and geodesic paths on freeform surfaces. The research combines geometric computing with architectural building practice. We present a computational workflow for the design and interactive modification of hybrid asymptotic geodesic webs. At its core are discrete models that are based on concepts of differential geometry and allow to compute constrained structures within an optimization framework. The resulting webs are tested for architectural applications. We derive a strategy for the elastic erection process, in which geodesic lamellas are used as a guide and bracing of the spatial structure. Two architectural scenarios, a timber roof and a steel facade are presented. Their feasibility for construction is verified through prototypical joints and physical models. The research introduces a new class of networks and related surfaces and offers insights into the practical challenges of freeform construction from elastic slats.

------

##### <i class='fas fa-file-pdf'>**Paper/Slide**</i>

paper to be updated...

<!-- [paper](https://www.geometrie.tuwien.ac.at/geom/ig/publications/geodesic/geodesic.pdf) -->

<!-- <iframe src="https://www.geometrie.tuwien.ac.at/geom/ig/publications/geodesic/geodesic.pdf#toolbar=0" 
width="100%" height=400 frameborder="0" style="border: none;">
</iframe> -->

<iframe src="/assets/pdf/slides/2022-AG-Hui.pdf#toolbar=0" 
width="100%" height=350 frameborder="0" style="border: none;">
</iframe>

------

##### <i class='far fa-images'>**Figures**</i>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/proj6/webs.png" title="example image" class="img-fluid rounded z-depth-1" zoomable=true%}
    </div>
</div>
Fig.1: Numerical models of geodesic nets (1-2 row), Voss nets (3-4 row), asymptotic nets (5-6 row), AAG-webs (7-8 row), AGG-webs (9-10 row), AGAG-webs (11-12 row), their gridshells (second column) and corresponding developable strips' unrollments (right columns).


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/proj6/singular.png" title="example image" class="img-fluid rounded z-depth-1" zoomable=true%}
    </div>
</div>
Fig.2: Discussions in Fig.1 are confined to nets and webs of regular combinatorics, which limits the shape variety. For such meshes with a singularity of valence 6 or valence 8, we divide the web into 6 or 8 regular quad patches. Each patch is an AAG-web. Right column are two designs. 


###### **Applications**

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/proj6/app1.png" title="example image" class="img-fluid rounded z-depth-1" zoomable=true%}
    </div>
</div>
Fig.3: We designed and built a timber roof structure from straight lamellas.
The Top and bottom mesh boundaries of the computed rotational AAG gridshell have square and circular shapes, respectively. The real model is one-quarter of it.


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/proj6/app2.png" title="example image" class="img-fluid rounded z-depth-1" zoomable=true%}
    </div>
</div>
Fig.4: We redesigned the Emporia shopping center façade and successfully built a small-scaled steel AAG gridshell from straight rectangular steel slats. The original façade has obvious unsmooth supporting structures.
Our optimized AAG-web approximates the shape with 4 original planar boundaries,  the shell improves the structure’s appearance.


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/proj6/app3.png" title="example image" class="img-fluid rounded z-depth-1" zoomable=true%}
    </div>
</div>
Fig.5: We roughly approximated the negatively curved part of the Soumaya Museum Model by an AAG web. This web results from the carefully-controlled optimization.
Given any negatively curved mesh, we cannot directly approximate it to be an AGG or AAG-web. Only special shapes are possible.
How to approximate a given curved shape is still an open question. 
A promising way to investigate the generation of webs is by using a level set approach.
It will be our future work.



<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/proj6/xuerongxing0.png" title="example image" class="img-fluid rounded z-depth-1" zoomable=true%}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/proj6/xuerongxing1.png" title="example image" class="img-fluid rounded z-depth-1" zoomable=true%}
    </div>
</div>
Fig.6: During the Winter Olympic Games Beijing 2022, many steel landscape sculptures called [Xuerong Stars](http://city.cri.cn/20220221/5011d6ff-c7ac-ca90-7db1-e44a3e98ca2b.html)(namely Edelweiss Stars) appeared in front of the National Stadium and Ice Cube. They were designed by Prof. Weixin Huang's team from Tsinghua University. These steel models are designed based on the regular icosahedron, where 6 pairs of triangular faces are used to form the congruent curved patches and the other 8 left triangular faces are deleted. 
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/proj6/xuerongxing2.png" title="example image" class="img-fluid rounded z-depth-1" zoomable=true%}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/proj6/xuerongxing3.png" title="example image" class="img-fluid rounded z-depth-1" zoomable=true%}
    </div>
</div>
Fig.7: Still based on a regular icosahedron, I redesigned another AAG-gridshell with 20 patches congruent to each other. The red strips are tangent along the geodesic curves of each simple negatively-curved patch, and the other two families of diagonal strips are orthogonal along the asymptotic curves of the patch.

------

#### <i class='fas fa-photo-video'>GIF</i>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/proj6/AGG.gif" title="example image" class="img-fluid rounded z-depth-1" zoomable=true%}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/proj6/AAG.gif" title="example image" class="img-fluid rounded z-depth-1" zoomable=true%}
    </div>
</div>
<div class="caption">
    Interactive design of AGG-web (left) and AAG-web(right). In this way, a sequence of freeform webs are produced.
</div>

------

#### <i class='fab fa-youtube'>**Video**</i> 

Presentation video in [YouTube](https://www.youtube.com/watch?v=jyjE0wSNoHw) and in [Bilibili](https://www.bilibili.com/video/BV1Rf4y1Z7yK?spm_id_from=333.999.0.0&vd_source=3fcaaf2fe9f45c94842d7fa553d555be).


<!-- <p align="center">
<iframe width="560" height="315" src="https://www.youtube.com/watch?v=jyjE0wSNoHw" title="Designing Asymptotic Geodesic Hybrid Gridshells" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</p> -->

<!-- <p align="center">
<iframe width="420" height="315" src="https://www.youtube.com/watch?v=jyjE0wSNoHw" frameborder="0" allowfullscreen></iframe>
</p> -->

------

##### <i class='fas fa-download'>Open Source</i>

to be updated ...

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/proj6/hops.png" title="example image" class="img-fluid rounded z-depth-1" zoomable=true%}
    </div>
</div>
A user-friendly design tool has been realized by integrating the optimization into the CAD system Rhinoceros3D. Our plugin allows the user to define the main inputs to the optimization, the initial mesh, the web type, strip width and optimization parameters like the number of iterations and weights. The results, namely the optimized mesh,
strip boundaries in piecewise quintic Bezier form, ruling vectors, the developable strips as well as their developments are returned as Rhinoceros3D geometry objects. The optimization is implemented in CPython and called from Grasshopper, Rhinoceros’ parametric design extension, using the [Hops component](https://developer.rhino3d.com/guides/compute/hops-component/). This allows the user to offload the actual computation to a more powerful remote machine, if desired. We will make our plugin available to the architectural community in the near future.