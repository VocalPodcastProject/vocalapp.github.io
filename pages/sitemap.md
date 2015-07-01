---
title: Sitemap
permalink: /sitemap/
---

# Pages

{% for post in site.pages %}
 * [{{ post.title }}]({{ site.baseurl }}{{ post.url }})
{% endfor %}

# Posts

{% for post in site.posts %}
 * [*{{ post.date | date: "%e %B %Y" }}: *{{ post.title }}]({{ site.baseurl }}{{ post.url }})
{% endfor %}