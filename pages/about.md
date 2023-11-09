---
layout: page
title: About
permalink: /about/
weight: 3
---

# **About Me**

Hi I am **{{ site.author.name }}** :wave:,<br>
I am a highly motivated Data Engineer with over 3 years of professional experience working in the field of Big Data, Cloud, Artificial Intelligence and Research. I am also interested in Video Game Development.

<div class="row">
{% include about/skills.html title="Programming Skills" source=site.data.programming-skills %}
{% include about/skills.html title="Databases" source=site.data.databases %}
{% include about/skills.html title="Cloud Platforms" source=site.data.cloud-platforms %}
</div>

<div class="row">
{% include about/timeline.html % title="Professional Experience" source=site.data.professional-experience %}
</div>

<div class="row">
{% include about/timeline.html % title="Education" source=site.data.education %}
</div>