---
layout: page
title: forecast
permalink: /forecast/
description: 
nav: true
nav_order: 4
related_publications: zhang2024forecasting
---

#### March 2025 Update: Successful Prediction of 2024 Tropical Land TWmax

In December 2023, [Zhang et al. (2024)](https://agupubs.onlinelibrary.wiley.com/doi/full/10.1029/2023GL106990) predicted that the tropical land mean TWmax (annual maximum hourly wet-bulb temperature) for 2024 would be **26.2°C (25.9–26.4°C)**. This prediction was based on the El Nino strength in December 2023. The actual observed value turned out to be **26.3°C**, falling well within our 95% prediction interval and closely matching the central estimate. This value surpassed the previous record set in 1998 **by 0.14°C**.  

The updated figure below, adapted from Supplementary Figure S4, includes reanalysis data for 2024. Our predictions not only captured the tropical land mean TWmax but also accurately forecasted TWmax in four of the world's most heat-stressed regions: Sahel, Southeast Asia, Sumatra, and North India.

**Our model thus successfully predicted the out-of-sample extreme wet-bulb temperatures in 2024.**

<div class="row">
    <div class="col-sm-10 col-md-10 col-lg-10 mt-3 mt-md-0 mx-auto">
        <figure class="figure">
            {% include figure.html path="assets/img/enso_tw_suppfig_walk_forward.png" title="Prediction for 2024" class="img-fluid rounded" %}
                        <figcaption class="figure-caption text-center">Figure S4 in Zhang et al. (2024), updated with new reanalysis data points for 2024 (red stars).</figcaption>
                    </figure>
    </div>
</div>



-----
#### Dec 2023 Post: Prediction of 2024 Tropical Land TWmax

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



