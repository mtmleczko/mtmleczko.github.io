---
layout: page
title: Better Together
permalink: /bettertogether/blog/
---

<h2>Better Together</h2>
<p>Welcome to <strong>Better Together</strong>, TBD. 
<hr>

<ul class="post-list">
  {% for post in site.posts %}
    <li>
      <h3>{{ post.url | relative_url }}{{ post.title }}</a></h3>
      <p><small>{{ post.date | date: "%B %d, %Y" }}</small></p>
      <p>{{ post.excerpt | strip_html | truncatewords: 30 }}</p>
    </li>
  {% endfor %}
</ul>
