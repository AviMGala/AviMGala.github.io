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
        <iframe width="360" height="202" src="https://www.youtube.com/embed/_41KNuIh3wY" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </div>
    <div class="col-sm mt-3 mt-md-0">
        <iframe width="360" height="202" src="https://www.youtube.com/embed/htSv0uxy3sE" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </div>
    <div class="col-sm mt-3 mt-md-0">
        <iframe width="360" height="202" src="https://www.youtube.com/embed/PPrS0S1SDRw" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </div>
</div>
<div class="caption">
    The leftmost video features projectile collision detection, networked kill streaks, and messages that indicate the start and end of the game. In the middle is networked chat functionality. Lastly, the rightmost clip shows tagging and switching tags (like in Valorant or Overwatch).
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <iframe width="650" height="365" src="https://www.youtube.com/embed/KNC-wJUlZbU" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </div>
</div>
<div class="caption">
    Here's a snippet from the final project, implementing a networked projectile that explodes and communicates the explotion animation/sound effects to the listen server.
</div>

Below are snippets of code that make this project work behind the scenes. C++ is the backbone of this demo, it enabled the save/load capability of the game, the storing of chat messages, collision, and pretty much everything else that you just saw.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/projectileCode.png" title="Projectile Code" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/SequenceBlueprint.PNG" title="Sequence Puzzle Blueprint" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    On the left is a snippet from the projectile code, on the right is an image of the blueprint used to build an in-game puzzle that is triggered by pressure plates.
</div>


If you'd like to see more, shoot me an email at avinashmgala@gmail.com and I'll be happy to show you Game AI, responsive animation, and other game logic, including what you see above!
