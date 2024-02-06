---
layout: page
title: forecast
permalink: /forecast/
description: 
nav: true
nav_order: 4
related_publications: zhang2023forecasting
---
Humid heatwaves, characterized by high temperature and humidity combinations, challenge tropical societies. Extreme wet-bulb temperatures (TW) over tropical land are coupled to the warmest sea surface temperatures (SST) by atmospheric convection and wave dynamics (see Zhang, Held, and Fueglistaler, 2021 on my publications page for details). Here, we harness this coupling for seasonal forecasts of the annual maximum of daily maximum TWmax. In Zhang et al. (2023), we develop a multiple linear regression model that explains 80% of the variance in tropical mean TWmax and significant regional TWmax variances. Forecast of the annual maximum wet-bulb temperature TWmax averaged over land between 30°S and 30°N and over four regions listed in the menu below. Place your mouse on the interactive chart to read the probability of setting new records. The Oceanic Niño Index for December (NDJ) 2023 is 2.0 based on [NOAA](https://origin.cpc.ncep.noaa.gov/products/analysis_monitoring/ensostuff/ONI_v5.php).


<div class="figure-container">
  <div class="figure-item">
   {% include pr_exc_tropical_mean.html %}
     </div>
  <div class="figure-item">
    {% include twmax_tropical_mean.html %}
  </div>
</div>






<div class="row">
    <div class="col-md-16 mt-6 mt-md-0 mx-auto"> 
        <figure class="figure">
            {% include figure.html path="assets/img/enso_tw_fig4.png" title="example image" class="img-fluid rounded" %}
            <figcaption class="figure-caption text-center">Map of the root mean squared error (RMSE) of the model and the four focus regions in red boxes.</figcaption>
        </figure>
    </div>
</div>



