---
layout: page
title: Electic Scooter
#description: a project with a background image and giscus comments
img: assets/img/Scooter1.jpg
importance: 3
category: Extracurricular
giscus_comments: true
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/Scooter2.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/Scooter3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/Scooter4.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

In my spare time between working on my family's oyster farm and taking online summer classes, I designed and built an electric scooter from various scrap parts found in our garage. I have always had an interest in making vehicles go faster and becoming more rugged - when I was younger, I would disassemble RC cars and boats in an attempt to achieve these goals. 

In fact, one of my favorite projects that I had as a kid was building and modifying a minibike. Using my mom's water bottle as a fuel tank -an action that was not well received-  and removing the governor from the engine, I would change gear ratios and wheel type and size to achieve the best combination of acceleration and top speed. Unfortunately, minibikes are not road legal.

<!--
To give your project a background in the portfolio page, just add the img tag to the front matter like so:

    ---
    layout: page
    title: project
    description: a project with a background image
    img: /assets/img/12.jpg
    ---
-->

Limited by my budget and available tools, I chose to convert a push scooter into an electric scooter. I used an angle grinder to modify the rear section of the scooter and then sandwiched aluminum and steel plates to create a new platform on which to mount the modified wheel (the scooter deck is made out of magnesium and thus, I was not able to weld to it with the equipment at hand). I then crafted mounts for the wheel, disk brake, and battery. Using parts typically found on electric skateboards, I created a drive system that maximized acceleration and hill climbing abilities in order to scoot up Science Hill in New Haven.

Component List & Specifications:
- 6374 brushless DC motor
- 80:15 gear ratio (belt driven)
- 6s2p lithium ion battery pack
- 5" steel disk brake
- Top Speed: ~15mph
- Able to climb Science Hill? Yes
- Run time: ~45mins at full speed

I improved upon this design for the [final project] of my Computer Aided Design class. Using SolidWorks, I modeled a sleeker deck, more efficient folding mechanism, and a more compact drive system.

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
