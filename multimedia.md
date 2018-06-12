---
layout: novipage
permalink: /multimedia/
title: Research
tags: [code]
modified: 11-June-2018
comments: false
sidebar:
  nav: sidebar-research
---

# Multimedia

## Objective 
To design an advertisement detection- and integration- system for multimedia videos, useful for next-generation online publicity. 

## Team
Worked in collaboration with [The ADAPT Centre](https://www.adaptcentre.ie/), Trinity College Dublin and [Huawei Ireland Research Center](http://www.huawei.com/en/about-huawei/corporate-information/research-development), Dublin. 

## Description 
With the rapid development of internet services, there has been a massive surge in the development of online multimedia videos. These videos are equipped with *skip-ad* buttons and ad blockers, bringing online marketing and advertisement to a standstill. In this project, we solve this problem by seamlessly integrating new adverts into existing adverts in videos. We design a system that can localize an existing advert in an image frame (from the video sequence), and replace it with a new target advert.   
<img src="{{ site.url }}/images/advert-story.png" width="200">
<img src="{{ site.baseurl }}/images/adapt-logo.png" width="140">
![image](/images/adapt-logo.png)
![image](/images/advert-story.png)
*(From left to right) Original image, Augmented image with new target advert.*   

<br />
We use a deep-learning based method to localize the position of the advertisement in an image frame. Based on a large-scale dataset of outdoor scenes with manually annotated ground-truth maps, we propose a probabilistic billboard detection framework. We localize the bounded billboard, using a deep-learning based refinement network.   
<img src="{{ site.baseurl }}/images/advert-localization.png">
*(From left to right) Input image, Binary ground-truth map, Detected advert, Localized advert.*  

## Results   

We are currently in the process of disseminating our research results to the community. 