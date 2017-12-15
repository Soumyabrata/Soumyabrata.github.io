---
layout: novipage
permalink: /cloud/
title: Research
tags: [code]
modified: 24-04-2017
comments: false
sidebar:
  nav: sidebar-research
---

# Cloud Imaging 

With the ubiquity of powerful digital cameras, there has been a paradigm shift in understanding and analyzing any scene. The central theme of this project is to use conventional cameras to capture images of a scene and derive essential information about its content. In particular, we focus our attention on images captured by ground-based sky cameras. Ground-based sky cameras, popularly known as Whole Sky Imagers (WSIs), are now extensively used by remote sensing analysts. They are useful in variety of applications: signal attenuation analysis, local weather prediction, or solar and renewable energy forecasting. They complement conventional weather satellite images with higher temporal and spatial resolutions. The WSIs capture images of the earth's atmosphere in regular intervals of time. In this project, we analyze this huge amount of captured image data, and propose several algorithms and methodologies for various applications.

<br />
We designed and built four different versions of ground-based sky cameras, which are efficient, low-cost, and highly flexible. Our custom-built WSIs are equipped with a high resolution fish-eye lens that captures the images of the sky scene at user defined intervals of time. Our imagers are modular with easily configurable hardware and software, offer a high image resolution (5184X3456 pixels), and cost less than US$3K to build. Furthermore, they give us the flexibility to explore the use of High Dynamic Range Imaging (HDRI) techniques to capture the wide range of luminosity of the sky scene.   
![]<img src="{{ site.baseurl }}/images/1-sky-camera.jpg">
*Various models of our designed sky cameras, along with their corresponding captured images.*

<br />
With the vast image data collected from these ground-based sky cameras, extracting valuable information viz. cloud coverage can be challenging. Cloud segmentation of the images into cloud vs. sky regions is one of the fundamental problems, as clouds are non-rigid, and have a wide variety of shapes, sizes, colors or textures. In this project, we present a supervised segmentation framework for ground-based sky/cloud images based on a systematic analysis of different color spaces and components. Unlike other state-of-the-art cloud segmentation methods, our proposed approach is entirely learning-based and does not require any manually defined parameters. As part of this effort, we released a large segmentation database of annotated sky/cloud images to the research community.   
<img src="{{ site.baseurl }}/images/2-multi-class.png">   

<br />
In addition to cloud segmentation, we also propose a framework for automatic cloud type recognition that classifies sky/cloud image patches efficiently into various cloud types. Our proposed algorithm systematically integrates both *color* and *texture* cues of cloud, and has a good multi-class classification accuracy. We also released a large-scale cloud categories database for further benchmarking purposes.  
<img src="{{ site.baseurl }}/images/3-five-classes.png">   

<br />
In most cases of atmospheric study, collocated weather stations are present alongside these sky cameras. Unlike solar pyranometers and other regular meteorological sensors, ground-based sky images have additional information about the continuous evolution of cloud over time. We use our cloud/sky images to propose a solar radiation estimation model, that can accurately capture the short-term fluctuations of solar irradiance. We also use these sequence of images to estimate cloud motion fields, and thereby predict future locations of cloud with a lead time of a few minutes. These solar estimation and cloud forecasting techniques can be applied in the field of solar energy generation and forecasting.   
<img src="{{ site.baseurl }}/images/4-solar.png">   

<br />
Finally, we use our ground-based sky cameras in a stereo-setup for accurate reconstruction of cloud-base height. We propose a consistent and optimal point localization algorithm for noisy camera poses and error-free matching between image frames. A rigorous analysis of such localization problems provides better insights in cloud-base height reconstruction.   
<img src="{{ site.baseurl }}/images/5-3d-cloud.png">   