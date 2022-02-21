---
title: Transfer and Curriculum Learning
---

[Return Home Page](../index.md)
# Transfer and Curriculum Learning
## Introduction
Human's are intrinsically able to transfer the knowledge from one scenario to another task. With the inception of deep reinforcement learning algorithms, we are able to see
super human performance in many domains. These methods often spend a huge amount of time and resources to train a deep model to perform a single task.
When the problem is extend to a multi-agent setting, the system gets exponentially difficult to solve. Quite often when we include decision making model
in belief state, the system becomes even more complicated to run. Currently applying knowledge gained from performing a single task to performing an other related task remains a challenging problem. This is the problem **Transfer
learning** is trying to solve (Taylor Stone, 2009).\\
A curriculum is an efficient tool for humans to progressively learn from simple concepts to hard problems. 
It breaks down complex knowledge by providing a sequence of learning steps of increasing difficulty.
While curriculum learning has been presented in a wide range of human robot intersection and application, an excellent blog to understand 
Curriculum learning for Reinforcement Learning is [here](https://lilianweng.github.io/lil-log/2020/01/29/curriculum-for-reinforcement-learning.html)

Sebastian Ruder, posted a blog in titled ["Transfer Learning- Machine Learning's Next Frontier"](https://ruder.io/transfer-learning/).
The article presents the idea of transfer learning, applications, scenarios and methods and related work in the research area. The article was presented in 2017 but is a beginner's guide to transfer learning.
In sections below, we will be presenting some of the state of the art algorithms in transfer learning and focus on avenues of research at RISE-Lab.

## Transfer Learning in Computer Vision



## Algorithms for Transfer Learning

## Multi Task Learning and Transfer 
There exist various techniques that incorporate tasks directly into the definition of the value function
for multitask learning (Kaelbling, 1993; Ashar, 1994; Sutton et al., 2011). UVFAs have been used for
zero-shot generalisation to combinations of tasks (Mankowitz et al., 2018; Hermann et al., 2017), or
to learn a set of fictitious goals previously encountered by the agent (Andrychowicz et al., 2017).
One of the key aspects of learning can be through MetaLearning where the agents are taught different task and the genralization of the task to a new task is tested.
Thus signfying true transfer. \

When we think of value functions or universal value functions for the function approximation across tasks, we can look into how transfer learning can be approached using Reinforcement Learning.
One of the key aspects of transfer in RL to do multi task is through UVFAs.
Another aspect for transfer in RL is done through the idea of Successor Features, where the reward of the RL algorithm is divided into weights and features associated to the environment.
Deepmind, has been working on this idea for years now. The associated research for this can be found in [here](https://deepmind.com/blog/article/fast-reinforcement-learning-through-the-composition-of-behaviours)



## Transfer Learning in Human-Robot Interaction
*[Conventions](https://arxiv.org/pdf/2104.02871.pdf)\
The authors introduce the idea of conventions to differentiate the knowledge that may be specific to the task and to the partners. 
Multi-level Perceptrons are used to encode the behavior of the agents. \
Spotlight Talk about the framework is available [here]https://www.youtube.com/watch?v=rTPEPG4kc34&t=726s)\
The code for the paper is available [here](https://github.com/Stanford-ILIAD/Conventions-ModularPolicy)


## Transfer Learning in Autonomous Vehicles
*[Transferable and Adaptable Driving Behavior Prediction]


### Simulation Software for Transfer and Generalization
* [MetaDrive](https://decisionforce.github.io/metadrive/)\
To generate a generalizable policy for the autonomous vehicles in real world scenario, the authors have developed Meta Drive. 
The system currently supports RL algorithms and MARL algorithms with varying driving scenarios, vehicle dynamics and real data set inclusion.

* [CommonRoad](https://commonroad.in.tum.de/)\
CommonRoad is a collection of composable benchmarks for motion planning on roads, which provides researchers with a means of evaluating and comparing their motion planners.
RL framework has been integrated in the CommonRoad framework. There are available blogs and forums for support.

### 



## Concept or Subtopic 1
*(EXAMPLE: Nash equilibrium solutions)*\
*(ADD: description of concept or subtopic)*

### Sample Projects
*(ADD: RISE Code/Github link and description)*\
*(ADD: or in text example/walkthrough)*
 
### Additional Reading
+ *(ADD: Article)*
+ *(ADD: Article)*
+ *(ADD: Article)*


## Concept or Subtopic 2
*(EXAMPLE: Pareto optimality)*\
*(ADD: description of concept or subtopic)*

### Sample Projects
*(ADD: RISE Code/Github link and description)*\
*(ADD: or in text example/walkthrough)*

### Additional Reading
+ *(ADD: Article or resource)*
+ *(ADD: Article or resource)*
+ *(ADD: Article or resource)*

[Return Home Page](../index.md)
