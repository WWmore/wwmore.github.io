---
layout: page
title:  Pleated Shell
description: Rhino(Grasshopper)
img: assets/img/fun/Marc_pleate1.png
importance: 2
category: fun
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/fun/Marc_pleate2.png" title="example image" class="img-fluid rounded z-depth-1" zoomable=true%}
    </div>
</div>
<div class="caption">
    I like designer Marc Fornes' colorful and cheerful sculptures, one of his famouse design is a <a href="https://www.dezeen.com/tag/marc-fornes/" target="\_blank"> pleated shell </a> for a French school (left). I similarly did this simple pleated shell (center).
    There are several steps to do: 1. get some random points inside a rectangular region. 2. get a Voronoi diagram from the points. 3. do the offset of the polygon and union the region. 4. loft offsets to get a simple mesh and then refine it. 5. float the mesh with some fixed boundary points by Kangaroo optimization. 6. get individual connected strips by the plugin Stripper (right).
    This simple test integrates the modeling and fabrication process: the first 5 steps are for the modeling, and the last step is for fabrication.
</div>

------

##### <i class='fas fa-download'>**Downloads**</i>

See the tutorial in YouTube: [Mesh Topology](https://www.youtube.com/watch?v=ZNPKYTstQX0&list=RDCMUCwImuwbI4lKk544-FS7A2Yw&start_radio=1&rv=ZNPKYTstQX0&t=367).