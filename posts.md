---
layout: default
title: Posts
---

{% for post in site.posts %}
<li>
	<a href="/book_reviews/{{ post.url }}">{{ post.title }}</a>
</li>
{% endfor %}


