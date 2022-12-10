---
layout: page
title: Architectural Structures from Quad Meshes with Planar Parameter Lines
description: architectural geometry, computational design, planar parameter lines, static equilibrium
img: assets/img/paper_2022PPQ.png
importance: 7
category: work
---

------
##### <i class='fas fa-folder-open'>**Publication**</i><br/>
Computer-Aided Design (CAD)

##### <i class='fas fa-laugh-beam'>**Authors**</i><br/>
Cheng Wang, Caigui Jiang, Hui Wang, Xavier Tellier, Helmut Pottmann 

##### <i class='fas fa-align-justify'>**Abstract**</i>
We address the computational design of architectural structures which are based on a frame of intersecting beams that are
aligned with the parameter lines of a quad mesh. While previous work mainly put a planarity constraint onto the faces of
the mesh, we focus on the planarity of long-range supporting beams which follow selected polylines in the underlying mesh.
In addition to that, we impose further constraints including planarity of faces, right node angles and static equilibrium, and
discuss in which way these may be combined. Some of the studied meshes are discrete counterparts of certain well-known
surfaces in classical geometry, whose knowledge is helpful for initializing the proposed optimization algorithms.

##### <i class='fas fa-file-pdf'>**Paper**</i>
[paper](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4144321)

<iframe src="/assets/pdf/2022PP-HW.pdf#toolbar=0" 
width="100%" height=400 frameborder="0" style="border: none;">
</iframe>
------

##### <i class='far fa-images'>**Figures**</i>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/proj7/chadstone.png" title="example image" class="img-fluid rounded z-depth-1" zoomable=true%}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/proj7/PPQ1.471.png" title="example image" class="img-fluid rounded z-depth-1" zoomable=true%}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/proj7/PPQ2.472.png" title="example image" class="img-fluid rounded z-depth-1" zoomable=true%}
    </div>
</div>
Fig.1: Inspired by the glass roof of [Chadstone Shopping Centre](https://seele.com/references/chadstone-shopping-centre) in Melbourne, I designed a quad mesh with planar faces and one family of planar polylines (P+PQ type).

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/proj7/every5_PPQ1.480.png" title="example image" class="img-fluid rounded z-depth-1" zoomable=true%}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/proj7/every5_PPQ1.481.png" title="example image" class="img-fluid rounded z-depth-1" zoomable=true%}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/proj7/every5_PPQ1.483.png" title="example image" class="img-fluid rounded z-depth-1" zoomable=true%}
    </div>
</div>
Fig.2: Different from the one in Fig.1, every fifth polyline of a family is planar. 


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/proj7/harbin.png" title="example image" class="img-fluid rounded z-depth-1" zoomable=true%}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/proj7/harbin.440.png" title="example image" class="img-fluid rounded z-depth-1" zoomable=true%}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/proj7/harbin.441.png" title="example image" class="img-fluid rounded z-depth-1" zoomable=true%}
    </div>
</div>
Fig.3: Left: MAD Architects-designed [Harbin Opera House](https://www.archdaily.cn/cn/778981/ha-er-bin-ge-ju-yuan-madjian-zhu-shi-wu-suo) in China. Right-two: Inspired by it, I designed a supporting structure with two families of orthogonal planar polylines (PP+90 type).

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/proj7/meixihu.png" title="example image" class="img-fluid rounded z-depth-1" zoomable=true%}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/proj7/meixihu.450.png" title="example image" class="img-fluid rounded z-depth-1" zoomable=true%}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/proj7/meixihu.444.png" title="example image" class="img-fluid rounded z-depth-1" zoomable=true%}
    </div>
</div>
Fig.4: Left: Zaha Hadid Architects-designed [Changsha Meixihu International Culture and Art Centre](https://www.dezeen.com/2019/05/03/zaha-hadid-architects-changsha-meixihu-jnternational-culture-art-centre/) in China.
Right-two: Based on the left corner one, I designed another supporting structure with two families of orthogonal planar polylines (PP+90 type).

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/proj7/2PPQ_1.png" title="example image" class="img-fluid rounded z-depth-1" zoomable=true%}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/proj7/2PPQ_8.png" title="example image" class="img-fluid rounded z-depth-1" zoomable=true%}
    </div>
</div>
Fig.5: Left: A quad mesh with planar faces and one family of piecewise planar polylines (in colors) approximating the surface on the top of the Lilium Tower model by Zaha Hadid Architects. 
Right: A quad mesh in static equilibrium rationalized with planar faces and one family of piecewise planar polylines (in colors). 

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/proj7/jining.png" title="example image" class="img-fluid rounded z-depth-1" zoomable=true%}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/proj7/9.png" title="example image" class="img-fluid rounded z-depth-1" zoomable=true%}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/proj7/12.png" title="example image" class="img-fluid rounded z-depth-1" zoomable=true%}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/proj7/15.png" title="example image" class="img-fluid rounded z-depth-1" zoomable=true%}
    </div>
</div>
Fig.6: A P+PQ mesh with its support structure generates different shading patterns during a day at 9:00, 12:00 and 15:00. When the light is parallel to those planar polylines, the respective parts in the shading pattern are lighter. The base curve comes from the Ryue Nishizawa-designed [Jining Art Museum](https://www.archdaily.cn/cn/964365/ji-zhu-mei-zhu-guan-xi-ze-li-wei?ad_source=search&ad_medium=projects_tab&ad_source=search&ad_medium=search_result_all) in China.
