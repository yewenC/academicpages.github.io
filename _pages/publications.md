---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

<div align=center>![cyw](https://github.com/yewenC/academicpages.github.io/blob/master/images/image-alignment-580x300.jpg?raw=true)
<br>
<p align="center">
  <span style="font-size: 1.5em;">Yewen CAO</span>
</p >
<br>
_started Aug 2024_  
_research interests: wireless communications, signal processing, IoT_  
_email: 2200201101@stu.hit.edu.cn_  

- B.E. in Communication Engineering, Harbin Institute of Technology (Sep. 2020-June 2024)

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
