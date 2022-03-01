---
title: Robot-aided Gait Rehabilitation and Assistance 
---

[Return Home Page](../index.md)
# Introduction 
The aging population and neurological disorders such as stroke and Parkinson’s disease lead to increased walking impairments. Traditional gait rehabilitation techniques involve multiple training sessions supervised by physical therapists. This paradigm is physically demanding for therapists, inconvenient for patients, and expensive for the entire healthcare system. Wearable assistive robots have been shown effective in restoring lost motor functions and improve training performance. The goal is to develope intent estimation and adaptive control algorithms to personalize the robot assistance for different users in various tasks.


## Wearable Robots (Exoskeletons)
Lower-limb exoskeletons need to be light-weight,compact, powerfull enough to assist gait and lower-limb motions, safe and reliable. Series-elastic and cable-driven actuators [^1], soft actuators [^soft], and variable stiffness [^2] are among the widely used mechanisms to reach those goals.  
Both sigle and multi joints wearable robots can be used, depending on the gait impairment and assistance goal.   

### Additional Resources
* []

## Wearable Sensors 
Wearable Sensors are essntial in gait robotic rehabilitation to provide real-time user's data and states for the robot controller, as well as analysis and study of the human-robot gait. Encoder and inertial sensors are used to collect walking kinemtics [^w1]. Force plates and force sensor embedded insoles (smart shoes for example) [^w2] are used to study ground contact forces. Electromyography (EMG) [^w3] sensors are used to analyze muscle activities. 
### Aditional Resources
* []

## Gait Exoskeleton Controller 
![Picture6](https://user-images.githubusercontent.com/70563722/155220479-393d6fba-8150-412f-a692-3abeb6dcc838.png)
The overal control overview of gait exoskeleton is shown above [^c1]. The decision-making unit firstly needs to estimate the intent and states of the user based on the data from the sensors. For walking assistance and rehabilitations, estimation of gait phase and activity, along with pose and velocity of different body parts (i.e. pelvis) are vital to the motion/torque planning. In some cases the environemntal factors (train) are also need to be known or estimated, as they can influence the gait pattern and the required assistance. Gait phase and event detection are usually formulated as classification/pattern recogniion problems. Fuzzy Logic [^w1], hidden Markov models (HMM) [c^3] and support vector machines (SVM) [c^4] are among the commonly used methods. 
The mid-level controller mapps the detected intent and rehabilitation or assistance strategies to the desired device states for the low-level controller to track. Impedance controller is one of the most widely used method in this field regarding its clear physical intuition and simple implementation [^c5]. This approach gives the ability of controlling the position of the end-effector of the robot while maintaining safety limits on human-robot interaction force, which is desirable for rehabilitation and assistance applications. It is usually needed to modulate the impedance values based on different gait phases and activities [^c6] [^c7]. More controllers and strategies for lower-limb exoskeletons are included in the additional resources below. 
### Aditional Resources
* []
* 
[^w1]: A Wireless Human Motion Monitoring System for Smart Rehabilitation (https://asmedigitalcollection.asme.org/dynamicsystems/article/138/11/111004/473999/A-Wireless-Human-Motion-Monitoring-System-for)
[^w2]: An Advanced Gait Monitoring System Based on Air Pressure Sensor Embedded in a Shoe (https://www.sciencedirect.com/science/article/pii/S1877705812021121)
[^w3]: EMG and EPP-Integrated Human–Machine Interface Between the Paralyzed and Rehabilitation Exoskeleton (https://ieeexplore.ieee.org/document/6126040)
[^1]: A series elastic-and bowden-cable-based actuation system for use as torque actuator in exoskeleton-type robots (https://journals.sagepub.com/doi/10.1177/0278364906063829)
[^2]: Design of smart modular variable stiffness actuatorsfor robotic-assistive devices (https://ieeexplore.ieee.org/document/7929351)
[^soft]: Soft robotics: Review of fluid-driven intrinsicallysoft  devices; manufacturing, sensing, control, and applications in human-robot interaction (https://onlinelibrary.wiley.com/doi/10.1002/adem.201700016)
[^c1]: Control strategies for active lower extremity prosthetics and orthotics: a review (https://jneuroengrehab.biomedcentral.com/articles/10.1186/1743-0003-12-1)
[^c3]: An Unsupervised Approach for Automatic Activity Recognition Based on Hidden Markov Model Regression (https://ieeexplore.ieee.org/document/6516632)
[^c4]: Monitoring Motor Fluctuations in Patients With Parkinson's Disease Using Wearable Sensors (https://ieeexplore.ieee.org/abstract/document/5290148)
[^c5]: Impedance control: An approach to manipulation (https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=4788393)
[^c6]: Design and control of the MINDWALKER exoskeleton (https://ieeexplore.ieee.org/abstract/document/6940308)
[^c7]: Automatic virtual impedance adaptation of a knee exoskeleton for personalized walking assistance (https://par.nsf.gov/servlets/purl/10111547)

[Return Home Page](../index.md)
