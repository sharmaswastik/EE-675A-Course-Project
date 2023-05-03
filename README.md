# EE 675A Course Project
 An implementation of the paper $RL^2$: Fast Reinforcement Learning via Slow Reinforcement Learning available [here](https://arxiv.org/pdf/1611.02779.pdf). We used GRUs to train our model, and the policy is optimized using the vanilla policy gradient algorithm (REINFORCE). The RNN agent is trained with 20,000 instances of bandit environments each lasting for 100 episodes. We also test the performance of our said model with other State of the Art algorithms available, and found that the algorithm sufferes from high dimensionality of the problem.

 ## To reproduce the results following dependencies are required:
1. torch
2. numpy
3. matplotlib
4. gym


