---
layout: archive
title: "Members"
permalink: /people/
author_profile: true
---

PHD Students
======
<hr style="height:1px;border:none;border-top:1px solid #555555;" />  实线，一条直线
<table style="width: 70%; border: 0; border-collapse: collapse;">
  <tr>
    <th style="border: 0;"><img src='../images/500x300.png'></th>
    <th style="border: 0;">
    **wenhao gan** <br>
    **M.S.** <br>
    **B.S.** <br>
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
