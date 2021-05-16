+++
author = "Pierre Haou"
title = "Multi-Agent Reinforcement Learning (MARL) and Cooperative AI"
date = "2021-05-15"
+++

![Agents play hide and seek in OpenAI’s Emergent Tool Use from Multi-Agent Interaction. Gif by OpenAI.](/img/emergenttooluse.gif)

*Agents play hide and seek in OpenAI’s [Emergent Tool Use from Multi-Agent Interaction](https://openai.com/blog/emergent-tool-use/). Gif by OpenAI.*

Multi-Agent Reinforcement Learning (MARL) is a subfield of reinforcement learning that is becoming increasingly relevant and has been blowing my mind (see gif and link above). It has found incredible success in popular [strategy games](https://openai.com/projects/five/) and will be key to the continued advancement of several emerging technologies, communication between different autonomous vehicles being one such example. This post will first discuss what this subfield is, how it relates to Cooperative AI, and then quickly move onto the monumental impact these fields of study are poised to have in the future.

#### What is Multi-Agent Reinforcement Learning?

**Vanilla reinforcement learning** is concerned with a single agent, in an environment, seeking to maximize the total reward in that environment. You can imagine—or just view this [video](https://www.youtube.com/watch?v=gn4nRCC9TwQ&ab_channel=TechInsider)—a robot learning to walk, where its overall goal is to walk without falling. It receives rewards for taking steps without falling over, and through trial and error, and maximizing these rewards, the robot eventually learns to walk. In this context, we have a *single* agent seeking to accomplish a goal through maximizing total rewards.  

**Multi-agent reinforcement learning** studies how multiple agents interact in a common environment. That is, when these agents interact with the environment and one another, can we observe them collaborate, coordinate, compete, or collectively learn to accomplish a particular task. It can be further broken down into three broad categories: 

- Cooperative: All agents working towards a common goal
- Competitive: Agents competing with one another to accomplish a goal
- Some mix of the two: Think a 5v5 basketball game, where individuals on the same team are coordinating with one another, but the two teams are competing against one another. 

A canonical example of MARL is a swarm of robots seeking to rescue an individual. Each robot has only partial observability of its environment (they can only see a small patch of land below them) therefore the robots need to coordinate with one another to rescue the individual.

Here, we can see the barrier between science fiction and reality quickly dissolve. You are likely already imagining teams of robots building homes, autonomous vehicles seamlessly interacting with another, or distributed resource management. 
#### Large Scale Cooperation 

Cooperation at scale is a key ingredient to the incredible success of our species, homo sapiens. It is through humanity’s collective intelligence and collaboration that we have been able to accomplish unbelievable feats. To achieve large scale cooperation, we have created mechanisms that enable collaboration at scale. That is, we have created protocols (belief systems, systems of government, etc.) to induce large scale cooperation so that one feels comfortable collaborating with total strangers. Many of humanity’s failures and existential threats can be viewed as a coordination or collaboration issue (nuclear arms race, climate change, world wars etc.). How might MARL be used to solve these coordination issues? Enter [Cooperative AI](https://deepmind.com/research/publications/Open-Problems-in-Cooperative-AI). 
#### Cooperative AI
Cooperative AI is a class of problems within artificial intelligence that seek to use AI to solve or contribute to solving problems of cooperation. This research is focused on (1) Building AI with the capability to cooperate and (2) Creating AI that can be used to foster cooperation in populations (both machine and human).

Humanity’s success largely depends on our ability to cooperate with another, if AI can one day be used to improve cooperation between humans this could lead to incredible advancements in human progress and the mitigation of human suffering. 

AI could be used to supercharge humanity’s superpower—large scale cooperation. Given this framework, it is not farfetched to imagine AI being used to help negotiate peace treaties, creating more robust and fair forms of government, or helping humans cooperate with one another to avoid existential disasters (climate change, pandemics, nuclear holocaust). In fact, this kind of research already exists, recently the multi-agent system framework was used to [design tax policy](https://blog.einstein.ai/the-ai-economist/). 

Multi Agent Reinforcement Learning along with other disciplines (game theory, natural language processing, multi agent design, etc.) are the tools that will be leveraged to solve these problems that exist in Cooperative AI. Here is another example of [research](https://deepmind.com/blog/article/understanding-agent-cooperation) being conducted on this class of problems within the framework of MARL. 
#### Want to learn more?
If you’re interested in learning more about Cooperative AI, I’d recommend reading [Open Problems in Cooperative AI](https://deepmind.com/research/publications/Open-Problems-in-Cooperative-AI). Have I convinced to start poking around in MARL? This [github repo](https://github.com/LantaoYu/MARL-Papers) provides a nice collection of MARL research papers. Drooling at the mouth to conduct your very own MARL experiments? Check out [PettingZoo](https://www.pettingzoo.ml/)!

References

[1]: Y. Harari, [Sapiens](https://www.ynharari.com/book/sapiens-2/) (2015)

[2]: Allan Dafoe and Edward Hughes and Yoram Bachrach and Tantum Collins and Kevin R. McKee and Joel Z. Leibo and Kate Larson and Thore Graepel, Open Problems in Cooperative AI (2020), <https://arxiv.org/abs/2012.08630>

[3]: Improbable AI. (2021, April 12). CSL seminar: Jakob Foerster​​ [Video]. YouTube. <https://www.youtube.com/watch?v=ii_SwIsY8aU&ab_channel=ImprobableAI>

[4]: P. Barekatin, <https://www.quora.com/What-is-multi-agent-reinforcement-learning>



