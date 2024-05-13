---
layout: single
title: Challenges
permalink: /challenges/
sidebar:
    nav: "sidebar"
---

This year, we are running the following challenges:
- [Shape Completion and Reconstruction of Sweet Peppers Challenge](#shape-completion-and-reconstruction-of-sweet-peppers-challenge)
- [Multi-object Tracking of Sweet Peppers Challenge](#multi-object-tracking-of-sweet-peppers-challenge)


During the workshop, we will announce the winners and plan to award a certificate for winning entries that provide a short description of their technical approach by submitting a [short technical report](http://localhost:4000/cfp/#challenge-technical-report).

[Feng Chen](mailto:feng.chen@ed.ac.uk) is the challenges lead. Please contact with questions and/or concerns. Please also contact the competition organisers with specific questions regarding the competition.


## Shape Completion and Reconstruction of Sweet Peppers Challenge

| **Challenge Organisers** |
| [Federico Magistri](http://www.ipb.uni-bonn.de/people/federico-magistri/index.html) | Photogrammetry and Robotics Lab, Center for Robotics, University of Bonn | [Email](mailto:federico.magistri@igg.uni-bonn.de) |
| [Jens Behley](http://jbehley.github.io) | Photogrammetry and Robotics Lab, Center for Robotics, University of Bonn | [Email](mailto:jens.behley@igg.uni-bonn.de) |

In this challenge, you are tasked to provide a complete 3D mesh given a partial RGB-D observation of sweet peppers. You are provided with RGB-D frames with corresponding instance masks and poses where sweet peppers are only partially visible. We ask the participants to predict a 3D mesh representing the complete fruit. Obtaining such information is a fundamental building block for agricultural autonomous systems across different downstream tasks, such as harvesting and yield estimation.

More details about this challenge can be found in our technical report <link>

For participating in this challenge we setup a CodaLab competition here <link>

Please contact [Federico Magistri](mailto:federico.magistri@uni-bonn.de) if you have questions about this competition and concerns regarding the submission on CodaLab.


## Multi-object Tracking of Sweet Peppers Challenge

| **Challenge Organisers** |
| [Chris McCool](http://agrobotics.uni-bonn.de/chris-mccool/index.html) | Institute of Agricultural Engineering, University of Bonn, Germany | [Email](mailto:cmccool@uni-bonn.de) |
| [Esra Güçlü](http://agrobotics.uni-bonn.de/esra-guclu/index.html) | Institute of Agricultural Engineering, University of Bonn, Germany | [Email](mailto:egueclue@uni-bonn.de) |

In this challenge, you need to make use of weakly labelled data to perform detection and tracking of small objects in a cluttered agricultural environment. With this information we can obtain the current state of the field (glasshouse) as well as the amount of harvestable crop, this is because it also includes a coarse estimate of the ripeness of the crop.  The weak labels that we provide are instance-based semantic segmentation masks along with an estimated unique ID for each instance in the short video sequences. Please contact [Esra Güçlü](mailto:egueclue@uni-bonn.de) if you have specific questions about this competition.
