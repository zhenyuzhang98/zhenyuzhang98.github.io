---
layout: archive
title: "Blogs"
permalink: /blogs/
author_profile: true
---

{% if site.author.inspire %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.inspire}}">my INSPIRE profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
