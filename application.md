---
layout: novipage
permalink: /application/
title: Overview
tags: 
modified: 24-04-2017
comments: false
sidebar:
  nav: sidebar-application
---

<!---
	Details about sidebar info is provided inside _data/navigation.yml file
-->
# Summary

I am currently in the academic job market. This page provides details on several aspects of application packet.

<br />
Curriculum Vitae | [<a href="https://soumyabratadev.files.wordpress.com/2018/05/cv-soumya.pdf">PDF</a>]


## Research Statement

The central theme of my research vision is to identify the specific computational problems in the above areas; and solve them in a cooperative manner with the domain experts. I am a firm believer of open science and research reproducibility – and thereby interested to advance science by promoting mutual collaboration and collective efforts amongst the community. I am interested in developing computer-vision based techniques to analyze earth observations. Currently, I am also involved in applying deep-learning based techniques in consumer multimedia data. In the future, I am interested to extend my expertise of artificial intelligence in medical imaging, specifically, in multimodal neuroimaging.   

### Remote sensing
The future of solving energy crisis lies at the successful integration of solar and renewable energy into the conventional power grid. With the rapid development in photogrammetric techniques and low-cost weather station data, it is now increasingly easier to collect massive image and other meteorological sensor data of the earth's atmosphere from the ground. The key to many unsolved problems lies in systematically analyzing these massive data, and fusing these diverse data types to develop new tools and techniques in renewable energy. My research plan in this particular field of atmospheric observations lies at the intersection of remote sensing and machine learning. In particular, I am interested to visualize in what ways state-of-the-art techniques inspired from computer vision and machine learning community help us in analyzing solar energy falling at earth's surface.   

<br />
I am particularly interested to delve more into solar and renewable energy sectors. Currently, solar energy is the one of the most reliable sources of renewable energy. However, it suffers from two major drawbacks---variability and uncertainty. 
It is a well-known fact that clouds have a huge impact on this intermittency of Photovoltaic (PV) energy generation. The passage of clouds over the solar panels can incur variable fluctuations in the received solar irradiance on the earth's surface. This problem of intermittency can be effectively solved, if the cloud motion vectors can be accurately forecasted with a considerable lead time. An accurate forecast model will be highly beneficial for efficient solar energy generation. Such problems in remote sensing merit a more rigorous and thorough analysis in a multitude of applications, and I intend to bridge that gap. I am interested to study such remote-sensing problems from the perspective of computer vision and machine learning communities.   

<br />
My interest in this field of solar and renewable energy stems from my previous doctoral experience at Nanyang Technological University Singapore. My previous work involved the study and analysis of clouds in tropical regions, like Singapore, and to understand its impact in the signal attenuation of satellite communication links. We used ground-based sky cameras that continuously captures the images of the earth's atmosphere at regular intervals of time. These images are useful in generating a highly localized cloud profile.   


<img src="{{ site.baseurl }}/images/wsi-image.jpg">
*We designed low-cost, ground-based sky cameras for continuous cloud profiling. The region around the sun (popularly known as circumsolar region) is highlighted with a white rectangle.*   

<br />
These hardware developments in imaging the earth's atmosphere inspired me to analyze better the problems in solar energy generation and forecasting. These devices can provide a new paradigm in understanding the solar energy dynamics. I am interested to analyze how clouds can have an impact on the total solar irradiance falling on the earth's surface. This is an interesting problem at hand: how the intermittency and rapid fluctuations in solar radiation be best captured by ground-based imaging devices? This can be intuitively explained by the fact that a drop in total solar irradiance leads to a decreased imaging luminance by the camera sensor, and vice versa. With the massive amount of imaging data collected by such cameras, it will provide us a good user study to apply machine-learning techniques on such imaging data. I plan to use deep-learning based neural networks to parametrize the camera response curve of the imaging sensors. I am interested in modeling the received solar irradiance from the luminance of the sky camera. Additionally, I also plan to further miniaturize the sky cameras, so that it can be deployed at multiple locations across the region of interest. This will help us in mapping the entire solar irradiance map over the considered region.   

