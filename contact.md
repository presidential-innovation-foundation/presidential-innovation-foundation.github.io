---
title: Contact us
permalink: /contact/
---

### Contact the board

<ul class="members small-block-grid-1 medium-block-grid-2 large-block-grid-3">
{% for member in site.data.board %}
<li class="member">
  <img src="https://github.com/{{ member.github }}.png" alt="{{ member.name }}">
  <div class="about">
    {{ member.name }}<br />
    <small>{{ member.title }}</small>
  </div>
</li>
{% endfor %}
</ul>

Looking to get in touch? We'd love to hear from you. Email us at <hello@presidentialinnovation.org>. For inquiries about donations or to request financial assistance for a project email <pifftreas@gmail.com>.

### Social media

* Twitter: [@InnovFellows](https://twitter.com/InnovFellows)
* Facebook: [Membership-only Facebook group](https://www.facebook.com/groups/presidentialinnovationfellows)

### Mailing lists

* Alumni mailing list — <alumni@presidentialinnovation.org>

Please note that this is a membership-only mailing list. All PIFs are eligible to join after serving as a PIF for six months. To request access, visit [the Google Groups page](https://groups.google.com/a/presidentialinnovation.org/forum/#!forum/alumni).

#### GSA Mailing lists

* Current PIFs — <pif@gsa.gov>
* PIF Alumni — <pif-alum@gsa.gov>
