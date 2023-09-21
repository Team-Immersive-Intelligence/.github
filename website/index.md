---
title: Home
layout: home
permalink: /
---

## Who we are
We are a group of Minecraft modders, who mainly work on the mod [Immersive Intelligence](https://github.com/Team-Immersive-Intelligence/ImmersiveIntelligence), an addon to [Immersive Engineering](https://github.com/BluSunrize/ImmersiveEngineering).<br>
We plan to expand our portfolio of mods with new IE addons, to enhance the game even further.<br>
We do it as volunteers - people who just want to enjoy the game modded in their way.

---
<br>

## How it all began

II started with [@Pabilo8](https://github.com/Pabilo8/), in April/May 2019. Since then, the mod has grown and many new features, planned back then were implemented.
Thorough the years our Team has expanded, currently the members are:

<div class="grid-container2">
{% for member_hash in site.data.team_members %}
  {% capture callout_content %}{{ member_hash[1].id }}{% endcapture %}
  {%- include person.html person=callout_content -%}
{% endfor %}
</div>
<br>

---
<br>

## New Members

{% if site.data.hiring %}

II has become a big project. Due to lack of time (uni, work) of our members, the progress is very slow.<br>
We are in need of a:
<div class="grid-container3">

{% for member_hash in site.data.hiring %}
  {% capture callout_content %}{{ member_hash[1].id }}{% endcapture %}
  {%- include hiring.html person=callout_content -%}
{% endfor %}

</div>

{% else %}

For now we're not in a need of anything in particular, but you may send a message to [pabilo@iiteam.net](mailto:pabilo@iiteam.net) to see how you can help.

{% endif %}

---
<br>

## Our Projects
Our most known projects are, naturally, Minecraft Mods, we also develop tools and assets that are helpful for modders and video game developers.
<div class="grid-container3">
{% for projects_hash in site.data.projects %}
  {% capture callout_content %}{{ projects_hash[1].id }}{% endcapture %}
  {%- include project.html project=callout_content -%}
{% endfor %}
</div>

<br>
<hr>
Finally, our main plan and final goal is to create a big *modpack*, based on the Immersive mod series, which will be like no *modpack* you've seen before... ^^
<img src="../assets/projects/modpack_logo.svg" alt="Engineered Adventures: Tales from the Front" style="display: block; margin-left: auto; margin-right: auto; width: 50%;"><br>

