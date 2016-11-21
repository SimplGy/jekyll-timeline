---
layout: base
---

# jekyll-timeline
## A timeline for your GitHub Pages that doesn't need plugins or JavaScript

Source, and readme on [GitHub](https://github.com/SimplGy/jekyll-timeline).

### Examples 

<ul class="timeline-examples">
  {% for post in site.posts %}
    <li class="post summary">
      <a href="{{ site.baseurl }}{{ post.url }}" title="{{ post.title }}">
        <!-- <p>{{ post.title }}</p> -->
        <img src="{{ site.baseurl }}/screencaps{{ post.id }}.png" />
      </a>
    </li>
  {% endfor %}
</ul>








