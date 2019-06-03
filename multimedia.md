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
With the rapid development of internet services, there has been a massive surge in the development of online multimedia videos. These videos are equipped with *[skip-ad](https://medium.com/@alenarajwani/the-mistake-you-make-each-time-you-press-the-skip-ad-button-on-youtube-e4f21b4d101c)* buttons and ad blockers, bringing online marketing and advertisement to a standstill. In this project, we solve this problem by seamlessly integrating new adverts into existing adverts in videos. We design a [system](https://arxiv.org/pdf/1808.00163.pdf) that can localize an existing advert in an image frame (from the video sequence), and replace it with a new target advert.    
<img src="{{ site.baseurl }}/images/mul-story.png">
<br />
*(From left to right) Original image, Augmented image with new target advert.*   

<br />

Traditionally, the frames in a video are manually checked by the video-editors, for possible candidates in new advert integration. This is obviously cumbersome and time-consuming. In this project, we propose a deep-learning module called <a href="https://arxiv.org/abs/1811.04115">ADNet</a> that automatically detects if a video frame contains an existing advert. Furthermore, we also use a deep-learning based method to localize the position of the advertisement in the video frame. Based on a large-scale dataset of outdoor scenes with manually annotated ground-truth maps, we propose a probabilistic billboard detection framework. We further refine the bounding box of the billboard, using a deep-learning based refinement network. 

<img src="{{ site.baseurl }}/images/mul-localization.jpg">
<br />
*(From left to right) Input image, Binary ground-truth map, Detected advert, Localized advert.*  

## Demonstration 

[<img src="{{ site.baseurl }}/images/video-grab.png">](https://youtu.be/zaKpJZhBVL4)

## Results   
Please refer to the [publications](https://soumyabrata.github.io/publications/). It also received extensive media coverage: 
[<a href="https://www.tcd.ie/news_events/articles/adapt-scoops-technology-ireland-award-for-disruptive-advertising-system/">tcd</a>]
[<a href="https://www.dcu.ie/news/news/2018/Nov/ADAPT-scoops-Technology-Ireland-Award-for-Disruptive-Advertising-System.shtml">dcu</a>]
[<a href="https://www.irishtimes.com/business/technology/learnupon-takes-top-prize-at-annual-technology-ireland-awards-1.3708041">irishtimes</a>]
[<a href="https://www.isin.ie/go/news_events/news/learnupon-adapt-centre-amongst-the-winners-at-the-2018-technology-awards">isin</a>]
[<a href="https://www.adaptcentre.ie/news/adapt-research-centre-scoops-technology-ireland-award-for-disruptive-advert">adaptcentre</a>] 
[<a href="http://www.engineersjournal.ie/2018/11/28/adapt-wins-technology-ireland-award-for-disruptive-advertising-system/">engineersjournal</a>] 
[<a href="https://www.adaptcentre.ie/news/adapt-research-shortlisted-for-2018-technology-ireland-software-industry-aw">adaptcentre</a>] 
[<a href="https://www.technology-ireland.ie/Sectors/TI/TI.nsf/vPages/Awards~finalists-2018!OpenDocument">technology-ireland</a>] 
[<a href="https://www.ibec.ie/IBEC/Press/PressPublicationsdoclib3.nsf/vPages/Newsroom~finalists-named-for-technology-ireland-2018-awards-25-10-2018?OpenDocument">ibec</a>] 
[<a href="https://www.techcentral.ie/technology-ireland-awards-shortlist-revealed/">techcentral</a>].