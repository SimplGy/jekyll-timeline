---
layout: base
---

# jekyll-timeline Examples <small>[GitHub](https://github.com/SimplGy/jekyll-timeline)</small>



<ul>
  {% for post in site.posts %}
    <li class="post summary">
      <a href="{{ site.baseurl }}/{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
