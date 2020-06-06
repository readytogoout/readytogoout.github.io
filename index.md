---
layout: default
---

# Willkommen bei ready to go out!

<div>
  {% for post in site.posts %}
    <div class="card my-4">
      <h5 class="card-header">{{ post.title }}</h5>
      <div class="card-body">
        {{ post.excerpt }}<a href="{{ post.url }}">mehr lesen...</a>
      </div>
    </div>
  {% endfor %}
</div>
