---
title: "Spatial Analysis: Urban Growth Modeling for Pittsburgh MSA"
excerpt: 
header:
  teaser: /assets/images/portfolio-675growthmodel.png
layout: single
---

In a team of two, we completed a growth modeling project in anticipation of the Southwestern Pennsylvania Commission (SPC)’s next large-scale comprehensive planning process for Pittsburgh Metropolitan Statistical Area (MSA). Our findings aim to help planners model the interplay between supply and demand-side insights and guide smart-growth development across to places where growth can have economic and sustainable impacts.

Specifically, I trained a binomial model with 2001-2011 information and applied the model to forecast new developments in 2021 in _R studio_. This includes forecasting for a natural growth (demand-side) scenario and a planned growth (supply-side) scenario as well as providing allocation maps to guide sustainable growth.

For a quick view of the project, check out this one-pager poster I made in _InDesign_.

{% capture fig_img %}
![Prediction result maps]({{ "/assets/images/portfolio-675poster.png" | relative_url }})
{% endcapture %}

<figure>
  {{ fig_img | markdownify | remove: "<p>" | remove: "</p>" }}
  <figcaption>Poster</figcaption>
</figure>

For the full report, click on the "view report" button below.

[View Report](https://rpubs.com/gxzhao/pittsburghMSAgrowth){: .btn .btn--info}

_disclamer: this project is a part of a graduate course_