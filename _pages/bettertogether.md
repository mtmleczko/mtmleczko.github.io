---
layout: page
title: Better Together
permalink: /bettertogether/blog/
---
<ul>
  {% for post in site.posts %}
    <li>
      {{ post.url }}{{ post.title }}</a> - {{ post.date | date: "%B %d, %Y" }}
    </li>
  {% endfor %}
</ul>
