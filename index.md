---
layout: default
---

# Welcome to HocoNomNom

We're just getting started. If you're seeing this, you are lucky enough to stumble upon a great adventure!

More to come, stay tuned!

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
