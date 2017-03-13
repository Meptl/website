---
layout: default
title:  "Person"
---

# The Blog Landing Page

Welcome to a blog space!

Here you'll find my mad ravings, emotional obsesions, and maybe just a touch of technical support.
They were likely coerced out during droughts of social interaction.
Though I suppose a drought would suggest some sort of low-point in a time series.
I hope you enjoy your stay.
Do excuse my writing style though;
It has this odd tendency of being very... grandiose in word selection.
It's odd given my verbal communication can be compared to that of a 3rd grader in timeout.

Well, as what I can only assume landing pages do, here's a list of posts:

<ul>
{% for post in site.posts %}
  <li>
    <a href="{{ post.url }}">{{ post.title }}</a>
  </li>
{% endfor %}
</ul>
