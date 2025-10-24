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
* 2018（预计）：版本控制理论博士，GitHub University
* 2014：Jekyll 硕士，GitHub University
* 2012：GitHub 学士，GitHub University

工作经历
======
* 2024 年春：Academic Pages 合作者
  * GitHub University
  * 主要职责：维护并改进模板
  * 指导老师：The Users

* 2015 年秋：科研助理
  * GitHub University
  * 主要职责：合并 Pull Request
  * 指导老师：Professor Hub

* 2015 年夏：科研助理
  * GitHub University
  * 主要职责：标注问题
  * 指导老师：Professor Git
  
技能
======
* 技能 1
* 技能 2
  * 子技能 2.1
  * 子技能 2.2
  * 子技能 2.3
* 技能 3

学术发表
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
报告
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
教学
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
服务与领导力
======
* 目前加入 43 个不同的 Slack 团队
