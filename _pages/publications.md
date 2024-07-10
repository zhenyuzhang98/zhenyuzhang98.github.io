---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.inspire %}
  <div class="wordwrap">You can also find my articles on <a href="{{https://inspirehep.net/authors/1744398?ui-citation-summary=true}}">my INSPIRE profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
