---
layout: archive
title: "可视化作品"
date: 2018-01-02T11:40:45-04:00
---

<img src="/images/数据分析.jpg" alt="数据分析.jpg"/></a>
<div class="tiles">
{% for post in site.categories.chart %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
</div><!-- /.tiles 把所有categories 有 chart 的列出來-->