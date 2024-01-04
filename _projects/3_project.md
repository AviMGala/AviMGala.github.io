---
layout: page
title: Blizzard Entertainment (SWE Intern Summer 22' and 23')
description: I worked on the Server & Netcode team under the Blizzard Core Tech organization, Team 0
img: assets/img/blizzard.jpeg
importance: 3
category: Games
---

I started at Blizzard as an intern on Server & Netcode Team 0, working on the Unannounced Survival Game. I interned again with the same team the following summer, this time working on a DDOS Mitigation project, writing code to help automate performance and load testing.

My work at Blizzard is under an NDA, so I cannot disclose sensitive details about either project. Here are some general concepts regarding what I helped build:

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/netcode_settings.png" title="Netcode Settings" class="img-fluid rounded z-depth-1" %}
    </div>
     <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/netgraph_display.png" title="Netgraph Display" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    In the Unannounced Survival Game, I helped reduce rubber banding and in game latency, and built netcode settings functionality, a display for netcode related info, and HUD notifications when latency events occur.
</div>

 My team is also working on an awesome DDOS mitigation tool that I contributed to in the Summer of 2023. It is currently being rolled out to Overwatch 2 with plans to roll it out to the remaining games in the Blizzard suite. Here are some of its features:

<!-- Bullet-pointed list -->
<ul>
  <li>Process packets in the networking stack with extremely low overhead</li>
  <li>Avoids expensive network layer packet analysis</li>
  <li>Allows ID of individual clients, and implements rollover features so that server failures do not prompt interruption of the game</li>
</ul>
