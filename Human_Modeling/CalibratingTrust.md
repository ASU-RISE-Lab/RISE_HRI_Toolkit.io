
---
title: Calbirating Trust
---

[Return Home Page](../index.md)

Typically robot policies are found to comply and supplement human preferences. This is sufficient for most cases of human-robot interation (HRI) since the human is genrally considered to be a good maximizers of task rewards.  However, what happens when the human is behaving suboptimally according the the robot's reward function? In these cases there are several questions that the must be adressed when interecting:

1. Should the robot intervene to mitigate the effect of suboptimal behavior in team performance?
2. Should the robot comply with the human to preserve their relationship (trust) and improve future team performance?
3. Is the human truely suboptimal or do they just look that way to the robot's assumed reward and limited generalizability?  

# Mutual Adaptation
One approach to the answering the first two questions is to balance a tradeoff between team performance and preserved trust based on the _adaptability_ of the human. The following studies look at how we can approach interacting with humans that behave unexpectedly according to the robot's reward function.

### Sample Projects
In a collaborative table carrying task (found [here](https://journals.sagepub.com/doi/10.1177/0278364917690593?icid=int.sj-abstract.similar-articles.3)), the authors assigned the human goal, either being the first or second agent to pass through the door, to be inherantly suboptimal no matter their actual choice. This is done under the assumption that the human will make decisions with incomplete information about the dynamics of the robot. For example, the sensing capabilities may be better on a certain side of the robot and make a given order of agents through the door optimal. However, if the a robot were to insist on a conflicting goal with a stubborn human, then the robot's reward would increase but conflicts that degrade trust would be generated. Conversely, if the human is more tollerant of intervention, then the robot can increase team performance with minimal degradation of trust. They found that the robot was able to achieve higher rewards under a mutaully-adaptive mode of behavior when compared to the traditional one-way adaptation (the robot follows human preferences in all cases). Also, they found that there was little significant difference in trust between these to models.  Therefore, this shows that there is an opportunity to increase team performance while preserving trust by estimating how _adaptable_ the human is and incorperating into the robot's decision-making.


https://journals.sagepub.com/na101/home/literatum/publisher/sage/journals/content/ijra/2017/ijra_36_5-7/0278364917690593/20170629/images/medium/10.1177_0278364917690593-fig1.gif

![image](https://user-images.githubusercontent.com/62581907/163048246-85f3c24b-0f8b-4946-a6fa-4f4c4c19aa14.png)

Similar studies were done with table-clearing tasks (found [here]) 
 
### Additional Reading
+ [Formalizing human-robot mutual adaptation: A bounded memory model](https://ieeexplore.ieee.org/abstract/document/7451736?casa_token=O9MJeLpLVjEAAAAA:dZ8wx4hJri3LY_tx9bdiQhvKDuqQqrv5iN9On3Sic7LRHzF47O9tovLZWJVmFIa6HQy5sK7TJA)
+ [Human-robot mutual adaptation in collaborative tasks: Models and experiments](https://journals.sagepub.com/doi/10.1177/0278364917690593?icid=int.sj-abstract.similar-articles.3)
+ [Human-Robot Mutual Adaptation in Shared Autonomy](https://arxiv.org/abs/1701.07851)
+ [Symbiotic human-robot collaborative assembly](https://www.sciencedirect.com/science/article/abs/pii/S0007850619301593?casa_token=APqvpoaiT1QAAAAA:4ttyWewDfeyilQtHYyGLGREwu3nwPehZK1i5IYSaVh0iFgt3c6o3e-GGg1HYReu2-2yi98CnbC8)

# Incorperating Unexpected Human Behaviors


# Explainability and Transparancy




[Return Home Page](../index.md)
