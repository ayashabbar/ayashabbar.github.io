---
title: "Generative Adversarial Skill Estimation in Opponent Modeling"
collection: publications
category: conferences
permalink: /publication/2024-05-17-My_Paper2
#excerpt: ''
date: 2024-05-31
venue: 'Training Agents with Foundation Models Workshop - RL Conference'
paperurl: 'http://ayashabbar.github.io/files/My_Paper2.pdf'
citation: 'Shabbar, Aya. (2024). Generative Adversarial Skill Estimation in Opponent Modeling'
---

In opponent modeling, data about failed actions and models of opponent capabilities can be mined to improve estimates of the strategy gradient and the reliability and stochasticity of certain actions for the given opponent. We want our opponent modeling systems to reason similarly not only about what the opponent plans to do, but also about their probability of success should they choose a given action. The problem of skill estimation (Archibald and Nieves-Rivera, 2018) is closely related, and Bayesian techniques have been proposed for simulated, real-valued games including darts and billiards (Archibald and Nieves-Rivera, 2019). In this paper, I propose a novel method called generative adversarial skill estimation (GASE) to encourage the estimation and the probability of success in RL opponent modeling via introducing an intrinsic reward output from a foundation model generative adversarial network, where the generator provides fake samples of the opponent’s actions that help discriminator to identify those failed actions with their probability of success. Thus the agent can identify failed actions that the discriminator is less confident to judge as successful. This work is mainly motivated by the question: How can FMs be used for skill discovery?