---
layout: archive
title: "People"
permalink: /people/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

Education
======
* TODO

Work experience
======
* TODO

<img src='../images/500x300.png'>

<table style="width: 500px; border: 0; border-collapse: collapse;">
  <tr>
    <th style="border: 0;">表头1</th>
    <th style="border: 0;">表头2</th>
  </tr>
  <tr>
    <td style="border: 0;">数据1</td>
    <td style="border: 0;">数据2</td>
  </tr>
</table>

{% include base_path %}

{% for post in site.people reversed %}
  {% include archive-single.html %}
{% endfor %}