<br />
In summary, I am interested to work on this project on solar irradiance estimation and forecasting, as I firmly believe that efficient- and clear- energy generation is the need of the hour. Of course, solar energy encompasses a significant proportion of renewable energy. This project can be collaboratively executed alongside international institutions and research groups. I have already developed initial contacts with two leading solar energy forecasting group: Center for Energy Research, UC San Diego and Solar Energy Research Institute of Singapore (SERIS).   

### Multimedia Data

With the advancement in deep-learning techniques in image and video analysis, we have seen a massive interest in the field of autonomous driving from the leading companies in AI. There are a plethora of interesting problems in vision-based, computer-assisted self driving. However, I am interested to solve a specific problem in this area: to provide an end-to-end system in detecting the traffic- and road- signs from low-resolution car dashboard cameras. This problem becomes more challenging with poor lighting conditions during fog and misty weather conditions.   

<br />
My previous doctoral experience also dealt with using near-infrared cameras to see through fogs. Fredembach and Susstrunk demonstrated in their recent work that the haze disappears in near-infrared capture of an outdoor scene as compared to an image captured by a conventional RGB image. The following figure illustrates this. This is because of a physical phenomenon called Rayleigh scattering. Small atmospheric particles present in the air scatter incident light with varying degree. Because of Rayleigh scattering, the component of light having the least wavelength gets scattered the most; and thus provides a bluish color to the sky. However, near-infrared is less scattered as compared to its visible counterparts and renders the sky darker. I plan to investigate this characteristics of near-infrared imaging in the context of car dashboard cameras. Such imaging techniques are very important in our current application and has potential in capturing sharper and clearer images of the road scene. A regular RGB image, together with a near-infrared capture of the same scene will provide the car driver better insights about the traffic and road signs.    

<img src="{{ site.baseurl }}/images/haze-img.jpg">
*On the left, a conventional RGB image. On the right, a near-IR capture of the same scene. The haze has disappeared, revealing a sharper, cleaner, picture.*   

<br />
It is an interesting problem to harness the large amount of videos obtained from car dashboard cameras, with varying spectral resolutions. I am interested to use the color-information of the regular traffic signs to provide a robust and state-of-the-art object detection system. Color-based image segmentation is an expertise that I gathered since my PhD studies. During my doctoral problem, we presented a supervised segmentation framework for ground-based sky/cloud images based on a systematic analysis of different color spaces and components. Unlike other state-of-the-art cloud segmentation methods, our proposed approach was entirely learning-based and does not require any manually defined parameters. We also released a large segmentation database of annotated sky/cloud images, to the research community. Currently, at ADAPT Centre, Trinity College Dublin, I am also working on a segmentation-based task in an industry-affiliated project. I am investigating deep-learning based techniques to identify advertisement billboards in street-view videos. My current project is providing me the relevant know-hows for object detection and localization, in the field of vision-assisted autonomous driving.    

<br />
Apart from image-based data, I am also interested to explore other sensor data for assisted driving. I plan to use Light Detection and Ranging (LIDAR) data and Global Positioning System (GPS) for the same purpose. Such a multi-modal approach can help the driver to take an informed decision during autonomous navigation. I plan to execute this project with the assistance from small- and medium-size enterprises. I established contact with ai Robotics, an Anuva Ventures start-up company incubated in Singapore.    

<br />
In the future, I am interested to extend my expertise in image processing and machine learning in multimodal neuroimaging. Several studies have been conducted to study the amount of grey matter volume in the cortical and sub-cortical regions of the brain. This helps the medical experts in understanding chronic schizophrenia. I am interested in devising image-segmentation algorithms on MRI images to automatically calculate the global grey- and white- matter volume in the brain. I performed early experiments in this field, and intend to work further in developing image-based solutions.    

