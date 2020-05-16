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

I am no longer in the academic job market. However, this page provides details on several aspects of my application packet that I used in my academic applications.

<!---
<br />
Curriculum Vitae | [<a href="https://soumyabrata.github.io/files/CV.pdf">PDF</a>]
-->

## Research Statement

The current rapid developments in machine intelligence and computer vision
owe to three important factors – existence of massive data, open-source algorithms,
and higher computing power. I am interested in utilizing these recent developments
to solve specific computational problems in computer vision. My research interests are
primarily in the field of image processing, computer vision, machine learning, and deep
learning. Broadly speaking, I am interested in designing state-of-the-art algorithms and
systems, based on rigorous mathematical framework and systematic data analysis in
the following research areas:

+ Earth sciences and related observations,
+ Multimedia imaging- and video- data.


### Executive Summary

The central theme of my research vision is to identify the specific computational problems in the above areas; and solve them in a collaborative manner with the domain
experts. I am a firm believer of open science and research reproducibility – and thereby
interested in advancing science by promoting mutual collaboration and collective efforts
among the community.



### Computer Vision in Remote Sensing

The future of solving energy crisis lies at the successful integration of solar and renewable energy into the conventional power grid. With the rapid development in photogrammetric techniques and low-cost imaging and weather-station data, it is now
increasingly easier to collect massive image and other meteorological sensor data of the
earth’s atmosphere from the ground. The key to many unsolved problems in atmospheric studies lies in systematically analyzing these massive data, and fusing these
diverse data types to develop new algorithms and techniques. My research plan in this
particular field of atmospheric studies lies at the intersection of remote sensing and
computer vision. In particular, I am interested to visualize in what ways state-of-the-
art techniques inspired from computer vision and machine learning communities help
us in analyzing solar energy falling at earth’s surface.

<br />
My interest in this field of earth observations and solar energy stems from my
previous doctoral experience at Nanyang Technological University Singapore. My previous work involved the study and analysis of clouds in tropical regions, like Singapore,
and to understand the impact of clouds in the signal attenuation of satellite communication links. We used ground-based sky cameras that continuously captures the images
of the earth’s atmosphere at regular intervals of time. These images were useful in
generating a highly localized cloud profile, and understanding the various atmospheric
events. We designed our custom-built sky cameras [1], equipped with wide-angle fish
eye lens, and installed them in our university building for continuous cloud monitoring.
We have developed state-of-the-art algorithms that can efficiently compute the cloud
coverage, recognize and classify the cloud types, and accurately estimate the cloud base
height using a stereo setup of sky cameras.

<img src="{{ site.baseurl }}/images/wsi-image.jpg">
*We designed low-cost, ground-based sky cameras for continuous cloud profil-
ing. The region around the sun (popularly known as circumsolar region) is highlighted
with a white rectangle, and has the largest impact on the harnessed solar energy.* 

<br />
Currently, solar energy is the one of the most reliable sources of renewable
energy. However, it suffers from two major drawbacks – variability and uncertainty. It
is a well-known fact that clouds have a huge impact on this intermittency of Photovoltaic
(PV) energy generation. The passage of clouds over the solar panels can incur variable
fluctuations in the received solar irradiance on the earth’s surface. I am interested
to analyze how clouds can have an impact on the total solar irradiance falling on the
earth’s surface. This is an interesting problem at hand: how the intermittency and rapid
fluctuations in solar radiation be best captured by ground-based imaging devices? This
can be intuitively explained by the fact that a drop in total solar irradiance leads to a
decreased imaging luminance by the camera sensor, and vice versa. With the massive
amount of imaging data collected by such cameras, it will provide us a good user study
to apply machine-learning techniques on such imaging data. I plan to use deep-learning
based neural networks to parametrize the camera response curve of the imaging sensors. I am interested in modeling the received solar irradiance from the luminance of the sky
camera. Additionally, I also plan to further miniaturize the sky cameras, so that it
can be deployed at multiple locations across the region of interest. This will help us in
mapping the entire solar irradiance map over the considered region.

