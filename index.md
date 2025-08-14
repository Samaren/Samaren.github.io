---
layout: home
---

# Добро пожаловать на мой блог!

{% raw %}{% for post in site.posts %}
<article>
  <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
  <p>{{ post.date | date: "%d.%m.%Y" }}</p>
  {{ post.excerpt }}
</article>
{% endfor %}{% endraw %}
