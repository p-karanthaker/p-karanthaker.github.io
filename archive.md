---
title: Archive
description: All blog posts written by Karan Thaker.
---
# Latest Posts

I write things...sometimes, and sometimes I just want to share or keep a record 
of something cool or useful that I come across. Here you'll find anything I post
\- from coding projects and fitness talk, to my favourite recipes. I am doing 
this in hope that it becomes a great big archive of all the things I find myself
doing in life, and maybe even helps one of you in some way.

<ul>
  {% for post in site.posts %}
    <li>
      <h2><a class="default-link" href="{{ post.url }}">{{ post.title }}</a></h2>
      <p>{{ post.excerpt }}</p>
    </li>
  {% endfor %}
</ul>
