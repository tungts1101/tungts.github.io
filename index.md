---
layout: default
title: Home
---

<nav>
    {% for item in site.data.navigation %}
      <a href="{{ item.link }}" {% if page.url == item.link %}style="color: red;"{% endif %}>
        {{ item.name }}
      </a>
    {% endfor %}
</nav>
<h1>Hello</h1>