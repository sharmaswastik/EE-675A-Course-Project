# EE 675A Course Project
 An implementation of the paper $RL^2$: Fast Reinforcement Learning via Slow Reinforcement Learning is available [here](https://arxiv.org/pdf/1611.02779.pdf). We used GRUs to train our model, and the policy is optimized using a simple actor-critic algorithm, with the actor being the RNN agent and the baseline/critic network being a simple MLP. The RNN agent is trained with 20,000 instances of bandit environments each lasting for different number of episodes. We also test the performance of our said model with other State of the Art algorithms available, and found that the algorithm sufferes with increasing dimensionality of the problem.

 ## To reproduce the results following dependencies are required:
1. torch
2. numpy
3. matplotlib
4. gym


