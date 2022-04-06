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

Based on the application, the transfer learning algorithms vary to a certain degree. Here we provide some of the sample projects on transfer learning on different applicaitons.

### Sample Projects

![Octocat](https://github.githubassets.com/images/icons/emoji/octocat.png)

| Application  | Description |
| ----------- |  :----: |
|  Transfer Learning in Computer Vision                   |[identifying cancer cells in absence of large dataset](https://ieeexplore.ieee.org/document/8641762)          |
| Assistive Tool & Part Retrivial  |[<img src="https://img.youtube.com/vi/RN9iskWeNfE/0.jpg" width="30%" height="30%">](https://youtu.be/RN9iskWeNfE)   |

|     <img src="https://img.youtube.com/vi/I7mAoEJHee4/0.jpg" width="30%" height="30%">     |     Transfer Learning in Computer Vision\

Transfer learning is a popular method in computer vision because it allows us to build accurate models in a timesaving way (Rawat & Wang 2017). With transfer learning, instead of starting the learning process from scratch, you start from patterns that have been learned when solving a different problem [**here**](https://github.com/sunamatya/SocialGracefullnessTIV).
The [website](https://towardsdatascience.com/transfer-learning-from-pre-trained-models-f2393f124751#:~:text=Transfer%20learning%20is%20a%20popular,when%20solving%20a%20different%20problem.) provides sample code on using deep learning method to develop classifier for identifying cats from re-purposing a pre trainined model. 
The algorithms are not limited to image classifier, the research has been used in [identifying cancer cells in absence of large dataset](https://ieeexplore.ieee.org/document/8641762)|

* Transfer Learning in Human-Robot Interaction\
The authors of [Conventions](https://arxiv.org/pdf/2104.02871.pdf) introduce the idea of conventions to differentiate the knowledge that may be specific to the task and to the partners. 
Multi-level Perceptrons are used to encode the behavior of the agents. \
Spotlight Talk about the framework is available [here](https://www.youtube.com/watch?v=rTPEPG4kc34&t=726s)\
The code for the paper is available [here](https://github.com/Stanford-ILIAD/Conventions-ModularPolicy)

* Simulation Software for Transfer and Generalization in Autonomous Vehicles\
To generate a generalizable policy for the autonomous vehicles in real world scenario, the authors have developed[MetaDrive](https://decisionforce.github.io/metadrive/)\. The system currently supports RL algorithms and MARL algorithms with varying driving scenarios, vehicle dynamics and real data set inclusion.
Posing the same property, [CommonRoad](https://commonroad.in.tum.de/) is a collection of composable benchmarks for motion planning on roads, which provides researchers with a means of evaluating and comparing their motion planners.
RL framework has been integrated in the CommonRoad framework. There are available blogs and forums for support.

### Additional Videos and Media
+ [Deep Learning AI specialization in data science](https://www.youtube.com/watch?v=yofjFQddwHE&t=604s)
+ [Deep Mind's Demis Hassabis on transfer learning](https://www.youtube.com/watch?v=YofMOh6_WKo)

### Additional Reading
+ [Deep Mind collection in transfer learning](https://www.deepmind.com/search?query=transfer+learning)
+ [A survey on transfer learning](https://ieeexplore.ieee.org/abstract/document/5288526)
+ [A comprehensive survey on transfer learning](https://ieeexplore.ieee.org/abstract/document/9134370)

[Return Home Page](../index.md)
