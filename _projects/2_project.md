---
layout: page
title: Be Eldash
description: Graduate Student in Biology
img: assets/img/be_picture.jpg
importance: 2
category: current #work
---

I spend most of my days trying to understand the strategies that animals use to meet their needs and how environment
and biological characteristics shape their responses. I am particularly interested in questions about body size, energetics, and locomotion - which drew me to the Schilder Lab. Beyond my academic pursuits, you'll often find me walking a dog at the animal shelter, jogging, and drinking craft beers, sometimes all at once.

<!-- To give your project a background in the portfolio page, just add the img tag to the front matter like so:

    ---
    layout: page
    title: project
    description: a project with a background image
    img: /assets/img/12.jpg
    ---  -->

{% comment %}
<div class="row">
<div class="col-sm mt-3 mt-md-0">
{% include figure.html path="assets/img/1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
</div> 
<div class="col-sm mt-3 mt-md-0">
{% include figure.html path="assets/img/3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
</div> 
<div class="col-sm mt-3 mt-md-0">
{% include figure.html path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
</div>
</div>

<div class="caption">
    Caption photos easily. On the left, a road goes through a tunnel. Middle, leaves artistically fall in a hipster photoshoot. Right, in another hipster photoshoot, a lumberjack grasps a handful of pine needles.
</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This image can also have a caption. It's like magic.
</div>

You can also put regular text between your rows of images.
Say you wanted to write a little bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, *bled* for your project, and then... you reveal its glory in the next row of images.


<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    You can also have artistically styled 2/3 + 1/3 images, like these.
</div>


The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above:

{% raw %}
```html
<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
```
{% endraw %}
{% endcomment %}