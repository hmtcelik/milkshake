---
layout: default
title: Blog
permalink: blog
---
# Posts


{% for post in site.posts %}

- # [{{post.title}}]({{post.url}})
{{ post.excerpt }}

{% endfor %}
