---
layout: page
title: teaching
menutitle: teaching
permalink: /teaching/
---

<ul class="class-list">
{% for class in site.teaching %}
<h1 class="class-title">
  <span>{{ class.courseno }}: {{ class.title }}</span>

  {{ class.description }}

  <em>{{ class.lasttaught }}</em>

</h1>
{% endfor %}
