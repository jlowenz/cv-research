---
layout: cv
title: Jason Owens' CV
---

# Jason L. Owens

Computer scientist, software engineer, father.

<div id="webaddress">
<a href="jlowens@gmail.com">jlowens@gmail.com</a>
| <a href="https://www.linkedin.com/in/jlowenz/">LinkedIn</a>
| <a href="http://github.com/jlowenz">GitHub</a>
</div>

## Currently

I enjoy working on hard problems. For the last ~19 years: getting autonomous systems to see and understand the physical world. I'm currently a Staff Technical Lead at Aurora; previously Uber ATG and 16 years as a Computer Scientist at the US Army Research Laboratory. PhD in Computer Science (Penn), focused on perception for robotic spatial understanding.

### Research interests

- programming environment design
- knowledge representation and reasoning
- humane interfaces
- world models for intelligent agent behavior
- continuous open-set learning for physical agent perception

## Research

### CCDC Army Research Laboratory

Aberdeen, MD  
[https://arl.devcom.army.mil/](https://arl.devcom.army.mil/)

`2007-2019`

**Computer Scientist, Autonomous Systems Division, VTD**

Sep 2007 - Aug 2019

**Agent World Model**

Modern autonomous robots are a large collection of complex algorithms working together to solve a common goal. Collecting and interpreting uncertain spatial, temporal, and semantic knowledge into a single central repository can help these algorithms operate more efficiently and, in addition, allow for more advanced reasoning (e.g., reasoning over time). We developed an agent world model that provides a central repository of knowledge based on limited modal logic and an integrative symbolic and sub-symbolic data store.

**Adaptive perception processes for learning from experience**

The APPLE project investigated continuous object learning systems; since it is not possible to train a robot for all future situations, instead it must be able to *learn from experience*. We hypothesized that a robot must support six conceptual components in order to be able to continuously learn about objects; these include ego-motion estimation, segmentation, flexible object representation, instance and category recognition, novelty detection, and generalization. We worked towards a benchmark and framework for evaluating continuous object learning systems, as well as proposed a set of baseline component implementations.

**Multi-sensor graph calibration**

Our multi-sensor graph calibration framework solved a real problem for robots: they have a wide variety of sensors mounted in multiple locations that must be fused into a single coordinate frame to most effectively use the information. Our framework utilized a novel background subtraction algorithm, geometry-based alignment features, and graph optimization to generate global relative sensor poses for an arbitrary number of sensors over three different sensor modalities on a robot.

**Temporally consistent segmentation**

One of the first steps in scene understanding using vision is to group pixels into larger chunks for more efficient reasoning. We performed this process of over-segmentation in 3-D and modified an existing voxel clustering algorithm to support consistent segmentations over time given effective ego-motion estimates and clouds of the environment. Temporal consistency enables incremental segmentation of an environment during exploration.

**RGB-D Egomotion and Mapping**

Robots need to know where they are, and one approach to this task is to estimate local motion using vision sensors and simultaneously construct a map of the environment for localization. We developed both sparse and dense implementations for ego-motion estimation, used surface elements for mapping, and GPU acceleration to produce high-resolution maps of the environment and provide accurate local motion estimation using RGB-D sensors.

**Autonomous search and exploration**

**Robot platform development**

`2003-2007`

**Computer Scientist, Software Development Branch, SLAD**

Jun 2003 - Aug 2007

**Joint Blast Analysis Methodology Tool**

Designed and built a modular graphical tool for blast analysis experimentation.

**B-Rep Ray Tracing**

Researched and developed the initial boundary representation module for NURBs primitive rendering in BRL-CAD.

**Exposed Objects Framework**

Researched, designed, and built a GUI application framework using humane human-computer interaction principles. Implemented and integrated MUVES 3 object store with Hibernate as an object-relational mapper.

**RVis (Results Visualizer)**

Designed and developed a prototype 3D vulnerability results viewer for efficiently displaying and querying analysis results. Received enthusiastic feedback during prototype demonstrations.

## Education

`2009-2019`

**[Ph.D. in Computer and Information Science](http://www.upenn.edu/cis)**

University of Pennsylvania -- Philadelphia, PA, USA  
*Concurrent with employment at Army Research Lab*

_Jan 2009 - May 2019_

[https://www.upenn.edu](https://www.upenn.edu)

- Advisor: Prof. Kostas Daniilidis
- Defended: December 21, 2018
- Dissertation: Visual Perception for Robotic Spatial Understanding

`2005-2008`

**[Master of Science in Computer Science](http://www.cs.jhu.edu)**

Johns Hopkins University  
Baltimore, MD, USA  
[https://www.jhu.edu](https://www.jhu.edu)  
*Concurrent with employment at Army Research Lab*  
_Jan 2005-May 2008_

Cumulative GPA: 4.00 / 4.00

`1995-2000`

**[Bachelor of Music in Clarinet Performance](http://www.peabody.jhu.edu)**

Peabody Institute of the Johns Hopkins University  
Baltimore, MD, USA  
_Sep 1995-May 2000_

[https://peabody.jhu.edu](https://peabody.jhu.edu)  

- Co-principal clarinetist of the Peabody Symphony Orchestra

`1995-2000`

**[Bachelor of Science in Computer Science](http://www.cs.jhu.edu)**

Johns Hopkins University  
Baltimore, MD, USA  
Sep 1995-May 2000

[https://www.jhu.edu](https://www.jhu.edu)  

- Beneficial-Hodson Scholar (all 5 years)
- Consistently recognized on the Dean's List
- Graduated with General Honors
- Graduated with Departmental Honors
- Outstanding Double Major Award from Dept. of Comp. Sci.
- Cumulative GPA: 3.68 / 4.00

## Employment

`2021-Present`

__Aurora__

*Staff Technical Lead, Perception Capabilities*  
**Jan 2021 - Present**, Pittsburgh, PA  
Tech lead for multiple perception capabilities across the full stack — from ML model design through onboard and offboard system architecture to data, processing, and evaluation infrastructure.

- Lead cross-functional teams through capability releases
- Craft label and evaluation policy
- Direct development of multiple new capabilities from inception to production deployment
- Mentor engineers toward expanded technical ownership and scope

`2019-2021`

**Uber ATG**

*Senior Software Engineer, Perception*  
**Sep 2019 - Jan 2021** ATG/Aurora merged, Pittsburgh, PA  
Owned a core perception capability; responsible for the ML model, training, data infrastructure, and label quality. 

- Improved classification performance through large-scale label investigation and visualization
- Transitioned onboard architecture to new in-process components

`2003-2019`

__CCDC Army Research Laboratory__

*Computer Scientist*  
**June 2003 -- Aug 2019**, Aberdeen, MD  
See the research section.

`2001-2003`

__Portablehole.net__

*Owner and lead developer*  
**Oct 2001 -- Jan 2003**, West Covina, CA

- Enterprise-wide Intranet-based master calendar for The Hathaway-Sycamores
- Internet-based iconic bookmark management for a private client.

`2001-2002`

**Northrop Grumman**

*Software Engineer*  
**Aug 2001 -- May 2002**, Woodland Hills, CA

- Performance evaluation and testing for low-level PowerPC assembly exception handlers and real-time Ada operating system code to measure performance improvement over previous R3000 processor implementations.
- Ported legacy embedded system equipment test scripts from OS/2 REXX to Perl 5 for improved performance and software maintainability.

`2000-2001`

**Tallàn Inc.**

*Consultant, Software Developer*  
**Jun 2000 -- May 2001**

- Various web and internal Java Swing applications for Ingram Micro


## Publications

### Conferences

`2019`

Osteen, P. R., J. L. Owens, and B. Kaukeinen. 2019. "Reducing the Cost of Visual DL Datasets." SPIE Defense+ commercial sensing. (Baltimore, MD). [https://doi.org/10.1117/12.2519114](https://doi.org/10.1117/12.2519114)

`2018`

Osteen, P. R., J. L. Owens, R. St. Amant, C. Robison, B. Kaukeinen, and M. DiBlasi. 2018. "Enabling Intelligence with Temporal World Models." *Unmanned Systems Technology XX* 10640 (May).

`2017`

Owens, J., and P. Osteen. 2017. "APPLE: Adaptive Perception Processes for Learning from Experience." Paper presented at CVPR. *Continuous and Open-Set Learning Workshop (CVPR)* (Hawaii, USA), July.

`2015`

Owens, J. L., P. R. Osteen, and K. Daniilidis. 2015. "MSG-Cal: Multi-Sensor Graph-Based Calibration." *IEEE/RSJ International Conference on Intelligent Robots and Systems*.

`2014`

Owens, J. L., P. R. Osteen, and K. Daniilidis. 2014. "Temporally Consistent Segmentation of Point Clouds." *SPIE Defense+ Security*.

Tron, R., P. Osteen, J. Owens, and K. Daniilidis. 2014. "Pose Optimization for the Registration of Multiple Heterogeneous Views." *Multi-View Geometry in Robotics at Robotics, Science, and Systems.*

`2012`

Osteen, P. R., J. L. Owens, and C. C. Kessens. 2012. "Online Egomotion Estimation of RGB-D Sensors Using Spherical Harmonics." *Robotics and Automation (ICRA), 2012 IEEE International Conference on*, 1679--84.

Owens, J., P. Osteen, and M. Fields. 2012. "Autonomous Exploration and Mapping of Unknown Environments." *SPIE Defense, Security, and Sensing* 838717--17.

`2010`

Owens, J., and M. Fields. 2010. "Incremental Region Segmentation for Hybrid Map Generation." *Army Science Conference*, 281--86.

### Reports

`2017`

Owens, J., and P. Osteen. 2017. *Ego-Motion and Tracking for Continuous Object Learning: A Brief Survey.* Technical Report ARL-TR-8167. US Army Research Laboratory.

`2012`

Owens, J. 2012. *Object Detection Using the Kinect*. DTIC Document.

`2008`

Haas, G., J. Owens, and J. Spangler. 2008. *A Platform for Developing Autonomy Technologies for Small Military Robots*. DTIC Document.

`2004`

Owens, J. L., and L. A. Butler. 2004. *RVis: The RIVA/MUVES Prototype Visualization Tool*. DTIC Document.

### Dissertation

`2019`

J. L. Owens. 2019. _[Visual Perception For Robotic Spatial Understanding](https://repository.upenn.edu/handle/20.500.14332/30245)._ Advisor K. Daniilidis. Doctor of Philosophy, Computer and Information Science, University of Pennsylvania.  

### Patents

`2026`

Djuric, N., Lewitt, T., Owens, J. 2026. "Traffic Signal State Detection." Patent application \#20260175870
