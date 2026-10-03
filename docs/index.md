---
layout: default
title: Home
---

# Welcome!

I am a graduate student at the University of Virginia working under the supervision of Prof. Chris Neu.


My research interests lie in experimental high energy physics, especially in searches for physics beyond the Standard Model (BSM), detector building, testing and commissioning for the HL-LHC, and ultimately applying that expertise to building experiments for future colliders such as the FCC or a muon collider.

For my PhD thesis, I work on a novel search for dark matter with displaced lepton jets and the assembly and commissioning of the Barrel Timing Layer of the MIP Timing Detector. More details about my work can be found on the [Research]({{ "/research/" | relative_url }}) page.

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
