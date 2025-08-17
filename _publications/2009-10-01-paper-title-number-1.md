---
title: "Generative-Discriminative Mean Field Distribution Approximation in Multi-agent Reinforcement Learning"
collection: publications
category: conferences
permalink: /publication/2024-05-17-My_Paper_3
#excerpt: ''
date: 2024-05-17
venue: 'Coordination and Cooperation in Multi-Agent Reinforcement Learning Workshop - RL Conference'
paperurl: 'http://ayashabbar.github.io/files/My_Paper_3.pdf'
citation: 'Shabbar, Aya. (2024). Generative-Discriminative Mean Field Distribution Approximation in Multi-agent Reinforcement Learning'
---

Non-cooperative and cooperative games with a very large number of players remain generally intractable when the number of players increases. Introduced by Lasry and Lions (2007) and Huang et al. (2006), Mean Field Games (MFGs) rely on a mean-field approximation to allow the number of players to grow to infinity. In Mean-field reinforcement learning, When the state space is finite but very large storing the population distribution in a tabular way for every state and computing the evolution of this distribution in an exact way is prohibitive in terms of memory and computational time. In continuous spaces, representing and updating the distribution is even more challenging, even if it is just for the purpose of implementing the RL environment and not to use it as an input to the policies. In this case, one needs to rely on approximations. This research aims to propose a model-based reinforcement learning algorithm, GD-MFRL that efficiently represents the distribution using function approximation in a two-part generative and discriminative setting;
(i) one part learns to generate distributions by trial and error, and (ii) the other part tries to evaluate these distributions. The definition of such a framework requires answering several challenging research questions, including: How to evaluate the transfer quality in a Multiagent scenario?