---
title: Autonomous Vehicles
---

[Return Home Page](../index.md)
## Introduction
Driver error factors in 94% of causes of car crashes. Self-driving vehicles help in reduced such driver error saving lives. 
Industrial interests in autonomous vehicles is of growing interest with automated deliveries amid safety interests during Covid-19 pandemic.
Autonomous Vehicles need to be **safe** as well as should be able to **interact** with other vehicles in crowded environment.
Often times data driven systems fail to work in previously unseen environment. 
We provide here some of the algorithms AV interactions have been modeled with some of the available datasets.

## Data Driven Multi Agent Trajectory Prediction
With the inception of deep network, Autoencoders and (Generative Adversarial Network) GAN have shown great performance in computer vision applications. 
However when it comes to encoding interactions in AV setup, the temporal and topological contextual information for all the participating agents are imperative.
Some of the recent data driven network encoding such information are presented below:

### [Social GAN](https://openaccess.thecvf.com/content_cvpr_2018/html/Gupta_Social_GAN_Socially_CVPR_2018_paper.html)
One of the most sort out paper, the proposed GAN model was encoded each agent's motion in interpersonal level with the agents in the environment with social acceptance clause and further made the system multimodal.
The presented social pooling algorithm has influenced other GAN based model for predicting multi agent trajectory.

### [CGNS](https://ieeexplore.ieee.org/abstract/document/8967822)
the authors proposed Conditional Generative Neural Systems (CGNS) which jointly predict future trajectories of multiple highly-interactive agents, which takes into account the static context information, interactions among multiple entities and feasibility constraints.
A block attention mechanism and a Gaussian mixture attention mask are proposed and applied to historical trajectories and scene image sequences respectively, which are computationally efficient.
Hence the proposed system is context aware, interaction aware, feasibility aware and provides probabilistic condition on predicted algorithm. 

### [Social-WaGDAT](https://arxiv.org/abs/2002.06241)
The authors propose a generic generative neural system (called Social-WaGDAT) for multi-agent trajectory prediction where explicit interaction are modeling by incorporating relational inductive biases with a dynamic graph representation and leverages both trajectory and scene context information. 
They further employ an efficient kinematic constraint layer applied to vehicle trajectory prediction which not only ensures physical feasibility but also enhances model performance. 
The system has been evaluated on three public benchmark datasets for trajectory prediction, where the agents cover pedestrians, cyclists and on-road vehicles. 
The ablation and baseline study carried out in the paper gives an outline on the state of the art algorithms in such social models.

### [Probabilistic Crowd GAN](https://ieeexplore.ieee.org/abstract/document/9123560)
Probabilistic Crowd GAN, extends recent work in trajectory prediction, combining Recurrent Neural Networks (RNNs) with Mixture Density Networks (MDNs) to output probabilistic multimodal predictions, from which likely modal paths are found and used for adversarial training.
the use of Graph Vehicle- Pedestrian Attention Network (GVAT), which models social interactions and allows input of a shared vehicle feature, showing that inclusion of this module leads to improved trajectory prediction both with and without the presence of a vehicle.


## Game Theoretic Trajectory Prediction
Unlike the data driven counterpart, the game theoretic models represents the agents with strategies to reduce their cost function while in interaction with the other agents.
Nash Equilibrium solutions are heavily exploited in such interactions. Depending on the discrete or continuous action and state space, the solutions to the interaction can be based off of graphical solution to solving Hamilton Jacobi Issac's solution.
Below are some of the papers that have used game theoretic trajectory predictions. In some solutions the authors deal with incomplete information setting where the intent of the other agents are not present. Here intent refers to the goal directed behavior which is part of any optimization based algorithm. 

### [Safe and Interactive Autonomy](https://www2.eecs.berkeley.edu/Pubs/TechRpts/2017/EECS-2017-143.pdf)
The presented work is the thesis work of Dorsa Sadign who presented a comprehensive study for Nash Equilibrium solutions in multi agent interaction. The driving interaction in belief update and preferences are highlighted which provides different motion. 
The papers with the subsequent codes are available in Dorsa's github [here](https://github.com/dsadigh). 

