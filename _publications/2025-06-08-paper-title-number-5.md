---
title: "Model-Agnostic Meta-Learning with Open-Ended Reinforcement Learning"
collection: publications
category: conferences
permalink: /publication/2024-12-01-finalpaper
#excerpt: ''
date: 2024-12-01
venue: 'Intrinsically Motivated Open-ended Learning Workshop - NeurIPS Conference'
paperurl: 'http://ayashabbar.github.io/files/finalpaper.pdf'
citation: 'Shabbar, Aya. (2024). Model-Agnostic Meta-Learning with Open-Ended Reinforcement Learning'
---

This paper is an in-progress research that builds on the Open-Ended Reinforcement Learning with Neural Reward Functions proposed by Meier and Mujika [1] which use reward functions encoded by neural networks. One key limitation of their paper is the necessity of re-learning for each new skill learned by the agent. Consequently, we propose integrating meta-learning algorithms to tackle this problem. We, therefore, study the use of MAML, Model-Agnostic Meta Learning that we believe could make policy learning more efficient. MAML operates by learning an initialization of the model parameters that can be fine-tuned with a small number of examples from a new task which allows for rapid adaptation to new tasks.
