---
title: "Spatial Analysis: Modeling Parking Demand in SF"
excerpt: 
header:
  teaser: /assets/images/sfParking.gif
layout: single
---
{% capture fig_img %}
![Binomial Modeling Result]({{ "/assets/images/portfolio-505sfparking.png" | relative_url }})
{% endcapture %}

<figure>
  {{ fig_img | markdownify | remove: "<p>" | remove: "</p>" }}
  <figcaption>Binomial Modeling Result</figcaption>
</figure>

In a team of two, we conducted a statistical analysis on how space/time features influence parking behaviors. We also portrayed their implications on planning practice, especially to demand-responsive parking policy (smart parking). The presentation provides a walkthrough of our use case, data wrangling process, two final models (OLS and binomial), findings, and discussions.

Specifically, I researched the use case and built the models in _R studio_. We found several features that are significantly associated with parking demand. Some of our findings contradicts our assummption, as it indicates that the closer to tourist attractions the lower the demand. This suggests that Smart Meters might be curbing the demand as the prices there are usually higher.

[Narrated Presentation](https://youtu.be/zU5NV32CpKA){: .btn .btn--info}

[View Presentation PDF](https://github.com/gillianzhaoxz/web/blob/master/assets/doc/sf_parkingdemand.pdf){: .btn .btn--info}

_disclamer: this project is a part of a graduate course_