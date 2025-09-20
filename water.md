---
layout: novipage
permalink: /water/
title: Research
tags: [code]
modified: 19-Sep-2025
comments: false
sidebar:
  nav: sidebar-research
---

# Water

## Objective 
To develop scalable methods for accurate water body detection using spectral analysis and deep learning.

## Team
This is a collaborative work between:
- [ADAPT SFI Research Centre](https://www.adaptcentre.ie/)
- [University College Dublin](https://www.cs.ucd.ie/)

## Description 

Water is a cornerstone of ecosystems and human society, yet monitoring its distribution and dynamics remains challenging. Our research develops computational methods to detect, classify, and monitor water bodies using remote sensing data. By combining hyperspectral and multispectral satellite imagery with advanced machine learning, we deliver accurate and scalable water monitoring solutions.

<br />
We investigate the use of spectral indices such as Normalized Difference Vegetation Index (NDVI), Water Index (WI), Normalized Difference Water Index (NDWI), and Modified Normalized Difference Water Index (MNDWI) for extracting rivers, lakes, coastal waters, and even narrow streams. Our studies show that traditional indices often misclassify water pixels, whereas the Modified Normalized Difference Water Index (MNDWI) excels in delineating coastlines and small streams. This enables precise mapping for environmental monitoring and hydrological applications.
<img src="{{ site.baseurl }}/images/water-NDVI.png">   
*Comparison of spectral indices (NDVI, WI, NDWI, MNDWI) applied to hyperspectral data, illustrating how MNDWI more effectively delineates rivers, coastlines, and small streams.*   

<br />
Alongside spectral approaches, we advance AI-driven methods by integrating attention mechanisms into deep learning architectures. Using multispectral data from the EuroSAT dataset, our models achieve up to 86 percent classification accuracy, significantly outperforming standard networks. The attention-based framework enhances the model’s ability to focus on the most relevant spatial and spectral features, resulting in robust and generalizable performance.  
<img src="{{ site.baseurl }}/images/attention-resnet.png">   
*Architecture of the Attention ResNet50 model, which enhances classification accuracy by focusing on the most relevant spatial and spectral features in multispectral satellite imagery.*   

<br />
Together, these advances form a comprehensive framework for reliable water monitoring systems, supporting water resource management, biodiversity conservation, and climate resilience.



## Results   

Please refer to the [publications](https://soumyabrata.github.io/publications/).  
