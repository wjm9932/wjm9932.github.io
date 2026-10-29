---
layout: page
title: About
permalink: /about/
weight: 1
---

# **About Me**

I am **{{ site.author.name }}** :wave:

<h3 class="project-section-title">Skills</h3>

<article class="portfolio-card card bg-themed text-themed about-skills-card">
  <div class="card-body">
  {% include about/skills.html title="Programming Languages" source=site.data.programming-skills %}
  {% include about/skills.html title="Tools" source=site.data.tools %}
  {% include about/skills.html title="Other Skills" source=site.data.other-skills %}
  </div>
</article>

<h3 class="project-section-title">Education</h3>

<div class="row">
  {% include about/timeline.html %}
</div>
