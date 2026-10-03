---
layout: default
title: Home
---

# Welcome!

I am a graduate student at the University of Virginia working under the supervision of Prof. Chris Neu.

For my PhD thesis, I work on a novel search for dark matter with displaced lepton jets and the assembly and commissioning of the Barrel Timing Layer of the MIP Timing Detector. More details about my work can be found on the [Research]({{ "/research/" | relative_url }}) page.

My research interests lie in experimental high energy physics, especially in searches for physics beyond the Standard Model (BSM), detector building, testing and commissioning for the HL-LHC, and ultimately applying that expertise to building experiments for future colliders such as the FCC or a muon collider.


## Latest Posts

{% for post in site.posts %}
### [{{ post.title }}]({{ post.url | relative_url }})

*{{ post.date | date: "%B %-d, %Y" }}*

{{ post.excerpt }}

{% endfor %}
