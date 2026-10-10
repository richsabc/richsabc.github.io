
---
layout: default
title: 摄影图文
permalink: /photos/
---

# 摄影图文

{% assign articles = site.photos | sort: "date" | reverse %}
{% for post in articles %}
- [{{ post.title }}]({{ post.url | relative_url }}){% if post.date %} · {{ post.date | date: "%Y-%m-%d" }}{% endif %}
{% endfor %}