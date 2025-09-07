---
layout: page
title: 1949 Willy's Jeep
#description: a project with a background image and giscus comments
img: assets/img/Jeep6.jpg
importance: 2
category: Extracurricular
giscus_comments: true
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/Jeep1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/Jeep2.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/Jeep3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/Jeep4.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

As an automotive enthusiast, I have alway been interested in how engines worked and how to make the vehicles they power go faster. Starting with minibike that I built and modified until it was able to reach speeds that breached the boundary of safety, my interest manifested in restoring a 1949 Willy's Jeep. Purchased in 2015 - special thanks to my parents - I had the daunting task of rebuilding the seized engine and brakes, wobbly steering system, and incomplete electrical system.

Using a reprint of the original owner's manual and countless YouTube videos, I was able to rebuilt the the broken systems and eventually got it to move under its own power.

Since cost was one of the main limiters of this project, I taught myself how to weld in order to fix various torn brackets and to avoid paying a third party to do so.

Throughout the rebuilding process, I was continually impressed by how much a simple machine in comparison to today's standards was truly a feat of engineering.

<!--
To give your project a background in the portfolio page, just add the img tag to the front matter like so:

    ---
    layout: page
    title: project
    description: a project with a background image
    img: /assets/img/12.jpg
    ---
-->

<div class="row">
    <div class="col-sm mt-2 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/Jeep5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-2 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/Jeep7.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include video.liquid path="https://www.youtube.com/shorts/ly0pIo0tSrM?feature=share" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

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
