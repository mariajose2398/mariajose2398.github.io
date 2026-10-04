---
layout: default
title: Home
---

# Welcome!

I am a graduate student at the University of Virginia working in experimental high energy physics.

This website is my personal space to share a little about my work, travels, photography, hobbies and things I find interesting. 

If you are interested to know more about me, please check [about]({{ "/aboutme/" | relative_url }}) page.
If you are curious what I do in physics, you can find more on the  [Research]({{ "/research/" | relative_url }}) page.


## Latest Posts
{% for post in site.posts %}
<div class="post-box">

<h3>
  <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
  <span class="post-date">{{ post.date | date: "%B %-d, %Y" }}</span>
</h3>

{{ post.excerpt }}

</div>
{% endfor %}