### [Courteous Autonomous Cars](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8593969)
Besides performing a game theoretic solution for multi agent interactions, the authors here  formalize courtesy as a
term in the objective that measures the increase in another
driver’s cost induced by the autonomous car’s behavior. The courteous behavior aids in explaining human driving. The authors have further validated the proposed algorithm in NSGIM Dataset.

### [Social Behavior in Autonomous Vehicles](https://www.pnas.org/doi/10.1073/pnas.1820676116)
We present a framework that integrates social psychology tools into controller design for autonomous vehicles. Our key insight utilizes Social Value Orientation (SVO), quantifying an agent’s degree of selfishness or altruism, which allows us to better predict driver behavior.
The presented algorithm has been further validated in the NSGIM dataset

 
## Available Datasets
* [**INTERACTION Dataset**](https://interaction-dataset.com/)\
The INTERACTION dataset contains naturalistic motions of various traffic participants in a variety of highly interactive driving scenarios from different countries. 
* [**NSGIM Dataset**](https://ops.fhwa.dot.gov/trafficanalysistools/ngsim.htm)\
NSGIM dataset has been developed with the intention of open behavioral algorithms in support of traffic simulation with a primary focus on microscopic modeling, including supporting documentation and validation data sets that describe the interactions of multimodal travelers, vehicles and highway systems, and interactions presented to them from traffic control devices, delineation, congestion, and other features of the environment.
* [**high D**](https://www.highd-dataset.com/)\
The highD dataset is a new dataset of naturalistic vehicle trajectories recorded on German highways. Using a drone, typical limitations of established traffic data collection methods such as occlusions are overcome by the aerial perspective.
* [**ZEN**](https://zen-traffic-data.net/english/outline/dataset.html)\
Zen dataset is from Japan and developed by Hanshin Expressway Company. The data consists of wide range and long period of all vehicle trajectory data and any other data affecting traffic events.
* [**AGROVERSE**](https://www.argoverse.org/)\
Argoverse is developed by Argo AI, in collaboration with faculty and students from Carnegie Mellon University and Georgia Institute of Technology. One of the first publicly available datasets for research into self-driving vehicle perception, and grew into a larger project to provide high quality curated data and detailed maps to improve 3D tracking and motion forecasting models.
* [**WAYMO**](https://waymo.com/intl/en_us/dataset-download-terms/)\
The Waymo Open Dataset is a perception dataset comprising high resolution sensor data and labels for 1,950 segments.


### Sample Projects
* [Scalable and Customizable Intent Inference and Motion Planning for Socially-Adept Autonomous Vehicles](https://home.riselab.info/nri.html)\
The overall objective of this project is to allow future autonomous vehicles to interact with multiple surrounding vehicles in a safe and socially-adept manner. 
The authors develop a game based dynamics-aware intent inference algorithm which enables courteous vehicle interaction.
The code is available [**here**](https://github.com/sunamatya/SocialGracefullnessTIV)
 
### Additional Videos and Media
+ [MIT deep learning series on Autonomous Driving](https://deeplearning.mit.edu/)
+ [A Veratasium video on WAYMO cars on road](https://www.youtube.com/watch?v=yjztvddhZmI)

### Additional Reading
+ [Autonomous Driving: Technical, Legal and Social Aspects](https://www.google.com/books/edition/Autonomous_Driving/HdtCDwAAQBAJ?hl=en&gbpv=1)
+ [Autonomous Vehicles: Technologies, Regulations and Societal Impacts](https://www.google.com/books/edition/Autonomous_Vehicles/BggWEAAAQBAJ?hl=en&gbpv=1&dq=autonomous+vehicles&printsec=frontcover)

[Return Home Page](../index.md)