<br />
In summary, such problems in remote sensing merit a more rigorous and thorough analysis in a multitude of applications, and I intend to bridge that gap. I am
interested to study such remote-sensing problems from the perspective of computer vision and machine learning communities. This project can be collaboratively executed
alongside international institutions and research groups. I have already developed initial contacts with leading solar energy groups: [Copernicus Institute of Sustainable
Development, Utrecht University, The Netherlands](https://www.uu.nl/en/research/copernicus-institute-of-sustainable-development), [Center for Energy Research, UC
San Diego](https://cer.ucsd.edu) and [Solar Energy Research Institute of Singapore (SERIS)](http://www.seris.nus.edu.sg).

 

### Computer Vision in Smart Traffic Analytics

With the advancement in deep-learning techniques in image and video analysis, we have
seen a massive interest in the field of autonomous driving from the leading companies
in artificial intelligence. There are a plethora of interesting problems in vision-based,
computer-assisted self driving. However, I am interested to solve a specific problem in
this area: to provide an end-to-end system in detecting the traffic- and road- signs from
low-resolution car dashboard cameras. This problem becomes more challenging with
poor lighting conditions during fog and misty weather conditions. 

<br />
My previous doctoral experience also dealt with using near-infrared cameras
to see through fogs. Fredembach and Süsstrunk demonstrated in their recent work [2]
that the haze disappears in near-infrared capture of an outdoor scene as compared to
an image captured by a conventional RGB image. I plan to investigate this characteristics of near-infrared imaging in the context of car dashboard cameras. Such imaging
techniques are very important in our current application and has potential in capturing
sharper and clearer images of the road scene. A regular RGB image, together with
a near-infrared capture of the same scene will provide the car driver better insights
about the traffic and road signs. I am interested in exploring the possibility
of a multi-modal approach with Near-Infra-Red (NIR) and Global Positioning System
(GPS), in addition to regular RGB camera images.  

<img src="{{ site.baseurl }}/images/traffic.png">
*Automatic detection of traffic- light and signage using a multitude of sensor
data.*   

<br />
It is an interesting problem to harness the large amount of videos obtained
from car dashboard cameras, with varying spectral resolutions. I am interested to use
the color-information of the regular traffic signs to provide a robust and state-of-the-art
object detection system. Color-based image segmentation is an expertise that I gathered since my PhD studies. During my doctoral problem, we presented a supervised segmentation framework based on a systematic analysis of different color spaces and
components [3]. Unlike other state-of-the-art color segmentation methods, our proposed
approach was entirely learning-based and does not require any manually defined parameters. We also released a large segmentation database of annotated sky/cloud images,
to the research community. Currently, at the ADAPT Centre, I am also working on a
object-instance segmentation task in collaboration with Huawei Ireland Research Centre. I am developing deep-learning based techniques to identify advertisement billboards
in street-view videos. We are designing an advertisement detection- and integration-
system for multimedia videos, that is useful for next-generation online publicity [4].
We have developed ADNet, a deep convolutional network that automatically detect the
presence of a street billboard in a video frame [5]. Furthermore, we also developed a
deep-learning based method to localize the position of the advertisement in the video
frame. Our project produced an [impressive advertisement creation system](https://youtu.be/zaKpJZhBVL4), and also
received extensive [media coverage](https://www.tcd.ie/news_events/articles/adapt-scoops-technology-ireland-award-for-disruptive-advertising-system/) for the work. I believe my current project is providing me the relevant know-hows for object detection and localization, in the field of
vision-assisted autonomous driving.

<br />
Apart from image-based data, I am also interested to explore other sensor
data for assisted driving. I plan to use Light Detection and Ranging (LIDAR) data
and GPS [6] for the same purpose. Such a multi-modal approach can help the driver to
take an informed decision during autonomous navigation. I plan to execute this project
with the assistance from small- and medium-size enterprises. I established contact with [ai Robotics](http://anuva-ventures.com/projects), an Anuva Ventures start-up company incubated in Singapore.

 

### Closing Note

Inspired by the practical problems faced in various area, my vision is to use my expertise of machine learning and image processing to solve similar problems in myriad
fields: solar analytics, and smart traffic analytics. Alongside my research, I am interested to continue involving myself in a number of education and outreach activities.
Furthermore, I am a firm believer of open science, and the spirit of reproducible research [7]. Therefore, whenever possible, I continue to publish my preprints, and release
the associated codes and datasets amongst the community.


#### References

[1] S. Dev, F. M. Savoy, Y. H. Lee and S. Winkler, DIY Sky Imager For Weather Observation, IEEE
Signal Processing Society, 2016
<br />
[2] C. Fredembach and S. Süsstrunk, Colouring the near-infrared, Proc. Color and Imaging Confer-
ence, 2008.
<br />
[3] S. Dev, Y. H. Lee, S. Winkler, Color-based segmentation of sky/cloud images from ground-based
cameras, IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing,
vol. PP, no. 99, pp. 1-12, 2016.
<br />
[4] A. Nautiyal\*, K. McCabe\*, M. Hossari\*, S. Dev\*, M. Nicholson, C. Conran, D. McKibben, J.
Tang, W. Xu, and F. Pitié, An Advert Creation System for Next-Gen Publicity, Proc. European Conference on Machine Learning and Principles and Practice of Knowledge Discovery in
Databases (ECML-PKDD), 2018 (\* Authors contributed equally and arranged alphabetically).
<br />
[5] M. Hossari\*, S. Dev\*, M. Nicholson, K. McCabe, A. Nautiyal, C. Conran, J. Tang, W. Xu, and F.
Pitié, ADNet: A Deep Network for Detecting Adverts, Proc. 26th Irish Conference on Artificial
Intelligence and Cognitive Science (AICS), 2018 (\* Authors contributed equally and arranged
alphabetically).
<br />
[6] S. Manandhar, Y. H. Lee, Y. S. Meng, F. Yuan and S. Dev, A Potential Low Cost Remote Sensing
Using GPS Derived PWV, Proc. IEEE International Geoscience and Remote Sensing Symposium
(IGARSS), 2018.
<br />
[7] P. Vandewalle, J. Kovacevic, M. Vetterli, Reproducible Research in Signal Processing - What,
why, and how, IEEE Signal Processing Magazine, vol. 26, no. 3, pp. 37–47, 2009.







## Teaching Statement

There goes an old aphorism “Learning is the progressive discovery of one’s ignorance”; and in this journey of discovery, researchers have developed several pedagogical techniques viz. active-, collaborative-, cooperative- and problem-based- learning.
The existence of multitude of techniques brings out the subtle fact that the process of
learning is not at all simplistic; and no single technique can fit the bill at all times.
Therefore, in my teaching philosophy, I intend to provide a blend of such techniques,
with a strong emphasis on: a) problem-based learning and b) technology-enabled learning.

<br />
*Learning by doing*. This statement concisely put forwards my teaching philosophy, and what I strive to achieve in my class. In teaching the fundamental concepts of
signal processing and machine learning, I believe that it is necessary for the students to
complement their theoretical knowledge with current state-of-the-art research and its
applications. Engaging themselves in hands-on projects will foster creativity and team-building spirit amongst the peers. Such cooperative learning encourages the student
to present concerted efforts while solving the problem statement. Using a combination
of online and face-to-face sessions, collaborate and cooperative learning will flourish
further.

<br />
*Technology-enabled learning* will create greater learner engagement, and also
make the assessment process more engaging and fascinating. I am interested for a seamless integration of technology in my teaching methods – such learning aids will greatly
help in disseminating my lessons, and collecting student feedback, both during- and
after- the class. Whilst I appreciate the advantages of a technology-enabled learning
experience, however, I will avoid an over-reliance on them. Technology should not attempt to replace the basic tenants of teaching – I would continue fostering an interactive
and open discussion amongst my students.

<br />
My first experiences in teaching were during my doctoral training at the School
of Electrical and Electronic Engineering at Nanyang Technological University (NTU)
Singapore. This training provided me excellent opportunities to develop my teaching
philosophy over these years. I have been a teaching assistant in the course EE2008:
Data Structures and Algorithms during two complete semesters of AY 2014-15 and AY
2015-16 session. Based on the collective feedback of 120+ students, I was awarded
the ‘Commendable Teaching Assistant Award’. Moreover, I also involved myself in
peer-tutoring groups, where students with academic probation/warning can increase
their grades and eventually graduate in the same graduating cohort. These valuable
teaching experiences are greatly helping me in my current role as Associate Faculty at the School of Computing, National College of Ireland. In my current assignment, I am
teaching graduate courses in data analytics to postgraduate students. I am following
my philosophies – learning by doing and technology-enabled learning, and is providing
excellent results. The students are self-motivated, and are eager to learn about the
subject matter via the team research projects and classroom interaction. Collaborate
and cooperative learning approach stresses on the team building attitude of students
on top of problem solving skills. This provides the students a holistic understanding of
the entire subject matter.

<br />
Based on such experiences as a lecturer in regular courses and peer-tutoring groups, I was interested to delve further into my teaching philosophy. The Teaching Perspectives Inventory (TPI) [Pratt and McKenna 2001] has developed a comprehensive questionnaire to do a profiling of the intended teachers. The result of this TPI questionnaire provides the intendant teacher an analysis on the following perspective viewpoints -- Transmission, Apprenticeship, Developmental, Nurturing, and Social Reform. I participated in the survey, my personalized test results can be accessed [here](http://www.teachingperspectives.com/tpi/tpisurveyresult.html?surveyid=240289). These results made me realize, that I have a differentiated teaching profile with dominant perspective in nurturing and apprenticeship. My score is highest on Nurturing, with a low in Transmission. This makes sense to me -- because I always intend to foster creativity and team-building spirit amongst the students, rather than only disseminating the subject matter knowledge in the class. I believe this TPI profile results broadly encompasses my teaching philosophy, as I put strong emphasis on overall development of the students and also try to provide my students a practical viewpoint of the studied course.

<img src="{{ site.baseurl }}/images/TPI-results.jpg">
*My TPI profile sheet results, based on Teaching Perspectives Inventory (TPI). It is evident that my NURTUR trait is dominant amongst other traits.*  

<br />
Aside from teaching in a formal setting, I have been involved in mentoring
students in their Master of Science (MSc) research thesis, Final Year Projects (FYPs)
and Nanyang Research Program (NRP) projects. I was also involved in teaching junior
college and polytechnic students, as a part of our university outreach programs. It has
been a rewarding and enriching experience so far. I enjoyed the interaction with my
students, and I intend to continue such mentorship role in my prospective academic
career.


## Diversity Statement

Growing up overseas in the remote town of [Nagaon](https://en.wikipedia.org/wiki/Nagaon), in the province of Assam
situated on the north-eastern part of India, I was exposed to varied culture and tradition
from a very early age. My parents migrated to my home province about four decades
back because of their respective jobs. Consequently, I was born and raised in a different
culture and upbringing at a very early stage, as compared to my parents’ culture and
traditions. However, I was extremely privileged to be born in a family where my parents
and family members defied all odds, and were successful in providing the best education
to me and my other siblings.

<br />
In this intended application of mine, I would like to humbly point a few pointers that greatly helped me in embracing diversity and a positive inclusionary environment in my current self. I completed all my high-school education from my home
province. In 2006, I got admitted to a national institute of technology, for my engineering studies. This period was undoubtedly the first time, when I started lifelong
friendship with students, who came from the diverse cultural backgrounds of India.
It was an amazing experience, as I learnt to forge friendship with people from various backgrounds. Post my graduation in 2010, I joined a Swedish telecommunication
company as a network engineer and worked with them for 2 years. It was also an enriching experience for me, as I got a chance to interact with employees of different age
groups, designations, nationality etc. I understood first-hand that embracing diversity
and inclusiveness in the workplace positively impacts the overall well-being of the team.

<br />
My doctoral training at Nanyang Technological University (NTU) Singapore
since 2012, further assisted me in improving my emotional quotient. I got exposed to
education curriculum of international standards, and received opportunities to develop
friendship with friends and colleagues from diverse nationalities. Singapore prides itself
to possess one of the diverse workforce in the international community, and I was
fortunate to experience it first hand. My doctoral training at NTU also gave me the
initial opportunities in teaching diverse students. As a teaching assistant in the subject
Data Structures and Algorithms, I got exposed to a variety of students in my class.
Particularly, I was interested in helping the academically weak students who struggled
to maintain a good semester grades. Therefore, I enrolled myself as a peer tutor after
my office hours, to assist them in better understanding the fundamental concepts of
this subject. It was an opportunity for me to identify with the challenges faced by the
students, and I was delighted to see their improvements over the months. An email
excerpt from one of such students – she said, “Hi Soumya, I would like to thank you
for your guidance on DSA. I thought that I would failed badly for it but with your help I gotten B+. Thank you so much. Best regards, LY”. This frankly summarizes my
amazement after getting to know their outcomes.

<br />
Similar diverse cultural experiences were learnt during my research attachment at École polytechnique fédérale de Lausanne, Switzerland. These experiences
garnered over these years are greatly assisting me in my current job at Dublin, Ireland.
I have understood that diversity should be celebrated, and a diverse workforce is always
necessary for a balanced viewpoint. This philosophy stands true for both prospective
academicians and prospective students.

<br />
I am inclined to believe that, if opportunities are bestowed upon the right students, irrespective of the geographic boundaries, we can assist many in their educational
goals. Based on this philosophy, I am involved as an advisor at Xonkolpo: Higher-Ed
Initiative. [Xonkolpo](https://www.facebook.com/xonkolpo.org/) is a non-profit initiative floated by a community of enthusiasts
from Assam, India whose goal is to build a world-class support system for students of
North-Eastern India in any Science, Technology, Engineering and Management (STEM)
field.

<br />
These experiences further strengthen my commitment in promoting diversity
at my workplace, and I intent to look forward to a diverse community.
