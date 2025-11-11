---
layout: archive
title: "CV-jp"
permalink: /cv_jp/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

学位
======

* 広島市立大学情報科学部知能工学科 学士（情報科学）2023年
* 広島市立大学大学院情報科学研究科知能工学専攻　修士（情報科学） 2025年  
* 広島市立大学大学院情報科学研究科情報科学専攻　博士後期課程　2025年～

プログラミングスキル
======
* Python
* C++

論文
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
発表
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
教育
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
資格
======
* 基本情報技術者試験合格 2019年
* 応用情報技術者試験合格 2020年
