---
title: "Reward-Free Reinforcement Learning with GNN and Adversarial Linear Mixture MDPs"
collection: publications
category: conferences
permalink: /publication/2024-06-14-My_Paper_7
#excerpt: ''
date: 2024-06-14
venue: 'European Workshop on Reinforcement Learning'
paperurl: 'http://ayashabbar.github.io/files/My_Paper_7.pdf'
citation: 'Shabbar, Aya. (2024). Reward-Free Reinforcement Learning with GNN and Adversarial Linear Mixture MDPs'
---

Reward-free RL is independently developed in the unconstrained literature, which learns the transition dynamics without using 
the reward information and is thus naturally capable of addressing RL with multiple objectives under the common dynamics. This paper proposes a new framework for the reward-free RL setting with function approximation i.e. the adversarial linear mixture MDPs. As Jin, et al. (2020). We partition this setting into an exploration phase and a planning phase. During the exploration phase, the agent first collects trajectories from an MDP without a pre-specified reward function. Using the Graph Neural Networks (GNNs) to store the significant states in dataset D instead of all states, each with a heuristic weight. In the planning phase, it is tasked with computing near-optimal policies under M for a collection of given reward functions. The agent generalizes previously learned information using the linear mixture MDPs that allows it to approximate the policy given an arbitrary reward function.