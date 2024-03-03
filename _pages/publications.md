---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

<hr style="height:1px;border:none;border-top:1px solid #555555;" /> 
<table style="width: 100%; border: 0; border-collapse: collapse;">
  <tr>
    <th style="border: 0;">1.</th>
    <th style="border: 0;text-align: left;vertical-align: top;">
    Xu Zhi, Hongbo Zhu, Hua Chen, Wei Zhang <br>
    Polytopic Planar Region Characterization of Rough Terrains for Legged Locomotion  <br>
    In: IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS), 2022. <br>
    <a href="[mailto:example@example.com](https://www.baidu.com/)">Links</a>
    </th>
  </tr>
</table>

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
