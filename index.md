---
layout: default
title: Index
---

<pre>
# find . -type f -name "*.txt" 
{% for post in site.posts %}
<a href="{{post.url}}">./{{post.category}}/{{ post.title }}.txt</a>
{% endfor %}
</pre>
