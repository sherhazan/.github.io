---
title: "Learning-Based 3D Vision Sensor for Robotic Peg-In-Hole Insertion of Deformable Objects"
collection: publications
type: "Paper"
permalink: /publication/2026-3D-Vision-Sensor
redirect_to: "https://sherhazan.github.io/Deformable-Vision-Sensor/"
excerpt: 'This paper is in preparation for submission.'
date: 2026-01-01
citation: 'S. Hazan, E. Cohen, R. Schneor, A. Fischer and M. Zacksenhouse, "Learning-Based 3D Vision Sensor for Robotic Peg-In-Hole Insertion of Deformable Objects", Under Review, 2026.'
---

![2026-3D-Vision-Sensor](/images/Paper_3D_Vision_Sensor.png) 

## Abstract

The integration of precise object positioning systems in robotic assembly tasks, particularly Peg-in-Hole (PIH) operations, is crucial for enhancing automation efficiency in industrial environments. The challenge intensifies when dealing with deformable objects due to the additional geometry and location uncertainties of the objects. Advanced sensors and learning methods are recruited to face such challenges. This research presents a robust learning-based 3D vision sensor which is designed for estimating the relative position between both rigid and deformable objects in real-time. It is planned to be embedded into a robotic PIH insertion pipeline in the industrial
environment. Our 3D vision sensor incorporates capturing the 3D scene, predicting a probability vector indicating the relative position between the peg and hole. It uses a late fusion convolutional neural network (CNN) architecture for classification, extracting the continuous relative position from the probabilities vector. The estimated relative position is then utilized to extract a virtual friction force, which is fused with the F/T sensor measurements in the admittance control to improve the peg’s positioning during the insertion process. The efficiency of the 3D vision sensor was evaluated across various PIH tasks involving both rigid and deformable objects. Moreover, it was embedded into an industrial robotic cell without additional training in order to validate its robustness and generalization capabilities. The approach demonstrated high success rate, highlighting its effectiveness and applicability in real-world industrial settings.