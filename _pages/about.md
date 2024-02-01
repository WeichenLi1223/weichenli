---
permalink: /
title: ""
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
🐻 About me
------
I am a third-year Ph.D. student in the Machine Learning group at the University of Kaiserslautern-Landau, supervised by Professor Sophie Fellenz. My research primarily focuses on language-based deep reinforcement learning.

🐣 Research Interests
======
1. <strong>Language-Based Reinforcement Learning</strong>:
Text-based adventure games are a popular testbed for language-based RL. In previous work, deep Q-learning is most often used as the learning agent. Q-learning algorithms are difficult to apply to complex real-world domains, for example, due to their instability in training. Therefore, we adapt the Soft-Actor-Critic (SAC) algorithm
to the domain of text-based adventure games in this paper. To deal with sparse extrinsic rewards from the environment, we combine the SAC with a potential-based reward shaping technique to provide more informative (dense) reward signals to the RL agent. The SAC method achieves higher scores than the Q-learning methods on many games with only half the
number of training steps. Additionally, the reward shaping technique helps the agent to learn the policy faster and improve the score for some games. Overall, our findings show that the SAC algorithm is a well-suited approach for text-based games.
2. <strong>Safety Reinforcement Learning</strong>: 
RL has demonstrated its potential in solving goal-oriented sequential tasks. However, with the increasing capabilities of RL agents, ensuring morally responsible agent behavior is becoming a pressing concern. Previous approaches have included moral considerations by statically assigning a moral score to each action at runtime. However, these methods do not account for the potential moral value of future states when evaluating immoral actions. This limits the ability to find trade-offs between different aspects of moral behavior and the utility of the action. In our paper, we aim to factor in moral scores by adding a constraint to the RL objective that is incorporated during training, thereby dynamically adapting the policy function. By combining Lagrangian optimization and meta-gradient learning, we develop an RL method that is able to find a trade-off between immoral behavior and performance in the decision-making process. 


🐥 Publications
======
1. W. Li, R. Devidze, W. Mustafa, and S. Fellenz.(2024) Ethics in Action: Training Reinforcement Learning Agent for Moral Decision-making In Text-based Adventure Games. (To appear)Proceedings of International Conference on Artificial Intelligence and Statistics (AISTATS)
2. W. Li, R. Devidze, S. Fellenz.(2023) [Learning to play text-based adventure games with maximum entropy reinforcement learning](https://arxiv.org/abs/2302.10720). European Conference on Machine Learning and Data Mining (ECML PKDD)  [code](https://github.com/WeichenLi1223/Text-based-adventure-games-using-SAC)
3. W. Li.et.al.(2022),[Topic-Guided Knowledge Graph Construction for Argument Mining](https://ieeexplore.ieee.org/document/9667720). IEEE International Conference on Big Knowledge(ICBK)



📝 Teaching 
======
I supervise Master projects and theses. Please reach out if you are interested in the following topics:
1. Playing text-based adventure games using offline Reinforcement Learning: This topic aims to train a single agent using collected game trajectories, instead of training a separate agent for each individual game with online data collection.
2. Language understanding: This topic aims to explain an agent's decision-making process by investigating why it chooses a particular action a1 over a2 in a specific state and its ability to learn from semantic information.
3. Deep Reinforcement learning with application to chemical data. 
