---
title: Human Robot Teaming
---

[Return Home Page](../index.md)
# Introduction 
Robots have recently seen advances in sensing and control such that they can now enter the same workspace as humans. This affords a unique opportunity to apply the strengths of humans (general inteligence, flexibility, and contextual awarness) with the strengths of robots (accuracy, repeatability, and endurance). Effectivly implementing a human-robot team (HRT) can premote task efficiency while reducing cost, fatigue driven error, and risk in several applications. The remainder of this page will now explore the tpyes of HRTs as well as the industries and applications that stand to benifit from introducing a robotic teammate.  Specifically, we will explore three types of interection paradigms that is commonly found when disucssing HRT: 1) task handoff, 2) shared task execution, and 3) shared control.

<!--- ![HRC Modes](https://user-images.githubusercontent.com/62581907/154872098-36b5132e-6880-4e30-a837-aed7ee3d11e3.png) --->

# Handover Tasks
Task handoff refers to multiple agents that independantly complete subtasks that accumulate to the final goal of the team. The distingushing feature of this type of interaction is that teammates must be ADD

The key features of handover tasks are:
- Intermittantly interact with partner
- Full awarness of partner actions not required
- Independant completion of tasks with dependant task flow

## Example Applications

| Application  | Video Link |
| ----------- |  :----: |
| Object Handover                  |[<img src="https://img.youtube.com/vi/I7mAoEJHee4/0.jpg" width="30%" height="30%">](https://youtu.be/I7mAoEJHee4?t=126)   |
| Assistive Tool & Part Retrivial  |[<img src="https://img.youtube.com/vi/RN9iskWeNfE/0.jpg" width="30%" height="30%">](https://youtu.be/RN9iskWeNfE)   |


## Research & Resources 
- Huang C-M, Cakmak M, Mutlu B (2015) Adaptive Coordination Strategies for Human-Robot Handovers. Proc. 2015 Robot. Sci. Syst. Conf
- A. Bestick, R. Bajcsy, and A. D. Dragan. Implicitly assisting humans to choose good grasps in robot to human handovers. In International Symposium on Experimental Robotics. Springer, 2016
- F. Cini, T. Banfi, G. Ciuti, L. Craighero, and M. Controzzi, “The relevance of signal timing in human-robot collaborative manipulation,” vol. 1308, pp. 1–12, 2021.







# Shared Task Execution
Shared task execution refers to multiple agents that simultanously work on the same subtask. In contrast to task handoff, interaction with shared task execution is at such a high frequency, or possibly continous, that each team member must integrate their perceptions of their partner's actions into their low-level control and decision-making. That is to say, a team of this type must be actively aware of the partner's actions so that they can appropriatley adapt their trajectory and intentions to supplement their parnter. 

A common application in industry is for manufacturing; mainly collaborative assembly. Collaborative assembly in this context implies that a human and robot are operating in a shared enviorment and must actively adapt to their partner and jointly plain their actions in order to effectivley complete the task. Because collision between the robot and human is certainly possible in this type of enviorment, saftey is of particular interest to control of these robotic devices.

## Example Applications
| Application  | Video Link |
| ----------- |  :----: |
| Pick-and-Place |[<img src="https://img.youtube.com/vi/i9Vbh2mPG6M/0.jpg" width="30%" height="30%">](https://youtu.be/i9Vbh2mPG6M) |
| Automotive Assembly |[<img src="https://img.youtube.com/vi/O0Xcb_eLjYA/0.jpg" width="30%" height="30%">](https://youtu.be/O0Xcb_eLjYA?t=80) |


## Research & Resources 
- A. Hietanen, R. Pieters, M. Lanz, J. Latokartano, and J. K. Kämäräinen, “AR-based interaction for human-robot collaborative manufacturing,” Robot. Comput. Integr. Manuf., vol. 63, no. November 2019, p. 101891, 2020, doi: 10.1016/j.rcim.2019.101891.
- S. Tellex, R. A. Knepper, A. Li, T. M. Howard, D. Rus, and N. Roy, “Assembling Furniture by Asking for Help from a Human Partner,” Collab. Manip. Work. Human-Robot Interact., 2013.
- A. Casalino, F. Cividini, A. M. Zanchettin, L. Piroddi, and P. Rocco, “Human-robot collaborative assembly: a use-case application,” IFAC-PapersOnLine, vol. 51, no. 11, pp. 194–199, 2018, doi: 10.1016/j.ifacol.2018.08.257.


# Shared Control

## Example Applications
| Application  | Video Link |
| ----------- |  :----: |
|Teleoperation | [<img src="https://img.youtube.com/vi/M6mQWcLAiko/0.jpg" width="30%" height="30%">](https://youtu.be/M6mQWcLAiko) |
|Co-Manipulation | [<img src="https://img.youtube.com/vi/xB9-vEiZwKY/0.jpg" width="30%" height="30%">](https://youtu.be/xB9-vEiZwKY?t=28) |

## Research & Resources 
- N. Amirshirzad, A. Kumru, and E. Oztop, “Human adaptation to human-robot shared control,” IEEE Trans. Human-Machine Syst., vol. 49, no. 2, pp. 126–136, 2019, doi: 10.1109/THMS.2018.2884719.
- K. E. Schaefer, E. R. Straub, J. Y. C. Chen, J. Putney, and A. W. Evans, “Communicating intent to develop shared situation awareness and engender trust in human-agent teams,” Cogn. Syst. Res., vol. 46, pp. 26–39, 2017, doi: 10.1016/j.cogsys.2017.02.002.


_Author: Mason Smith_
[Return Home Page](../index.md)
