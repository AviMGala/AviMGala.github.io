---
layout: page
title: FPS Demo (Gameplay)
description: Built in Unreal Engine with C++ (for ITP 438)
img: assets/img/FinalProj.png
importance: 1
category: Games
related_publications:
---

Here is the final project from ITP 438: Advanced Gameplay Programming. This project is the culmination of around 8 weeks of work,
with c++ code written for networking, movement, combat, UI, and more!

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <iframe width="560" height="315" src="https://www.youtube.com/embed/1H1qfgXoE8k" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </div>
    <div class="col-sm mt-3 mt-md-0">
        <!-- Embed code for another video -->
    </div>
    <div class="col-sm mt-3 mt-md-0">
        <!-- Embed code for another video -->
    </div>
</div>
<div class="caption">
    On the left is a basic system to respawn the player. Middle, networked chat functionality in C++. Right, in-game tags and launching via Steam.
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Here's a snippet from the final project, implementing a networked projectile that explodes and communicates the explotion animation/sound effects to the listen server.
</div>

Below are snippets of code that make this project work behind the scenes. C++ is the backbone of this demo, it enabled the save/load capability of the game, the storing of chat messages, collision, and pretty much everything else that you just saw.

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
