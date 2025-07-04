---
title: 首页
layout: default        # Minimal 主题已自带
---

# 📚 我的笔记索引

{% for p in site.pages %}
* [{{ p.title | default: p.path }}]({{ p.url | relative_url }})
{% endfor %}
