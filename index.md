---
title: 首页
layout: default        # Minimal 主题已自带
---

# 📚 我的笔记索引

{% for p in site.pages %}
* [{{ p.title | default: p.path }}]({{ p.url | relative_url }})
{% endfor %}

---

# 🛠️ 补充内容

- [📈 交互图：频率 vs 波数](plot/index.html)
