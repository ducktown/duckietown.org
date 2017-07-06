---
layout: page
title: U. Montreal
permalink: classes/2017/17-Montreal/index.html
---

(to write)


## Updates to this page

<ul id='news'>
  {% for post in site.posts %}
  {% if post.categories contains '17-Montreal' %}
    <li>
    {{ post.date | date_to_long_string }} -
      <strong>{{ post.title }}</strong> -
      {{ post.content }}
    </li>
  {% endif %}
  {% endfor %}
</ul>

<style>
#news li p { display: inline; }
</style>
