---
layout: archive
title: "People"
permalink: /people/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

# 团队成员

| 老师 | 博士生 |
| --- | --- |
| ![张三](zhangsan.jpg) <br> **张三** <br> 张三教授拥有多年的教学和研究经验，专注于计算机科学领域。他在人工智能和机器学习方面有着丰富的专业知识，并且致力于指导学生进行创新性研究。 | ![李四](lisi.jpg) <br> **李四** <br> 李四是我们团队的博士生，他的研究方向是自然语言处理和深度学习。李四在过去的研究中取得了一系列重要成果，发表了多篇高水平的学术论文，并且获得了多项科研项目的资助。 |

| 硕士生 |
| --- |
| ![王五](wangwu.jpg) <br> **王五** <br> 王五是我们团队的硕士生，他对人工智能和数据科学领域充满热情。王五在本科阶段已经展现出了扎实的编程能力和独立思考的能力，在加入实验室后，他积极参与项目研究，并且取得了可喜的成绩。 |


{% include base_path %}

{% for post in site.people reversed %}
  {% include archive-single.html %}
{% endfor %}
