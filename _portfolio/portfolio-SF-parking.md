---
title: "Spatial Analysis: Modeling Parking Demand in SF"
excerpt: 
header:
  teaser: /assets/images/sample.gif
layout: single
---
{% capture fig_img %}
![Binomial Modeling Result]({{ "/assets/images/sample.gif" | relative_url }})
{% endcapture %}

<figure>
  {{ fig_img | markdownify | remove: "<p>" | remove: "</p>" }}
  <figcaption>Binomial Modeling Result</figcaption>
</figure>

In a team of two, we developed a predictive model that predicts the probability that an area will be inundated with flood water. The report explains the planning motivation as well as illustrate the environment features, model performance, and prediction results.

Specifically, I used hydrology tools in _ArcGIS_ to turn digital elevation models (DEM) into an ordered network of streams and watersheds. From there I was able to create environment and hydrological features such as slope, basin, and distance to downstream. Then in _R studio_ I created fishnet grid areas as well as developed more meaningful variables such as distance to nearest slope and categorized slopes. After my teammate developed and validated the model, I double-checked as well as conducted spatial cross-validation. Finally, I adjusted the visualizations and turned everything into a report in _InDesign_.

[Narrated Presentation](https://youtu.be/zU5NV32CpKA){: .btn .btn--info}

[View Presentation PDF](https://github.com/gillianzhaoxz/web/blob/master/assets/doc/sf_parkingdemand.pdf){: .btn .btn--info}

_disclamer: this project is a part of a graduate course_