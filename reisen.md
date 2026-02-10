---
layout: page
title: Reisen
---

### Meine Reisen

Hier findest du die detaillierten Berichte meiner Touren.

{% for post in site.categories.reisen %}
#### [{{ post.title }}]({{ post.url | relative_url }})
*{{ post.date | date: "%d. %B %Y" }}*
{{ post.subtitle }}
{% endfor %}
