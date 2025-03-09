---
layout: page
title: Why will tropical rainfall become more unevenly distributed in space?
description: 
importance: 4
category: work
related_publications: zhang2019mechanism
---
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

