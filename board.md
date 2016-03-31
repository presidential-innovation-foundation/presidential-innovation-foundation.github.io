---
layout: page
title: Board of Directors
permalink: /board/
id: board
---

<ul class="members small-block-grid-1 medium-block-grid-2 large-block-grid-3">
{% for member in site.data.board %}
<li class="member">
  <img src="/assets/img/photos/{{ member.photo }}.png" alt="{{ member.name }}">
  <div class="about">
    {{ member.name }}<br />
    <small>{{ member.title }}</small>
  </div>
</li>
{% endfor %}
</ul>

Looking to get in touch? We'd love to hear from you. Email us at <hello@presidentialinnovation.org>.
