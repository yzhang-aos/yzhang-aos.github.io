---
layout: page
title: Extreme wet-bulb temperature controlled by mean warming
img: assets/img/project_prof_2.jpeg
importance: 2
category: work
topic: Heat Stress
year: 2021
description: >-
  Free tropospheric temperature sets a nearly uniform cap on local land wet-bulb
  temperature, so mitigating mean warming directly caps the worst tropical
  heat-stress events.
equation: '\Delta \mathrm{TW}_{\max}^{\text{land}} \approx \Delta \overline{T}'
related_publications: zhang2021projections
---

Heat stress is the joint effect of high temperature and high humidity on humans and mammals. Given that climate models already struggle to accurately capture extreme temperatures, one might initially think that adding the dimension of humidity would further complicate the projection of extreme heat stress. Interestingly, the opposite is true.

Convective instability is a natural process in the atmosphere that prevents persistent buoyant conditions in near-surface air thereby regulating extreme heat and humidity. 

We use wet-bulb temperature (TW) as a metric for heat stress, which is, by definition, tightly related to moist static energy which is also a function of temperature ($T$) and humidity ($q$):

$$
c_p\mathrm{TW}+L_vq_{\rm sat}(\mathrm{TW}) = c_pT+L_v q= \mathrm{MSE}-gz_s,
$$

where $z_s$ is surface elevation. The <a href="https://yzhang-aos.github.io/research/moist-static-energy-distribution/">dynamics</a> that control the maximum moist static energy also make the maximum wet-bulb temperature in the tropics relatively uniform, both on land and on the ocean. The changes of the maximum wet-bulb temperature over land and ocean are thus roughly equal:

$$
\Delta \mathrm{TW}_{\max}^{\text{land}} \approx \Delta \mathrm{TW}_{\max}^{\text{ocean}}.
$$

This finding allowed us to work around the land’s varying topography and surface types by calculating how climate change would affect the wet-bulb temperature over the homogenous surface of the ocean — which would play out similarly on land. What climate change does is raise the bar on the wet-bulb temperature. The tropospheric column stabilizes itself according to this new upper limit, and extreme wet-bulb temperatures across the tropics rise (see schematic). 

<div class="row">
    <div class="col-sm-12 col-md-12 col-lg-12 mt-3 mt-md-0 mx-auto">
        <figure class="figure">
            {% include figure.html path="assets/img/Zhang_ngeo_schematic.jpg" title="example image" class="img-fluid rounded" %}
                    </figure>
    </div>
</div>

With this reasoning, we project that the annual maximum wet-bulb temperature over tropical land rises in step with $\overline{T}$, the surface temperature averaged over the tropics,

$$
\Delta \mathrm{TW}_{\max}^{\text{land}} \approx \Delta \overline{T},
$$

that is, by about 1 degree Celsius for every degree of mean warming. 

<div class="row">
    <div class="col-sm-12 col-md-12 col-lg-12 mt-3 mt-md-0 mx-auto">
        <figure class="figure">
            {% include figure.html path="assets/img/Zhang_ngeo_fig.jpg" title="example image" class="img-fluid rounded" %}
             <figcaption class="figure-caption text-center">Model agreement on regional TW$_{\rm max}$ projections. The dashed black lines indicate the 1/1 ratio.</figcaption>
                    </figure>
    </div>
</div>

Though many studies have suggested potential surprises in extreme weather that climate change could bring, we do not think extreme wet-bulb temperatures in the tropics are one of these cases. This work brings a positive message regarding climate mitigation – If we mitigate the mean warming, we also reduce the most extreme heat stress episodes throughout the tropics.

The same land–ocean coupling also makes the tropical-land wet-bulb record predictable a season ahead — see the <a href="https://yzhang-aos.github.io/forecast/">forecast page</a> for details.