---
layout: default
---
# musings

A collection of my thoughts.

{% for post in site.posts %}
<a href="{{ post.url  }}">{{ post.date | date: "%Y-%m-%d" }} | <b>{{ post.title  }}</b></a>
{% endfor %}
