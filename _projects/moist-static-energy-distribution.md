---
layout: page
title: Tropical convection and the moist static energy distribution
img: assets/img/project_prof_5.jpeg
importance: 3
category: work
topic: Tropical Dynamics
year: 2020
description: >-
  Deep convection conserves moist static energy fast enough to explain why the
  tropical free troposphere stays nearly uniform over both land and ocean — and
  why monthly rainfall is spread so unevenly across the tropics, with the
  unevenness set to grow.
equation: '\langle \mathrm{MSE} \rangle_P^{\text{land}} \approx \langle \mathrm{MSE} \rangle_P^{\text{ocean}}'
related_publications: zhang2020tropical, zhang2019mechanism
---


Ignoring the Earth’s rotation effect can be a useful approximation in some aspects of tropical atmospheric dynamics. Supporting evidence is that the tropical atmospheric temperature is roughly uniform in the horizontal direction from about 2 km above the surface till the top of the troposphere.

Another characteristic of the tropical troposphere is frequent deep convection. Deep convection brings a humid air mass from the surface to above 10 km in just a few hours while condensing the air mass’ water vapor to rainfall. This process is much faster than other processes that heat or cool the air mass. The air mass thus conserves its moist static energy (MSE) during convection, which is the sum of the sensible, latent, and potential energy.

With these pieces of information, we can describe the tropical atmospheric dynamics using a two-layer model – The uniform temperature in the upper layer (about 2-15 km in altitude) acts as a uniform bar to the non-uniform lower layer (the bottom 2 km). Whenever and wherever the MSE in the lower layer reaches the threshold put in place by the upper layer, the whole tropospheric column becomes unstable. This results in convection that exports energy away from this column and prevents the local MSE from increasing. Land and ocean both experience deep convection, and the long-standing conceptual pictures suggests that subcloud MSE over land and ocean should, in some way, be equal.

To clearly demonstrate this equality, some data treatment is necessary. This work crystallizes these ideas and articulates the connection between land and ocean subcloud MSE, highlighting that they are only coupled in regions experiencing deep convection. Using precipitation as a proxy for convective activity, we weight the subcloud MSE by precipitation $P$ to sample only the air mass that convects. This *convective MSE*, $\langle \mathrm{MSE} \rangle_P$, is nearly equal over land and ocean within the tropics, approximately between 20°S and 20°N:

$$
\langle \mathrm{MSE} \rangle_P^{\text{land}} \approx \langle \mathrm{MSE} \rangle_P^{\text{ocean}}.
$$

This research bridges the gap between conceptual frameworks and observational data, and has implications for extreme heat stress, as detailed in <a href="https://yzhang-aos.github.io/research/extreme-wet-bulb-temperature/">this project</a>.

<div class="row">
    <div class="col-sm-12 col-md-8 col-lg-10 mt-3 mt-md-0 mx-auto">
        <figure class="figure">
            {% include figure.html path="assets/img/zonal_erai_trmm_sub_daily_2001-2014.png" title="example image" class="img-fluid rounded" %}
            <figcaption class="figure-caption text-center">The precipitation-weighted subcloud MSE (b),  indicative of MSE conditions during deep convection, is uniform within the deep tropics and roughly equal between land and ocean, in stark contrast to the zonal-mean picture (a).</figcaption>
        </figure>
    </div>
</div>

The same subcloud MSE distribution also shapes how tropical rainfall is distributed in space.

The global mean precipitation will increase by about 2% per degree of global warming. This increase in rainfall is not distributed uniformally across the globe. Prior work has found that regions that are already humid and energetic will become comparatively more so with global warming, and the unevenness of precipitation distribution in the tropics will amplify. This is broadly consistent with physical mechanisms including the "dry-get-drier-wet-get-wetter" mechanism and the "upped-ante" mechanism. This aligns with known physical mechanisms, including the "dry-get-drier-wet-get-wetter" and the "upped-ante" mechanisms. Our work explores this topic from a slightly different angle by examining the probability distribution of monthly rainfall across tropical grid points, rather than from a fixed location perspective.

To effectively measure the unevenness in a distribution as non-normal as rainfall, we have adopted the  <a href="https://en.wikipedia.org/wiki/Gini_coefficient">Gini Index</a>, a concept originally from economics used to estimate how far a country's wealth or income distribution deviates from an equal distribution. While the Gini Index is not a flawless metric, it is effective for analyzing non-negative and heavy-tailed distributions like rainfall. A fun fact: the Gini Index of tropical monthly rainfall is higher (indicating greater evenness) than that of the country with the greatest income inequality!
<div class="row">
    <div class="col-md-6 mt-3 mt-md-0 mx-auto">
        <figure class="figure">
            {% include figure.html path="assets/img/zhang_grl_2019b.jpeg" title="example image" class="img-fluid rounded" %}
            <figcaption class="figure-caption text-center">The Gini Index, traditionally used to measure income inequality, is adapted here to quantify the uneven distribution of rainfall. It is defined by the Lorenz curve, which plots the cumulative proportion of the total rainfall (represented on the y-axis) against the corresponding cumulative proportion of the surface area (on the x-axis).</figcaption>
        </figure>
    </div>
</div>


We explained the change in the Gini Index of rainfall using the subcloud MSE difference between the convective regions and the tropical mean. This is consistent with and similar to prior work, specifically the "upped-ante mechanism." However, an interesting result that emerges from our work is that the GCM-simulated change in the subcloud MSE distribution can be rather accurately reproduced by a simple scaling. This provided insights into the widening of the distribution—the key factor being that the Clausius-Clapeyron relationship amplifies specific humidity gradients and, therefore, subcloud MSE gradients.
<div class="row">
    <div class="col-md-8 mt-6 mt-md-0 mx-auto">
        <figure class="figure">
            {% include figure.html path="assets/img/zhang_grl_2019.jpeg" title="example image" class="img-fluid rounded" %}
            <figcaption class="figure-caption text-center">The widening of the subcloud moist static energy (MSE) distribution can be explained by a simple scaling that incorporates the Clausius-Clapeyron relationship.</figcaption>
        </figure>
    </div>
</div>
