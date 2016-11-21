---
layout: base
---

# jekyll-timeline
## A timeline for your GitHub Pages that doesn't need plugins or JavaScript

### Examples 

<ul>
  {% for post in site.posts %}
    <li class="post summary">
      <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>











[GitHub](https://github.com/SimplGy/jekyll-timeline)