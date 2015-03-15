---
layout: default
title: Archive
descript: Index of all writing.
---
{% for post in site.posts %}	
- [{{ post.title }}]({{ post.url }})
{% endfor %}	
