---

layout: default
title: 摄影图文
permalink: /photos/
---

# 摄影图文

{% assign articles = site.collections | where: "label", "photos" | first %}
{% if articles %}
{% assign articles = articles.docs | sort: "date" | reverse %}
{% for post in articles %}
- [{{ post.title | default: post.name }}]({{ post.url | relative_url }}){% if post.date %} · {{ post.date | date: "%Y-%m-%d" }}{% endif %}
{% endfor %}
{% endif %}
