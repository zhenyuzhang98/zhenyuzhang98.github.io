---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.inspire %}
  <div class="wordwrap">You can find a full list of my papers on <a href="{{site.author.inspire}}">my INSPIRE profile</a>.</div>
{% endif %}

Selected papers
===============

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
