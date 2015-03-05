---
layout: page
title: Board of Directors
permalink: /board/
id: board
---

<ul class="members small-block-grid-1 medium-block-grid-2 large-block-grid-3">
{% for member in site.data.board %}
<li class="member">
  <img src="https://github.com/{{ member.github }}.png">
  <div class="about">
    {{ member.name }}<br />
    <small>{{ member.title }}</small>
  </div>
</li>
{% endfor %}
</ul>
