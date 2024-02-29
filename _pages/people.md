---
layout: archive
title: "People"
permalink: /people/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

# PHD Students
| <img src='./images/500x300.png'> | - Research interests: Natural Language Processing, Machine Learning<br/>- Email: member1@email.com | **Member 2** | - Research interests: Natural Language Processing, Machine Learning<br/>- Email: member1@email.com |
| :----------- | :----------------------------------------------------------: | ------------ | ------------------------------------------------------------ |
|              |                                                              |              |                                                              |
|              |                                                              |              |                                                              |
|              |                                                              |              |                                                              |
```


{% include base_path %}

{% for post in site.people reversed %}
  {% include archive-single.html %}
{% endfor %}
