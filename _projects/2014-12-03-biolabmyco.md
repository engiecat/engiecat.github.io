---
title: "BioLab-MYCO"
excerpt: "Automatic detection system for Tuberculosis Diagnosis"
permalink: /projects/biolabmyco
breadcrumb: true
share: true
classes: wide
read_time: false
header:
  teaser: /assets/images/20141212_biolabmyco_sensor.png
---

**Project BioLabMYCO - An Automatic Detection System for Tuberculosis Diagnosis (2014-2016)**  
Team W5, Microrobot Research, KAIST

## A Low Cost/Low Power Open Source Sensor System for Automated Tuberculosis Drug Susceptibility Testing (2014-2016) ##

![BioLab-MYCO presented in Intel Korea Year-End Press Conference 2014](/assets/images/20141212_biolabmyco.jpg)  
*BioLab-MYCO presented in Intel Korea Year-End Press Conference 2014*

In this project, an open source, low power sensor node was developed to check the growth of mycobacteria in a culture bottle with a nitrate reductase assay method for a drug susceptibility test. 

Current TB diagnosis is finalized with a culture test, which takes approximately 8 weeks. Conventionally this was done manually by pathologists, which caused high complexity, labor, and the probability of failure to workers. In contrast, this project aimed for minimal human interaction with the samples. 

Powered by Intel Galileo, the system automatically maintains the temperature of culture chamber and monitors the growth of microbes via image processing of the solid culture bottle (Ogawa Medium) and Optical Density measurement of the Middlebrook 7H9 OADC liquid medium. Liquid medium monitoring provides preliminary results in 4 weeks. The system can be monitored on-line via a web-based interface. Final diagnosis is done by Nitrate Reductase Assay, where the type of the grown colony (Nitrate consuming Mycobacterium) is confirmed.

![Nitrate Reductase Sensor](/assets/images/20141212_biolabmyco_sensor.png)
*Nitrate Reductase Assay module, with automatic reagent feeder and sensor*

The result had been awarded **Grand Prize in High-tech Medical Service(2,700$)** in World Embedded Software Contest 2014, featured in **2014 Intel Korea Year-End Press Conference**, and received domestic media coverage from [CNET Korea](https://www.cnet.co.kr/view/123762) and so on.

The work was published in Sensors as a journal article. 

K. Kim, **H. Kim**, H. Lim, H. Myung, "A Low Cost/Low Power Open Source Sensor System for Automated Tuberculosis Drug Susceptibility Testing." *Sensors* 16.6 (2016): 942. (Indexed for SCIE) [[Link]](http://www.mdpi.com/1424-8220/16/6/942)

## DAS:TB - Deep-Learning Based Automatic System for TB AFB Smear Test (Spring 2016) ##
*CD401 - Multidisciplinary Capstone Design I Team Project (Spring 2016, KAIST) [[Poster](/assets/2016-06-09-DAS_TB_Poster.pdf)]*

In Spring 2016, as a course project, we have developed a fully-automatic fluorescent microscope for TB AFB Sputum Smear Testing, in conjunction with [InSpace](http://www.inspace.re.kr/) Corp. The microscope featured auto-focus and motorized XY Stage.  

![Prototype Microscope ](/assets/images/20160721_CD401_microscope.jpg)  
*The prototype microscope*

The image acquired from the microscope was analyzed by via deep convolutional network(VGG-VD-16). Due to the small amount of diagnosed and certified data (approx. 350 positives), we have utilized various techniques, such as transfer learning, data augmentation and utilization of SVM instead of SoftMax layer. We have achieved 90.3% of accuracy (sensitivity: 92.1%, specificity: 87.6%), which is higher than previous literatures (TBDx: 84%, InSpace In-house: 73%)

As the team captain, I had proposed the idea, distributed work for each member and developed image processing part of the system. 


![Result shown by DAS:TB](/assets/images/20160721_CD401_MATLAB.jpg)  
*Result Shown by DAS:TB*