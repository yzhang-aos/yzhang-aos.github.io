---
layout: page
title: Can heatwave temperatures go up indefinitely?
img: assets/img/project_prof_1.png
importance: 1
category: work
related_publications: zhang2023upper
permalink: /_site/projects/1_project/

---

In recent summers, the world has witnessed one extreme heatwave after another, raising concerns related to climate change. Such events prompt the pressing question: what limits the maximum surface temperature?

Traditionally, researchers have focused on processes that elevate surface temperatures, such as blocking anticyclones, dry soil, intense solar radiation, and the advection of warm air. These processes accumulate heat within the atmospheric boundary layer, the layer that extends a few kilometers above the Earth's surface.

However, this study takes a different angle. We explore the mechanisms that halt any further rise in surface temperatures. Essentially, if the surface temperature climbs too high, the nearby air mass becomes buoyant, leading to convective instability. This results in vigorous upward motion, effectively exporting the accumulated heat out of the boundary layer. Under conditions of a blocking anticyclone, this mechanism enables us to deduce an upper limit for the surface temperature,  $T_s$. This theoretical upper bound solely depends on the temperature at the middle troposphere, $T_{500}$, which is considered externally given by the anticyclone and remains relatively stable throughout a heatwave's development.


\begin{equation}
T_{s} \leq T_{\rm 500}+\frac{L_v}{c_p}q_{\rm sat}(T_{\rm 500})+\frac{g\overline{z_{\rm 500}}}{c_p\overline{T_{\rm 500}}}T_{\rm 500}-\frac{g}{c_p}z_s.
\end{equation}


<div class="row">
    <div class="col-md-6 mt-3 mt-md-0 mx-auto">
        <figure class="figure">
            {% include figure.html path="assets/img/upper_bound.png" title="example image" class="img-fluid rounded" %}
            <figcaption class="figure-caption text-center">Theoretical upper bound of surface temperature divides the phase space into unstable and stable parts, with observations lying in the stable part.</figcaption>
        </figure>
    </div>
</div>


This upper bound is nonlinearly dependent on $T_{500}$ due to the property of warmer air holding more water vapor, a relationship governed by the Clausius-Clapeyron equation. As a result, with each increment in $T_{500}$  warming, the change in the upper bound accelerates. In our current climate, the hottest days of the year correspond to a $T_{500}$  value that yields a slope of approximately 2 for the upper bound shown in the Figure. This partially explains why annual maximum temperatures over land have been increasing at roughly double the rate of the global mean surface temperature.

By highlighting the role of convective instability in heatwaves and presenting a theoretical upper bound, this work offers a fresh perspective on the dynamics of extreme temperature events.

<span class="cover-image-source">Cover image source: <a href="https://www.nytimes.com/interactive/2022/07/19/world/europe/uk-europe-heat-map.html">NY Times</a></span>

<style>
.cover-image-source {
    font-size: 0.8em; /* 80% of the parent element's font size */
}
</style>