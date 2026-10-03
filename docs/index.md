---
layout: default
title: Home
---

# Welcome to my Website!

I am Maria Jose, a graduate student at the University of Virginia working with the CMS experiment.

My research focuses on experimental high energy physics, with an emphasis on searches for physics beyond the Standard Model and detector development for the CMS HL-LHC upgrade.

## Research

My PhD research includes a search for self-interacting dark matter with displaced lepton jets and the development, assembly, testing, and commissioning of the CMS Barrel Timing Layer.

I am interested in experimental particle physics, detector development, and future collider experiments.

[Learn more about my research]({{ "/research/" | relative_url }})

## Latest Posts

{% for post in site.posts %}
### [{{ post.title }}]({{ post.url | relative_url }})

*{{ post.date | date: "%B %-d, %Y" }}*

{{ post.excerpt }}

{% endfor %}
