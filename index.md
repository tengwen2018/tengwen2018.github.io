---
layout: default
title: "Daily Notes"
hide_title: true
---

# 腾文的笔记汇总

以下是所有已发布的月度工作记录：

<ul>
  {% for note in site.notes %}
    <li>
      <a href="{{ note.url }}">{{ note.title }}</a>
    </li>
  {% endfor %}
</ul>
