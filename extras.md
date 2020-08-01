---
layout: default
title: About
permalink: /extras
---
# Extras

<ul class="post-list archive-ul">
  {% for post in site.categories.memo %}
    <li class="archive-li">
      <h2>
        <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
      </h2>
    </li>
  {% endfor %}
</ul>
