# Rainbow

This repository implements the deep reinforcement learning algorithm called **Rainbow** first developed by Deepmind. It works on both 1D and 3D inputs automatically switching between a dense or convolutional Q-network interfering the input shape. It is also possible to define a personalized input preprocessing function so to be compatible to all of the gym simulated environments and even user defined environments. **Pytorch** and **gym** need to be installed in order to run this model. Moreover, each model's component can be disabled so to compare different architectures. At present time, have been implemented the following architectures:
- DQN [[link]](https://www.cs.toronto.edu/~vmnih/docs/dqn.pdf)
- Double DQN (DDQN) [[link]](https://www.cs.toronto.edu/~vmnih/docs/dqn.pdf)
- Dueling network [[link]](https://arxiv.org/abs/1511.06581)
- Prioritized experience replay (PER) [[link]](https://arxiv.org/abs/1511.05952)
- N-Step learning [[link]](https://arxiv.org/abs/1901.07510)
- Noisy network [[link]](https://arxiv.org/abs/1706.10295)
- Categorical distribution [[link]](https://arxiv.org/pdf/1710.10044.pdf)
- Rainbow [[link]](https://arxiv.org/abs/1710.02298)

### References
- https://github.com/Curt-Park/rainbow-is-all-you-need
- https://github.com/facebookresearch/minihack
