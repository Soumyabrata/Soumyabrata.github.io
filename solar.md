---
layout: novipage
permalink: /solar/
title: Research
tags: [code]
modified: 11-June-2018
comments: false
sidebar:
  nav: sidebar-research
---

# Solar Analytics

## Objective 
To provide useful insights in the field of solar analytics using ground-based cameras and other weather sensors. 

## Team
This is a collaborative work between:
- [Nanyang Technological University Singapore](http://www.ntu.edu.sg/home/eyhlee/)
- [Advanced Digital Sciences Center (ADSC)](http://vintage.winklerbros.net/index.html), Singapore
- [Copernicus Institute of Sustainable Development](https://www.uu.nl/en/research/copernicus-institute-of-sustainable-development), Utrecht University, The Netherlands. 

## Description 

Owing to the growing concern of global warming and over-dependence on fossil fuels, there has been a huge interest in last years in the deployment of Photovoltaic (PV) systems for generating  electricity. The  output power of a PV array greatly depends, among other parameters, on solar irradiation. However, solar  irradiation has an intermittent nature and suffers from rapid fluctuations. This creates challenges when  integrating  PV systems in the electricity grid and calls for  accurate  forecasting methods of solar  irradiance. 

<br />
In this research theme, we attempt to use a multi-modal approach of using data from various sensors to better understand such fluctuations in solar irradiance. We use time-series data of measured solar irradiance, together with clear-sky solar irradiance, to forecast solar irradiance upto a period of 20 minutes. We use techniques derived from time-series theory, to <a href="https://arxiv.org/abs/1807.05872">model the seasonality</a> of solar irradiance, as captured in solar sensors. 
<img src="{{ site.baseurl }}/images/38000-lead-50.png">   
*Prediction of solar irradiance for shorter lead time.*   

<br />
In addition to using weather data, we also derive solar analytics information from images, captured via ground-based sky cameras. Unlike solar pyranometers and other regular meteorological sensors, ground-based sky images have additional information about the continuous evolution of cloud over time. We use these cloud/sky images to propose a solar radiation estimation model, that can accurately <a href="https://arxiv.org/abs/1606.02546">capture the short-term fluctuations</a> of solar irradiance. We also use these sequence of images to estimate cloud motion fields. These motion fields are derived from optical flow formulation of two successive image frames. We compute the horizontal and vertical translation of pixels, and thereby <a href="https://arxiv.org/pdf/1610.06666v1.pdf">predict future locations of cloud</a> with a lead time of a few minutes.   
<img src="{{ site.baseurl }}/images/optical-flow.png">   
*Using two successive image frames, we compute the optical flow fields, and thereby predict the future image frames.*   

<br />
Furthermore, such multi-modal data can be useful for the purpose of <a href="https://arxiv.org/pdf/1610.06667v1.pdf">detecting rainfall onset</a>. We use ground-based sky cameras to detect the onset of rainfall. Using the luminance of the camera image as an indicator, we can accurately identify the precipitation onset. We define Clearness Luminance Index as the ratio of measured luminance value to the clear-sky luminance value. 
<img src="{{ site.baseurl }}/images/cli-trend-conc.png">   
*We observe that the index value gradually decreases as it approaches a rain event, and reaches a minimum during rainfall. Post rain event, the clearness luminance index gradually increases with the passage of time. We also plot the Cumulative Distribution Plot (CDF) of clearness luminance index of images within and outside the time window of ±15 minutes.*  



## Results   

Please refer to the [publications](https://soumyabrata.github.io/publications/).  
