---
layout: archive
title: "信息可视化笔记"
date: 2018-01-04
modified:
excerpt: "内含信息可视化考试回顾 实用链接 重点内容"
tags: []
image: 
  feature: data_vis.gif
  teaser:  data_vis.gif
---


<div class="tiles">
{% for post in site.categories.datam %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles 把所有categories 有 datam 的列出來-->