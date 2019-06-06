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

## Objective 

To analyse and understand the impact of clouds in satellite communication links using ground-based, high-resolution digital cameras.


## Team

This is a collaborative work between:
- [Nanyang Technological University Singapore](http://www.ntu.edu.sg/home/eyhlee/) 
- [Advanced Digital Sciences Center (ADSC)](http://vintage.winklerbros.net/index.html), Singapore
- [National University of Singapore](https://www.comp.nus.edu.sg/cs/bio/winkler/) 

## Description 

The central theme of this project is to use conventional cameras to capture images of a scene and derive essential information about its content. In particular, we focus our attention on images captured by ground-based sky cameras. Ground-based sky cameras, popularly known as Whole Sky Imagers (WSIs), are now extensively used by remote sensing analysts. They are useful in a variety of applications: signal attenuation analysis, local weather prediction, or solar and renewable energy forecasting. They complement conventional weather satellite images with higher temporal and spatial resolutions. The WSIs capture images of the earth's atmosphere at regular intervals of time. In this project, we analyze this huge amount of captured image data and propose several algorithms and methodologies for various applications.

<br />
We designed and built four different versions of ground-based sky cameras, which are efficient, low-cost, and highly flexible. Our custom-built WSIs are equipped with a high-resolution fish-eye lens that captures the images of the sky scene at user-defined intervals of time. Our imagers are modular with easily configurable hardware and software, offer a high image resolution (5184X3456 pixels), and cost less than US$3K to build. Furthermore, they give us the flexibility to explore the use of High Dynamic Range Imaging (HDRI) techniques to capture the wide range of luminosity of the sky scene.   
<img src="{{ site.url }}/images/1-sky-camera.jpg">
*Various models of our designed sky cameras, along with their corresponding captured images.*   

<br />
With the vast image data collected from these ground-based sky cameras, extracting valuable information viz. cloud coverage can be challenging. Cloud segmentation of the images into cloud vs. sky regions is one of the fundamental problems, as clouds are non-rigid, and have a wide variety of shapes, sizes, colors or textures. In this project, we present a supervised segmentation framework for ground-based sky/cloud images based on a systematic analysis of different color spaces and components. Unlike other state-of-the-art cloud segmentation methods, our proposed approach is entirely learning-based and does not require any manually defined parameters. As part of this effort, we released [a large segmentation database](http://vintage.winklerbros.net/swimseg.html) of annotated sky/cloud images to the research community.   

<br />
<img src="{{ site.baseurl }}/images/2-multi-class.png">
<br />
*(From left to right) Sample input images, probabilistic cloud detection, 3-level ground-truth image, 3-level detected image.*   

<br />
As a part of benchmarking with other state-of-the-art cloud detection algorithms, we have also annotated and released the [three-level ground-truth images](https://github.com/Soumyabrata/HYTA) of the popular [HYTA](https://journals.ametsoc.org/doi/abs/10.1175/JTECH-D-11-00009.1) dataset. We have also extended our cloud segmentation methodology on High-Dynamic-Range (HDR) images. It assists in capturing the details of an entire scene with a regular camera in a single HDR shot. We have also released the first [HDR cloud segmentation dataset](http://vintage.winklerbros.net/shwimseg.html), along with manually annotated ground-truth images to the research community. Such analysis was also extended to <a href="https://arxiv.org/pdf/1705.10583.pdf">nighttime sky/cloud images</a>, and we also released the <a href="http://vintage.winklerbros.net/swinseg.html">first dataset of nighttime sky/cloud images</a> to the community. Recently, we employed deep neural networks to solve the cloud segmentation problem for <a href="https://arxiv.org/pdf/1904.07979.pdf">binary nychthemeron images</a> and <a href="https://arxiv.org/pdf/1903.06562.pdf">ternary daytime images</a>, with a high degree of accuracy. 

<br />
In addition to cloud segmentation, we also proposed a framework for <a href="https://soumyabratadev.files.wordpress.com/2016/06/icip2015cat.pdf">automatic cloud type recognition</a> that classifies sky/cloud image patches efficiently into various cloud types. Our proposed algorithm systematically integrates both *color* and *texture* cues of cloud and has a good multi-class classification accuracy. We also released a [large-scale cloud categories database](http://vintage.winklerbros.net/swimcat.html) for further benchmarking purposes.  

<img src="{{ site.baseurl }}/images/3-five-classes.png">
<br />
*Sample representative image of (a) Clear sky, (b) Patterned clouds, (c) Thick dark clouds, (d) Thick white clouds, and (e) Veil clouds.*   
<br />

Finally, we use our ground-based sky cameras in a stereo-setup for <a href="https://soumyabratadev.files.wordpress.com/2017/06/icip17recons.pdf">accurate reconstruction of cloud-base height</a>. We propose a consistent and optimal point localization algorithm for noisy camera poses and error-free matching between image frames. A rigorous analysis of such localization problems provides better insights in cloud-base height reconstruction.  

<img src="{{ site.baseurl }}/images/5-3d-cloud.png">
*3D point cloud for an image pair computer from the computer-generated sequence. The bounding boxes in which [Blender](https://www.blender.org/) generates the cloud are shown in green. The two black dots indicate the position of the imagers.*   


## Results   

Please refer to the [publications](https://soumyabrata.github.io/publications/).  