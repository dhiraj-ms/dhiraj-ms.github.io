---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
redirect_from:
  - /research
---

{% include base_path %}


Integration of Unmanned Aerial System and Machine Learning Approaches for Identifying Common ragweed in Soybean (MS Thesis)
------
Common ragweed (Ambrosia artemissifolia L.) is the major weed species in soybean in the United States which can substantially result in soybean yield loss. Integration of Unmanned Aerial Systems and Deep Learning technologies can help in the reduction of excess usage of herbicides by enhancing site-specific herbicide applications. One of the major challenges in training classification models is the non-availability of quality image data to train supervised models. It is also crucial that training data must be representative of all weather conditions, such as different daylights and precipitations for generalization. More than 100K images of ragweed and soybean at different growth stages were captured using DJI M-300 drone by me.
<br> <img style="float: left; padding: 10px 10px 10px 10px;" src="https://dhiraj-ms.github.io/images/research1.jpg" width=300>
<img style="float: left; padding: 10px 10px 10px 10px;" src="https://dhiraj-ms.github.io/images/research2.jpg" width=300>
I proposed a CNN architecture based on depthwise separable convolution that outperformed the state-of-art transfer learning Big Transfer (BiT) architecture. This model has the potential to be utilized for site-specific operations either with UAS-based low-volume spray applications or ground robots based mechanical control, leading to reduced herbicide usage, and ensuring sustainable crop production. My research won the **outstanding research award** at two conferences organized by United States Department of Agriculture and Southern Weed Science Society of America in 2022. [View Research Poster](https://auburnvirtual.auburn.edu/v/5VjYR5WYqob)
  
Neural Network-based High Throughput Field Phenotyping of Horticultural Crops using Hyperspectral UAV Imagery
------
Global population is expected to increase by 2 billion in the next 30 years, and global crop yields are on constant decline with decreasing availability of arable land. Developing smarter and non-destructive ways to accurately optimize crop yields is the need of the hour in the agriculture industry. This study presents high throughput field phenotyping of two horticultural crops namely tomato and melon. 
<br> <img style="float: left; padding: 10px 10px 10px 10px;" src="https://dhiraj-ms.github.io/images/research3.jpg" width=300>
<img style="float: left; padding: 10px 10px 10px 10px;" src="https://dhiraj-ms.github.io/images/research4.png" width=300>
With the ultimate goal of optimizing crop yield, these crops were monitored  for Chlorophyll-a (Chl-a) and Stem Water Potential (SWP) parameters. High volume and high throughput hyperspectral image data were collected using the Senop HSC-2 Hyperspectral camera on board a UAV flown over the crop fields. Chl-a and SWP were modelled regressively using the 50-band and 150-band hyperspectral reflectance as covariables and the in-situ measurements of Chl-a concentrations and SWP pressure as target variables. A small dataset of 18 samples for each crop was obtained after field-UAV image match-up. Traditional machine learning algorithms namely support vector machine, random forests, extreme gradient boosting and neural networks were used to model the characteristics and validated using leave-one-out cross validation technique. The analyses revealed that neural networks modelled Chl-a and SWP better than traditional machine learning algorithms, likely due to their representational capability even for smaller number of samples. Tomato Chl-a and SWP were modelled with an R-square of 0.90 and 0.94 respectively, and RMSE of 0.45 mg/m 3 and 0.03 bar respectively. Melon Chl-a and SWP were modelled with an R-square of 0.97 and 0.94 respectively, and RMSE of 0.86 mg/m 3 and 0.01 bar respectively. The high performance achieved in this study shows the potential of Neural Network-based High Throughput Field Phenotyping in continuous crop monitoring and aiding the everyday farmer in decision-making for yield optimization. [View Research Poster](http://dhiraj-ms.github.io/files/ps1.pdf).

Developing Deep Learning Algorithms for Remote Sensing of Turf Weeds using Visible Spectrum Imagery
------
Weed management in turfgrass is a serious issue in United States. Precision herbicide spraying applications to control weed in turfgrass cut the excessive use of herbicides thereby reducing herbicide wastage, costs, and human labor. Integration of remote sensing, deep learning, and Unmanned Ground Vehicle (UGV) can be an important tool for real-time weed detection to perform selective herbicide application in turfgrass. 
<br> <img style="float: left; padding: 10px 10px 10px 10px;" src="https://dhiraj-ms.github.io/images/research5.jpg" width=300>
<img style="float: left; padding: 10px 10px 10px 10px;" src="https://dhiraj-ms.github.io/images/research6.jfif" width=300>
In this research, I attempt a Proof of Concept(POC) implementation to investigate the feasibility of the use of deep learning in weed detection in turfgrass. This project involves developing deep learning-based segmentation and robust weed classification models, which would be deployed on a ground robot to recognize the locations of weeds. The ultimate goal is to automate the process of spot spraying by integrating the weed recognition deep learning model to revolutionize weed management in the turf. [View Research Poster](http://dhiraj-ms.github.io/files/poster2.pdf).

Assessment of Suitable Vegetation Indices Calculated from Remote and Proximal Sensing to Discriminate Irrigation Treatments ( Submitted for European Conference on Precision Agriculture 2022)
------
Water is becoming the most limiting factor for crop production, with irrigated agriculture being one of the main water-consuming sectors, which is a challenge for substantial water savings. In this context, the EU project DATI aimed to design and develop new Digital Agriculture (DA) technological solutions and procedures for crop and soil monitoring with the purpose of optimizing irrigation management by improving irrigation equipment at the farm scale and scheduling water release according to crop needs. Within the project, the field experiment was carried out at the Tenuta di Alberese farm (42 6935 º N, 11 1425 º W), Italy in 2021. Two crops,
melon and tomato, were monitored and three irrigation treatments were applied during the season: traditional (control-T1), 75% water reduction (T2) and 50% water reduction (T3). 
<br> <img style="float: left; padding: 10px 10px 10px 10px;" src="https://dhiraj-ms.github.io/images/experimental_design (1).jpg" width=300>
<img style="float: left; padding: 10px 10px 10px 10px;" src="https://dhiraj-ms.github.io/images/DJI_0140.JPG" width=300>
The aim of this work was to identify the most suitable vegetation index (VI) calculated from different remote and proximal sensing and ground soil measurements to discriminate irrigation treatments. Four field campaigns were carried out from June to August 2021. A Senop HSC 2 hyperspectral camera (50 bands), DJI Phantom Multispectral (5 bands) and Flir Fusion thermal camera (canopy temperature) were used for the flight measurements. Soil water content was collected using a
wireless sensor network. Several narrowband indices from hyperspectral imagery and broadband indices from multispectral were calculated. Firstly, an analysis of variance and post hoc Tukey tests showed significant differences between control and T2-T3 treatments in broadband multispectral indices for tomato (NDRE, GDVI) and in narrowband hyperspectral indices (SAVI, MTVI and EVI) for melon. Canopy temperature showed quite a high difference, although with a low significance value. Soil water content showed the highest difference among treatments. We also tested a second statistical approach to differentiate three treatment levels using classification deep neural networks. Permutation importance technique was used to explain the insights of the deep learning model’s behavior and it tells us which indices impact the
model’s predictions. Top hyperspectral indices for tomato crops were RENDI, TCARI and NDRE while for melon were NDRE, TCARI and RENDVI. Future work will examine ground
truth data such as yield, chlorophyll content and vegetative crop parameters and their behavior in different irrigation treatments.


Implementation of Deep Learning in Healthcare (Research Internship at University of Leicester, England)
------
<img style="float: left; padding: 10px 10px 10px 10px;" src="https://dhiraj-ms.github.io/images/research7.png" width=300>  

* Proposed a convolutional neural network (CNN) model with Bayesian Optimization to detect cerebral micro-bleeds in the cerebrum of brain achieving an accuracy: 98.97%, sensitivity: 99.66%, specificity: 98.14%, and precision: 98.54%. This model outperformed the state-of-the-art methods. Paper is here [Springer.](https://link.springer.com/article/10.1007/s00138-020-01087-0)

* Developed a small and low-latency Transfer Learning model on pre-trained MobileNet structure to build pathological brain detection system for mobile and embedded vision applications achieving an accuracy of 92%.

* Developed a CNN model to predict the age of human from samples of 3-D brain MRI images.

Identification of Italian Ryegrass in Wheat using Deep Learning
------
Italian ryegrass is the major weed species in wheat which can drastically reduce crop yield. Use of artificial intelligence-assisted robots and Unmanned Aerial Systems for weed identification and classification require digital database and modeling approach with high precision. One of the major challenges in training classification models is the lack of weed image database and difficulty in collecting sufficient number of images for this purpose. This problem can be solved by using Data Augmentation techniques.  
<br> <img style="float: left; padding: 10px 10px 10px 10px;" src="https://dhiraj-ms.github.io/images/research8.jfif" width=300>
<img style="float: left; padding: 10px 10px 10px 10px;" src="https://dhiraj-ms.github.io/images/research9.jfif" width=300>
I proposed research focused on CNN-based approach and tuned using Bayesian optimization. This proposed model is more efficient despite being the smallest one (7 layers) as  compared to use of pretrained network available for Transfer Learning such as ResNet-50 (50 layers). High performance of the model is attributed to the reasoning-based hyper-parameter search. Image augmentation also played a crucial role in giving high performing model. Italian ryegrass can be detected with an accuracy of 97%.

Unmanned Aerial System-Based Herbicide Spray Applications
------
Weeds are the major pests of agricultural crops and a major concern for sustainable crop production. The recent advances in small Unmanned Aerial Systems (UAS) technologies have opened new opportunities for agricultural systems. In the US, no documented information is available on the efficacy of UAS based broadcast and spot spray applications. 
<br> <img style="float: left; padding: 10px 10px 10px 10px;" src="https://dhiraj-ms.github.io/images/research10.jpeg" width=300>
<img style="float: left; padding: 10px 10px 10px 10px;" src="https://dhiraj-ms.github.io/images/research11.png" width=300>
<img style="float: left; padding: 10px 10px 10px 10px;" src="https://dhiraj-ms.github.io/images/image_6483441.jpg" width=300>

Therefore, it is important to standardize spray parameters (altitude, speed, volume, herbicide concentration etc.) and generate data to better understand the technology potential. Objective was to determine the minimum spray volume for UAS based herbicide applications and evaluate the efficacy of the UAS spray system using glufosinate in Liberty-Link® Soybean, Corn and Cotton. Achieved 90-100% control of weeds in both broadcast and spot spray.

Health Monitoring of Gear Box using Convolutional Neural Network (Undergraduate Thesis)
------
My undergraduate thesis was on conditional health monitoring of gearbox using convolutional neural network. Collected the samples of vibrational frequency signal of gearbox under 3 conditions chipped teeth, broken teeth, and worn teeth. Achieved the test accuracy of 87% from hybrid model (CNN+LSTM) architecture. 

Professional Experience
------
1. Built deep learning based Optical Character Recognition (OCR) system for Indian Government issued ID cards. Proposed model assisted the firm Augmenify to raise revenue of $30000 from clients.

1. Designed and built python based solution using NumPy and Pandas for web scraping the data of NBA, NFL and MLB tournaments.  Demonstrated data insights using data visualization techniques and received appreciation from client and EXL.

1. Proposed machine learning based methodologies to minimize the insurance industry loss due to fraud claims along with minimizing False Negatives to Australian-based insurance company as a part of the Machine Learning Hackathon. Novelty in research method got selected for the national final and obtained a full-time job offer as a Data Scientist.

1. Designed the computer vision model to solve case challenge Revolutionising Healthcare with AI and analytics for GE Healthcare analytics challenge 2020. My state of art method helped me to Qualify in Top-10 out of 92 teams for national finals.

1. Predicting the Productive Potential of a Natural Gas Resource using Machine Learning. Hackathon organised by Weatherford International plc. Implemented Principal Component Analysis and K-Means unsupervised machine learning algorithm to identify the potential regions of coal using data in the form of geophysical well logs obtained from boreholes.


