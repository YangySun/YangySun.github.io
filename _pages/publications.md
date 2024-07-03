---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

## Published Papers
### 2024
* Yangyang Sun, Fei Meng, Ruiyuan Li*, Yongxin Tang, Chao Chen, Jiang Zhong. Streaming Trajectory Segmentation Based on Stay-Point Detection. in 29th International Conference on Database Systems for Advanced Applications. (DASFAA 2024, CCF B)

### 2023
* Ruiyuan Li, Yangyang Sun, Chao Chen. 浅谈流批一体化的发展与挑战.(CCCF 2023)