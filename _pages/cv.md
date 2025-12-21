---
layout: archive
title: "简历"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

教育背景
======
* 硕士，计算机科学，香港城市大学（东莞），2025 - 2027
* 学士，软件工程，南京信息工程大学，2021 - 2025

研究兴趣
======
* 大模型安全 (Large Language Model Security)
* 可信AI (Trustworthy AI)
* Agent安全 (Agent Security)
* 多模态安全 (Multimodal Security)

论文发表
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
学术报告
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
教学经历
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
