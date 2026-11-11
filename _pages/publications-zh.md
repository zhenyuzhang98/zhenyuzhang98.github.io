---
layout: archive
permalink: /zh/publications/
title: "代表论文"
lang: zh-CN
author_profile: true
author_bio: '目前为宁波大学博士后研究人员'
---

{% if site.author.inspire %}
  <div class="wordwrap">完整论文列表请参阅<a href="{{ site.author.inspire }}">我的 INSPIRE 主页</a>。</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
