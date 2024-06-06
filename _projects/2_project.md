---
layout: page
title: What atmospheric dynamics control extreme wet-bulb temperatures?
description: 
img: assets/img/project_prof_2.jpeg
importance: 2
category: work
related_publications: zhang2021projections
---

Heat stress is the joint effect of high temperature and high humidity on humans and mammals. Given that climate models already struggle to accurately capture extreme temperatures, one might initially think that adding the dimension of humidity would further complicate the projection of extreme heat stress. Interestingly, the opposite is true.

Convective instability is a natural process in the atmosphere that prevents persistent buoyant conditions in near-surface air thereby regulating extreme heat and humidity. 

We use wet-bulb temperature (TW) as a metric for heat stress, which is, by definition, tightly related to moist static energy which is also a function of temperature ($T$) and humidity ($q$):
\begin{equation}
c_p\mathrm{TW}+L_vq_{\rm sat}(\mathrm{TW}) = c_pT+L_v q= \mathrm{MSE}-gz_s,
\end{equation}
where $z_s$ is surface elevation. The <a href="https://yzhang-aos.github.io/projects/5_project/">dynamics</a> that control the maximum moist static energy also make the maximum wet-bulb temperature in the tropics relatively uniform, both on land and on the ocean. The changes of the maximum wet-bulb temperature over land and ocean are thus roughly equal:
\begin{equation}
\Delta \mathrm{TW_{max, land}} = \Delta \mathrm{TW_{max, ocean}}.
\end{equation}
This finding allowed us to work around the land’s varying topography and surface types by calculating how climate change would affect the wet-bulb temperature over the homogenous surface of the ocean — which would play out similarly on land. What climate change does is raise the bar on the wet-bulb temperature. The tropospheric column stabilizes itself according to this new upper limit, and extreme wet-bulb temperatures across the tropics rise (see schematic). 

<div class="row">
    <div class="col-sm-12 col-md-12 col-lg-12 mt-3 mt-md-0 mx-auto">
        <figure class="figure">
            {% include figure.html path="assets/img/Zhang_ngeo_schematic.jpg" title="example image" class="img-fluid rounded" %}
                    </figure>
    </div>
</div>

With this reasoning, we project that annual maximum wet-bulb temperatures in the tropics would increase by 1 degree Celsius with every degree of mean warming. 

<div class="row">
    <div class="col-sm-12 col-md-12 col-lg-12 mt-3 mt-md-0 mx-auto">
        <figure class="figure">
            {% include figure.html path="assets/img/Zhang_ngeo_fig.jpg" title="example image" class="img-fluid rounded" %}
             <figcaption class="figure-caption text-center">Model agreement on regional TW$_{\rm max}$ projections. The dashed black lines indicate the 1/1 ratio.</figcaption>
                    </figure>
    </div>
</div>

Though many studies have suggested potential surprises in extreme weather that climate change could bring, we do not think extreme wet-bulb temperatures in the tropics are one of these cases. This work brings a positive message regarding climate mitigation – If we mitigate the mean warming, we also reduce the most extreme heat stress episodes throughout the tropics.

<span class="cover-image-source">Cover image source: <a href="https://www.nytimes.com/2015/06/07/opinion/sunday/the-deadly-combination-of-heat-and-humidity.html">NY Times</a></span>

<style>
.cover-image-source {
    font-size: 0.8em; /* 80% of the parent element's font size */
}
</style>