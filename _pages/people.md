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

![猫咪](https://example.com/cat.jpg) | 这是一只可爱的小猫咪| ![猫咪](https://example.com/cat.jpg) | 
---|---|---|

{% include base_path %}

{% for post in site.people reversed %}
  {% include archive-single.html %}
{% endfor %}
