---
layout: default
title: Home | User Empowerment Lab
---
<section class="section">
  {% include about.html %}
</section>

<section class="section-alt" style="padding: 40px 0px 20px 0px;">
{% include research-area-grid.html header="Research Areas" values=site.research-areas landing=true %}
</section>

<section class="section-alt">
{% include paper-grid.html header="Recent Papers" values=site.publications limit=3 landing=true %}
</section>

<section class="section-alt">
{% include news-grid.html header="Recent News" values=site.news limit=4 landing=true %}
</section>

