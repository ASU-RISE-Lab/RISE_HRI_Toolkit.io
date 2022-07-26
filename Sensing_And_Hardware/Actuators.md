---
title: Actuators
---

[Return Home Page](../index.md)
# Common Robotics Actuators
## Motors
### DC Motors
### Stepper Motors
### Servo Motors

## Linear Actuators
### Electric
### Fluid (Hydraulic and Pneumatic)

# Actuators for HRI

In industrial robtics, computerized machines are used to perform complex and often repetitive tasks in a production line. Once an industrial robot has been properly configured to perform its task, little interaction from human operators is required. As such, safety solutions in industrial robotics typically focus on providing safeth through physical solutions. These include alarmed cages around robot work cells, which will immediately halt the robot if entered during operation, and eliminating physical hazards such as teach pendant cables. This approach to safety is similar to that applied to other potentially dangerous equipment. th ISO identifies four approaches to safety for human-robot collaboration in an industrial context, as shown below.

![Four forms of safety in industrial human-robot collaboration.](/Sensing_And_Hardware/four_forms.jpg)

A safety-monitored stop is the most basic safety measure, automatically stopping robot operation when the work cell is entered by a human. Hand guiding utilizes a force-sensitive module to enable an operator to manually guide the end effector during programming. Speed and separation monitoring detects human presence and slows the robot accordingly. Power and force limiting reduces actuator power and speed so that unintentional collisions will have an impact force below the desired safety threshold.


## Flexible and Lightweight Robots

Flexible and lightweight robots improve HRI safety by reducing the energy of robot motions by decreasing weight and reducing collision force through added joint flexibility. If the impulse of a collision is constant, the maximum force applied will be lower for a longer collision than for a shorter one. Causes of contact-based injuries can be grouped into two genral categories: quasistatic clamping and dymanic loading. Quasistatic clamping includes actions such as grasping and pinning, where the applied force is typically used as a measure of injury potential. Dynamic loading includes collisions and impacts, where acceleration and energy are measures of injury potential.

### Backdrivable Electric Motors

Controlling actuator torque can reduce the risk of quasistatic clamping injuries by limiting the amount of force applied to within safe levels.

### Pneumatic Actuators

These include conventional rotary and linear actuators, along with soft robotic actuators. When operating at low pressures, the compressibility of air provides additional flexibility in the joint. This flexibility may make open-loop control infeasible, requiring additional sensors to determine the robot state.

## Soft Robotics

## Haptics



### Sample Projects
*(ADD: RISE Code/Github link and description)*\
*(ADD: or in text example/walkthrough)*
 
### Additional Reading
[Nook Industries: Selecting Lienar Actuators For Robotics](https://www.nookindustries.com/resources/blog/archive/selecting-linear-actuators-for-robotics/)
[Soft Robotics Toolkit: Actuators](https://softroboticstoolkit.com/actuators)
+ *(ADD: Article)*
+ *(ADD: Article)*
+ *(ADD: Article)*



### Sample Projects
*(ADD: RISE Code/Github link and description)*\
*(ADD: or in text example/walkthrough)*

### Additional Reading
+ *(ADD: Article or resource)*
+ *(ADD: Article or resource)*
+ *(ADD: Article or resource)*

[Return Home Page](../index.md)
