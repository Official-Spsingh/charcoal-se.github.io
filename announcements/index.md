---
title: Announcements
redirect_from: /announcements
permalink: /announcements/
---

# Announcements

{% for post in site.categories.announcements %}

  - [{{ post.title }}]({{ post.url }})
    > {{ post.excerpt }}

{% endfor %}
