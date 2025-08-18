---
title: "Reward-Free Deep-Learning-Based Reinforcement Learning"
collection: publications
category: conferences
permalink: /publication/2025-06-04-my_paper_7
#excerpt: ''
date: 2025-06-04
venue: 'European Workshop on Reinforcement Learning'
paperurl: 'http://ayashabbar.github.io/files/my_paper_7.pdf'
citation: 'Shabbar, Aya. (2024). Reward-Free Deep-Learning-Based Reinforcement Learning'
---

Exploration is widely regarded as one of the most challenging aspects of reinforcement learning (RL). We consider the reward-free RL problem, which operates in two phases: an exploration phase, where the agent gathers exploration trajectories over episodes irrespective of any predetermined reward function, and a subsequent planning phase, where a reward function is introduced. The agent then utilizes the episodes from the exploration phase to calculate a near-optimal policy. Existing algorithms and sample complexities for reward-free RL are limited to tabular, linear, or very smooth function approximations, leaving the problem largely open for more general cases. We consider deep-learning-based function approximations, i.e. DQNs, and propose an algorithm based on internal feedback and the agent’s own confidence and self-certainty in a graph MDP