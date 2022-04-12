
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

![Table-Carrying Task](https://user-images.githubusercontent.com/62581907/163048246-85f3c24b-0f8b-4946-a6fa-4f4c4c19aa14.png)

Similar studies were done with table-carrying (found [here](https://ieeexplore.ieee.org/abstract/document/7451736?casa_token=O9MJeLpLVjEAAAAA:dZ8wx4hJri3LY_tx9bdiQhvKDuqQqrv5iN9On3Sic7LRHzF47O9tovLZWJVmFIa6HQy5sK7TJA)) and table-clearing (found [here](https://arxiv.org/abs/1701.07851)) that applied this same mutual-adapation model and found similar results. The latter table-clearing study is the likely the most useful due to the higher resolution of the action space and applicability of the algorithm to other domains.

![Table-Clearing Task](https://user-images.githubusercontent.com/62581907/163049599-7651d521-52fc-4274-a50d-dfac1a2f156a.png)

### Additional Reading
+ [Human-robot mutual adaptation in collaborative tasks: Models and experiments](https://journals.sagepub.com/doi/10.1177/0278364917690593?icid=int.sj-abstract.similar-articles.3)
+ [Formalizing human-robot mutual adaptation: A bounded memory model](https://ieeexplore.ieee.org/abstract/document/7451736?casa_token=O9MJeLpLVjEAAAAA:dZ8wx4hJri3LY_tx9bdiQhvKDuqQqrv5iN9On3Sic7LRHzF47O9tovLZWJVmFIa6HQy5sK7TJA)
+ [Human-Robot Mutual Adaptation in Shared Autonomy](https://arxiv.org/abs/1701.07851)


# Incorperating Unexpected Human Behaviors
The previous section deals with how to interact with humans that are suboptimal. We will now look at how to calibrate trust when the human is not necesarrly behaving subotionally or when there is low ammount of trust in the robot.  Humans tend to be very good at make decisions in new scenarios. Robots are not so good at this and can percieve the human to be acting suboptimally when infact they are not. This also motivates a second question; does the human even want the help of the robot? The following studies will look at these perspectives and provide a framework of dealing with unexpected behaviors.

## Sample Projects
The authors in social cobot paper (found [here](https://www.sciencedirect.com/science/article/abs/pii/S0007850619301593?casa_token=APqvpoaiT1QAAAAA:4ttyWewDfeyilQtHYyGLGREwu3nwPehZK1i5IYSaVh0iFgt3c6o3e-GGg1HYReu2-2yi98CnbC8) proposed a way that the human may a) have intentions that are irrelevant and unkown intentions (motivation loss, alternative tasks, fatigue, ect...) and b) relevant intentions that they do not want the robot to assist with (distrust in robot, emotional state, ect...). They generated robot behavior that can both actively assist, stand by until needed, or communicate unexpected behaviors in a way that aligns with their turst in the robot. Consequently, the robot _optimally_ achieves the collaboration without overstepping its role in the human's task. The best example of this would be when the human does not desire robot intervention (due to distrust) but is distracted (looking around or performing tasks irrelevant to team goals), the robot may point to the object that it thinks is the optimal action that the human should take. They foound that proactively planning robot behavior, in accordance with the estimated trust in the robot, generated the most successfull interaction.

![image](https://user-images.githubusercontent.com/62581907/163053105-f85a42df-2320-4edf-86dc-62f1daa04b71.png)

A similar study was done (found [here](https://www.sciencedirect.com/science/article/abs/pii/S0007850619301593)) where humans and robots intermittantly collaborated on a factory floor. These authors were able to identify human states and intentions to effictively collaborate in, take-over, and surrender tasks as the human moved around this enviorment under thier proposed models of trust.

![image](https://user-images.githubusercontent.com/62581907/163054028-91e5598e-53a2-4493-b4d7-f9c9459034c7.png)



### Additional Reading
+ [Symbiotic human-robot collaborative assembly](https://www.sciencedirect.com/science/article/abs/pii/S0007850619301593?casa_token=APqvpoaiT1QAAAAA:4ttyWewDfeyilQtHYyGLGREwu3nwPehZK1i5IYSaVh0iFgt3c6o3e-GGg1HYReu2-2yi98CnbC8)
+ [Symbiotic human-robot collaborative assembly](https://www.sciencedirect.com/science/article/abs/pii/S0007850619301593)


# Dynamic Models of Trust




[Return Home Page](../index.md)
