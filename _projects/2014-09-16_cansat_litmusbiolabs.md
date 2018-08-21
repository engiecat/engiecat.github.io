---
title: "Litmus BioLabs"
excerpt: "Automatic detection system for microbes"
permalink: /projects/litmusbiolabs
breadcrumb: true
share: true
classes: wide
read_time: false
header:
  image: /assets/images/20140809_at_narospacecenter.jpg
  teaser: /assets/images/litmus_biolabs.png
---

**Project Litmus BioLabs - an Automatic detection system for microbes (2014)**
Team W5, Microrobot Research, KAIST

### Flying BioLab - Automatic detection system for microbes in biohazardous area (2014) ###

First formed to compete in Korea CanSat Competition, Team W5 consisted of students with various backgrounds, from Bioengineering to Aerospace engineering. Based on such diversity, we decided to build a CanSat that can measure biological contaminants (microbes) on-site in the bio-hazardous environment (e.g. Anthrax-contaminated area). The contamination is measured on-site, by culturing microbes and monitoring the medium’s optical density. 

Additionally, we successfully designed and built a 3D-printed platform for CanSats([Link](https://www.thingiverse.com/thing:425904)), that features standardized power-signal ports, fully-functional AHRS, and configurable mission modules. This also featured web-server based ground station, with responsive web design.

![Web-server based CanSat Ground Station](/assets/images/20140809_cansat_gs.jpg)

The CanSat was rewarded 2nd prize (President of KAIST), and the result had been presented in 2014 KSAS(Korean Society for Aeronautical and Space Sciences) Fall Conference as an oral presentation.

K. Kim, **H. Kim**, H. Roh, H. Choi, “Flying BioLab : A CanSat platform for sampling and monitoring air bacteria in bio-hazardous area”, in *2014 KSAS(Korea Society for Aeronautical & Space Sciences) Fall Conference*, Organized Session, pp. 86. [[Link]](http://www.riss.kr/link?id=A100498461)


### Litmus BioLabs - a Sensor Node for Remote Monitoring of Waterborne Disease-Causing Bacteria (2014 - 2016) ###

Based on the results we have gathered during the CanSat competition, we decided to apply our technology to the field of aquaponics (Plant Factory). In such an environment, where usage of antimicrobials is very limited, waterborne microbes, such as E. coli, pose a severe threat. While manual sampling had been used in small-scale, the number of diagnosis samples may be large and handling daily portions is likely to be labor intensive in large-scale factory settings.

![Litmus BioLabs - a prototype with automatic sampling system removed for clarity.](/assets/images/2018_08_24_SDSLitmus.jpg)

The prototype with automatic sampling system removed (Normally the samples are loaded via pumps)

A chromogenic enzyme substrate assay method was used to easily detect coliform bacteria by monitoring the color change of the sampled water mixed with a reagent. Live webcam image streaming to the web browser of the end user with a Wi-Fi connected sensor node shows the water color changes in real time. Such changes are detected automatically and reported to the user, while the webcam feed can be directly observed. Additionally, Optical Density was measured for liquid medium. Image streaming and web console servers run on Raspberry Pi.

The data could be monitored remotely via the web-based monitoring system.

The result was awarded **Grand Prize (President of Samsung SDS)** in the 2014 Samsung SDS S/W Club Championship. 

The derivative work which focused on the detection system had been published in Sensors journal. ([Details](/experiences/labonachip))

