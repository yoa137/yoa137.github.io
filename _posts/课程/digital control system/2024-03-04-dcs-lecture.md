---
layout:     post
title:      "dcs-lab1"
subtitle:   "Design of reference signals discrete generators"
date:       2024-3-4
author:     "Zheng"
header-img: "img/post-bg-js-module.jpg"
catalog: true
tags:
    - master lecture
    - dcs
---

DCS 
--------------------------------------------------------------

### 基础知识

###### DCS design stages

1.  Information on the processes and the signals can be provided by

   - direct measurable inputs, outputs, state variables, 

   - process models and signal models, 

   - state estimates of processes and signals.

2.  Control system structure has to be designed in the form of

   - single input/single output (SISO) control systems; 

   - interconnected control systems; 

   - multi input/multi output (MIMO) control systems; 

   - decentralized control systems.

3.  Feedforward and feedback control algorithms are to be designed and adjusted using

   - simple tuning rules for the parameters; 

   - computer-aided design; 

   - self-optimizing adaptive control algorithms.

4.  Noise filtering

   High-frequency noise which contaminates the controlled variables and which cannot be controlled, has to be filtered by analogue and digital filters.

5.  Feedforward or feedback control of actuators

   Depending on the construction of the actuator, various feedforward or feedback controls of the actuator are possible. The control algorithms for the process have to be adjusted to the actuator control.

3.  For all control and filter algorithms the effects of amplitude quantization have to be considered.

![image](/img/in-post/master/dcs/1.png)



