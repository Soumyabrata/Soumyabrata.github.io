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
This is a collaborative work between:
- [The ADAPT Centre](https://www.adaptcentre.ie/), Trinity College Dublin 
- [Huawei Ireland Research Center](http://www.huawei.com/en/about-huawei/corporate-information/research-development), Dublin. 

## Description 
With the rapid development of internet services, there has been a massive surge in the development of online multimedia videos. These videos are equipped with *[skip-ad](https://medium.com/@alenarajwani/the-mistake-you-make-each-time-you-press-the-skip-ad-button-on-youtube-e4f21b4d101c)* buttons and ad blockers, bringing online marketing and advertisement to a standstill. In this project, we solve this problem by seamlessly integrating new adverts into existing adverts in videos. We design a system that can localize an existing advert in an image frame (from the video sequence), and replace it with a new target advert.    
<img src="{{ site.baseurl }}/images/advert-story.png">
<br />
*(From left to right) Original image, Augmented image with new target advert.*   

<br />

Traditionally, the frames in a video are manually checked by the video-editors, for possible candidates in new advert integration. This is obviously cumbersome and time-consuming. In this project, we propose a deep-learning module called <a href="https://arxiv.org/abs/1811.04115">ADNet</a> that automatically detects if a video frame contains an existing advert. Furthermore, we also use a deep-learning based method to localize the position of the advertisement in the video frame. Based on a large-scale dataset of outdoor scenes with manually annotated ground-truth maps, we propose a probabilistic billboard detection framework. We further refine the bounding box of the billboard, using a deep-learning based refinement network. 

<img src="{{ site.baseurl }}/images/advert-localization.jpg">
<br />
*(From left to right) Input image, Binary ground-truth map, Detected advert, Localized advert.*  

## Demonstration 

[<img src="{{ site.baseurl }}/images/video-grab.png">](https://youtu.be/zaKpJZhBVL4)

## Results   
Please refer to the [publications](https://soumyabrata.github.io/publications/). It also received extensive <a href="https://www.adaptcentre.ie/news/adapt-research-shortlisted-for-2018-technology-ireland-software-industry-aw">media coverage</a>.