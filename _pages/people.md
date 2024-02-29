---
layout: archive
title: "Members"
permalink: /people/
author_profile: true
---

PHD Students
======

  
<hr style="height:1px;border:none;border-top:1px solid #555555;" /> 
<table style="width: 100%; border: 0; border-collapse: collapse;">
  <tr>
    <th style="border: 0;"><img src='../images/500x300.png'></th>
    <th style="border: 0;text-align: left;">
    __wenhao gan__ <br>
    <b>M.S.</b> <br>
    <b>B.S</b> <br>
    **Research Interests:** <br>
    **Email:** <br>
    </th>
    <th style="border: 0;"><img src='../images/500x300.png'></th>
    <th style="border: 0;">内容</th>
  </tr>
</table>

{% include base_path %}

{% for post in site.people reversed %}
  {% include archive-single.html %}
{% endfor %}
