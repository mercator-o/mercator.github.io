---
published: true
layout: post
title: Pistachio Crusher
date: 2021-11-01
#description: this is what included images could look like
tags: Undergraduate
#categories: sample-posts
thumbnail: assets/img/Pistachio1.jpg
featured: false
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/Pistachio2.jpg" title="" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/Pistachio3.jpg" title="" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/Pistachio4.jpg" title="" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

In MENG 325: Machine Elements and Manufacturing, we were challenged with designing and building a scaled-down rock crusher capable of splitting pistachios. Over the course of the semester, I performed various necessary analyses, one of which is shown to the right, of the proposed crusher. These calculations guided my choice of gear ratios, component thicknesses, axle and bearing sizes, and the overall design.

After an initial rough drawing was sketched out on paper, I used Solidworks to model my proposed design. I minimized the amount of required fasteners by creating puzzle-like pieces and 3D printing the base of the mechanism out of PLA with friction fit tolerances.

Overall, my design was a success as demonstrated in the videos below showing both my mechanism operating with no load, as well as, it operating under a load (ie. crushing a pistachio).

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include video.liquid path="assets/video/Pistachio Crusher No Load.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include video.liquid path="assets/video/Pistachio Crusher Load.mp4" class="img-fluid rounded z-depth-1" controls=true %}
    </div>
</div>
<div class="caption">
    Pistachio Crusher No Load vs. Load
</div>
