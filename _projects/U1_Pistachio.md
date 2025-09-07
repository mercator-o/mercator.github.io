---
layout: page
title: Pistachio Crusher
#description: a project with a background image and giscus comments
img: assets/img/Pistachio1.jpg
importance: 2
category: Undergraduate
giscus_comments: true
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/Pistachio2.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/Pistachio3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/Pistachio4.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

In MENG 325: Machine Elements and Manufacturing, we were challenged with designing and building a scaled-down rock crusher capable of splitting pistachios. Over the course of the semester, I performed various necessary analyses, one of which is shown to the right, of the proposed crusher. These calculations guided my choice of gear ratios, component thicknesses, axle and bearing sizes, and the overall design.

After an initial rough drawing was sketched out on paper, I used Solidworks to model my proposed design. I minimized the amount of required fasteners by creating puzzle-like pieces and 3D printing the base of the mechanism out of PLA with friction fit tolerances.

Overall, my design was a success as demonstrated in the videos below showing both my mechanism operating with no load, as well as, it operating under a load (ie. crushing a pistachio).

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include video.liquid path="https://youtu.be/QtYTKx_EsCI" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include video.liquid path="https://youtu.be/jkvmAWxj2-4" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<!--
To give your project a background in the portfolio page, just add the img tag to the front matter like so:

    ---
    layout: page
    title: project
    description: a project with a background image
    img: /assets/img/12.jpg
    ---
-->

<!--
The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above:

{% raw %}

```html
<div class="row justify-content-sm-center">
  <div class="col-sm-8 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm-4 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
```

{% endraw %}
-->
