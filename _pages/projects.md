---
title: "MoRPH - Projects"
layout: gridlay
excerpt: "MoRPH: Projects"
sitemap: false
permalink: /projects/
---

### Our Projects

Here are some ongoing and past projects.

<br>

{% for proj in site.data.projs %}

<div class="row">

<div class="clearfix well proj-item-container">
  <img src="{{ site.url }}{{ site.baseurl }}/images/pubpic/{{ proj.image }}" class="img-responsive" width="20%" style="float: right; margin-left: 2em;" />
    <pubtit>{{ proj.title }}</pubtit>
  <p>{{ proj.description }}</p>
</div>

</div>

{% endfor %}
