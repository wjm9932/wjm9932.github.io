---
layout: page
title: About
permalink: /about/
weight: 1
---

# **About Me**

I am **{{ site.author.name }}** :wave:,<br>
<div class="row">
{% include about/skills.html title="Programming Languages" source=site.data.programming-skills %}
</div>
<div class="row">
{% include about/skills.html title="Tools" source=site.data.tools %}
</div>
<div class="row">
{% include about/skills.html title="Other Skill" source=site.data.other-skills %}
</div>

<br>

### EDUCATION

<div class="row">
{% include about/timeline.html %}
</div>