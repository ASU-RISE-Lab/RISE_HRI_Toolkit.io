---
title: Trust
---

[Return Home Page](../index.md)

# Introduction
Creating a human decision-making model (HDMM) is often critical to the success of any human-robot interaction (HRI) context. This is because interaction requires some insight on the human agent's behavior such that the robot can accuratley predict future actions and plan accordingly. HDMMs are applied in both competitive as well as collaborative settings and can be implemented using a multitude of learning or control algorithms. Thus, we will look into three different types of HDMM: 1) rational agents, 2) noisy rational agents, 3) suboptimal agents.

# Rational Agents
Rational agents are actors that will **always** take the action that maximizes their future expected reward. This is the baseline model for capturing human behavior and it assumes that they think in the same way that the robotic partner would. In stochastic enviorments, a rational agent will correctly weight their expected reward according probabilities of an outcome occuring given an action. This HDMM is typically sufficient in simple and static enviorments where the human is able to percieve the full time horizon computation and determine what action is optimal.

<!---Osborne, Martin; Rubinstein, Ariel (2001), A Course in Game Theory, Cambridge, Massachusetts: MIT Press, p. 4, ISBN 0-262-65040-1 ---> 

It should be noted that a rational agent will take actions based upon:
- their individual preferences and goals (reward function)
- the information available to them; including past experiences (observation)
- the expected return from performing a single or sequence of actions (expected reward)

<img src="https://latex.codecogs.com/png.image?\dpi{110}&space;\bg_white&space;a_H&space;=&space;argmax_{a_H}&space;R_{H}(a_{H})" title="\bg_white a_H = argmax_{a_H} R_{H}(a_{H})" />

# Noisy Rational Agents
Noisy rational agents are actors that take an action with a probability proportional to the future expected reward. This is a popular approach to HDMM because of the simplicity and its ability to relax a strong assumption of rational agents. Assuming that humans are always rational does not account for the limited time to make decisions, the ammount of computational resources, and noise from individual variation within humans. Instead, we can assume that the human is _approximatley rational_ and will make decisions that will result in a high reward most of the time. This is also refered to as _Boltzmann rationality_ and can 

<img src="https://latex.codecogs.com/png.image?\dpi{110}&space;\bg_white&space;\mathbb{P}\frac{e^{\beta&space;\cdot&space;R_{H}(a_{H})}&space;}{\sum_{a\in&space;A}e^{\beta&space;\cdot&space;R_{H}(a_{H})}" title="\bg_white \mathbb{P}\frac{e^{\beta \cdot R_{H}(a_{H})} }{\sum_{a\in A}e^{\beta \cdot R_{H}(a_{H})}" />
where β is the _rationality coefficient_ that determines how noisy the human's actions will be. For example, as we increase β from β=0 (human uniformly picks from their actions) to larger values, we assume that the human is more optimal and is as a better reward maximizer.


# Suboptimal Agents
Suboptimal agents are actors that make systamatically biased decisions. This presents itself as _complex noise_ in the distribution of possible actions that an agent can make that cannot be described by noisy rationality. Humans commonly demonstrate suboptimality in scenarios that include uncertainty, risk, and suffient complexity such that they rely on heuristic decision making. This is an emerging direction of research that has generated two approaches to creating a HDMM: 1) explicitly modeling suboptimal behavior and 2) learning suboptimal behavior.

## Explicitly Modeling Suboptimal Behavior

## Learning Suboptimal Behavior







# Main Topic 1 
*(EXAMPLE: Game Theory)* \
*(Insert short introduction for main topic)*

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
+ Osborne, Martin; Rubinstein, Ariel (2001), A Course in Game Theory, Cambridge, Massachusetts: MIT Press, p. 4, ISBN 0-262-65040-1

[Return Home Page](../index.md)
