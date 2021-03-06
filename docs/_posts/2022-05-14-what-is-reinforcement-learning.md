---
layout: post
title:  "Reinforcement Learning - Human inspired machine learning"
date:   2022-05-14 23:46:00 +0530
categories: [reinforcement learning,machine learning]
---


Human brain is probably one of the most complex systems in the world and thus it’s an in-exhaustive source of inspiration for any AI researcher. For decades reinforcement learning has been borrowing ideas not only from nature but also from our own psychology making a bridge between technology and humans.

Humans apply key concepts of Reinforcement Learning in almost every aspect of our live. For example a kid taking the liberty of doing a mischief. There is no definitive guide such as "Hitchhiker's guide to mischief". The kid goes ahead with it and based on the reaction of the person on the receiving end of the mischief, may never repeat in future.

Learning from interaction with the environment comes from our natural experiences.

Another example would be a toddler learning to walk.


<img src="{{ site.baseurl }}/static/img/toddler_1.png" style="height:200px;width:250px;"/>
<img src="{{ site.baseurl }}/static/img/toddler_2.png" style="height:200px;width:250px;"/>

(Image Courtesy - https://www.youtube.com/watch?v=CKgxMu1oMOg) 


A toddler is sitting on the floor (it’s her current state),  takes an action - tries to stand up, and gets a reward after this. That is reinforcement learning in short.

The toddler does not know how to walk but she learns by trial and error. An environment gives feedback such as pain, when she falls down, or a hug from a loving mother, when she takes a step. Does this sound familiar? Yeah, it’s what many people know as positive and negative reinforcement or in more general way operant conditioning. We also apply it when we teach a dog to bark or to roll, for example.

> **Science makes mathematical model of reality** - _Leslie Lamport_

Reinforcement Learning is just a computational approach of learning from action. RL is a type of Machine Learning where an agent learns how to behave in an environment by performing actions and seeing the results.

<br>
### The keywords of RL

**Agent** is what many call an AI but it basically a personification of an algorithm which acts in an environment. 
A person, a dog, or a toddler could be an agent.

**Environment** is what surrounds the agent and what the agent takes a reward from. For example, the world around us or a game you play.

**Policy** is logic, morality and the brain of the agent. It gives the agent an insight on what he should do in order to succeed. Speaking more technically, it tries to predict the outcome of agent’s actions in some given situation.

**Reward** is what the agent gets when it does something. It could be positive or negative depending on how well the agent acts. A cookie for a dog for making a roll is an example of a positive reward and a violent shout of your coach is an example of a negative reward.

**State** is a situation the agent got into. It’s some representation of the information you possess, like how much money you have, how far from work you live, how lazy you are. The agent decides what to do depending on a state.

So basically what RL researchers do is trying to create such an agent (in terms of RL our toddler is an agent) which will be operating in an environment (such as the world for the toddler) and could understand what is the best move in a given situation. Back to toddler example, how he should put his body in order to hold the balance and make a step.

<br>
### The official definition

> Reinforcement Learning is about complex sequential decision-making under uncertainty.

Let's unpack it a bit, shall we? 

**Sequential** - The agent decides upon an action based on the state it is presented by the environment. As a result of that, environment 
presents reward, another state and decision-making opportunity for the agent. This continues till a terminal state is encountered 
(death if we formulate human life as a Reinforcement learning problem)

**Decision Making** - The action to take given the state so as to maximize cumulative rewards

**Under Uncertainity** - The agent does not know how the environment will react after an action it takes. Very much like real life. How would 
a domain change (For eg from data science to selling organic products) pan out. Will it be more rewarding or would one regret it?



<br>
### Conclusion

RL is a powerful and versatile branch of machine learning. It allows agents to learn, not through examples or even data, but by interacting with an environment, to optimize decision making. 

In a nutshell, RL is the study of agents and how they learn by trial and error. It formalizes the idea that rewarding or punishing an agent for its behavior makes it more likely to repeat or forego that behavior in the future.

The key advantage of reinforcement learning is its ability to develop behavior by taking actions and getting feedback, similar to the way humans and animals learn by interacting with their environment. Some scientists describe reinforcement learning as "the first computational theory of intelligence."
