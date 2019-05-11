---
title: Home
description: Homepage for Karan Thaker's personal website.
---

I write things...sometimes. Here you'll find anything cool or useful I come across.
From coding projects and fitness talk, to my favourite recipes. I'm doing 
this in the hope that it becomes a great big archive of all the things I find myself
doing in life, and maybe even helps someone along the way.
* * *

## Archive
<ol>
  {% for post in site.posts %}
    <li>
      <h4><a class="default-link" href="{{ post.url }}">{{ post.title }} - {{ post.date | date: "%Y/%m"}}</a></h4>
    </li>
  {% endfor %}
</ol>
