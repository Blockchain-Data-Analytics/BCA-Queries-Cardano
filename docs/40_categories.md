---
title: Cardano Queries Categories
---

￪ [bach to main](00_main.md)

# Categories

{% for cat in site.categories %}
  <h3>{{ cat[0] }}</h3>
  <ul>
    {% for post in cat[1] %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
{% endfor %}