<br />
Inspired by the practical problems faced in various area, my vision is to use my expertise of machine learning and image processing to solve similar problems in myriad fields: solar energy, assisted driving and neuroimaging. Apart from my ongoing research, I am interested to continue involving myself in a number of education and outreach activities. Furthermore, I am a firm believer of open science, and the spirit of reproducible research. Therefore, whenever possible, I will continue to publish my preprints, and release the associated codes and datasets amongst the community.    










## Teaching Statement

There goes an old aphorism “Learning is the progressive discovery of one’s ignorance”; and in this journey of discovery, researchers have developed several pedagogical techniques viz. active-, collaborative-, cooperative- and problem-based- learning. The existence of multitude of techniques brings out the subtle fact that the process of learning is not at all simplistic; and no single technique can fit the bill at all times. Therefore, in my teaching philosophy, I intend to provide a blend of such techniques, with a strong emphasis on: a) problem-based learning and b) technology-enabled learning.

<br />
*Learning by doing*. This statement concisely put forwards my teaching philosophy, and what I strive to achieve in my class. In teaching the fundamental concepts of signal processing and machine learning, I believe that it is necessary for the students to complement their theoretical knowledge with current state-of-the-art research and its applications. Engaging themselves in hands-on projects will foster creativity and team-building spirit amongst the peers. Such cooperative learning encourages the student to present concerted efforts while solving the problem statement. Using a combination of online and face-to-face sessions, collaborate and cooperative learning will flourish further. *Technology-enabled learning* will create greater learner engagement, and also make the assessment process more engaging and fascinating. I am interested for a seamless integration of technology in my teaching methods -- such learning aids will greatly help in disseminating my lessons, and collecting student feedback, both during- and after- the class. Whilst I appreciate the advantages of a technology-enabled learning experience, however, I will avoid an over-reliance on them. Technology should not attempt to replace the basic tenants of teaching -- I would continue fostering an interactive and open discussion amongst my students. 

<br />
My doctoral training at the School of Electrical and Electronic Engineering at Nanyang Technological University (NTU) Singapore, has provided me excellent opportunities to develop my teaching philosophy over these years. I have been a teaching assistant in the course EE2008: Data Structures and Algorithms during two complete semesters of AY 2014-15 and AY 2015-16 session. Based on the collective feedback of 120+ students, I was awarded the `Commendable Teaching Assistant Award'. Moreover, I also involved myself in peer-tutoring groups, where students with academic probation/warning can increase their grades and eventually graduate in the same graduating cohort. 

<br />
Based on such experiences as a lecturer in regular courses and peer-tutoring groups, I was interested to delve further into my teaching philosophy. The Teaching Perspectives Inventory (TPI) [Pratt and McKenna 2001] has developed a comprehensive questionnaire to do a profiling of the intended teachers. The result of this TPI questionnaire provides the intendant teacher an analysis on the following perspective viewpoints -- Transmission, Apprenticeship, Developmental, Nurturing, and Social Reform. I participated in the survey, my personalized test results can be accessed [here](http://www.teachingperspectives.com/tpi/tpisurveyresult.html?surveyid=240289). These results made me realize, that I have a differentiated teaching profile with dominant perspective in nurturing and apprenticeship. My score is highest on Nurturing, with a low in Transmission. This makes sense to me -- because I always intend to foster creativity and team-building spirit amongst the students, rather than only disseminating the subject matter knowledge in the class. I believe this TPI profile results broadly encompasses my teaching philosophy, as I put strong emphasis on overall development of the students and also try to provide my students a practical viewpoint of the studied course.

<img src="{{ site.baseurl }}/images/TPI-results.jpg">
*My TPI profile sheet results, based on Teaching Perspectives Inventory (TPI). It is evident that my NURTUR trait is dominant amongst other traits.*  

<br />
Aside from teaching in a formal setting, I have been involved in mentoring students in their Final Year Projects (FYPs) and Nanyang Research Program (NRP). I was also involved in teaching junior college and polytechnic students, as a part of our university outreach programs. It has been a rewarding and enriching experience so far. I enjoyed the interaction with my students, and I intend to continue such mentorship role in my prospective academic career. 
