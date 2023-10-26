---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}


<head>
  <style>
    .col-30 {
      width: 30%;
      float: left;
    }
    .col-70 {
      width: 70%;
      float: left;
    }
    .clearfix::after {
      content: "";
      display: table;
      clear: both;
    }
  </style>
</head>
<body>

<div class="container">
  <div class="col-30">
    < img src="https://github.com/yewenC/academicpages.github.io/blob/master/images/cyw.jpg?raw=true">
  </div>
  <div class="col-70">
    <p>右侧文字信息部分：<br>
    - 信息1<br>
    - 信息2<br>
    - 信息3</p >
  </div>
  <div class="clearfix"></div>
</div>

</body>
<div align=center><img src="https://github.com/yewenC/academicpages.github.io/blob/master/images/cyw.jpg?raw=true" width="300"></div>

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
