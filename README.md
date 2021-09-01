# Deep-Learning-and-Reinforcement-Learning

# Deep-Learning 
A Deep Convolution Generative Adverserial Network (DCGAN) used to generate images. This model follows a similar architecture to the original DCGAN papers (https://arxiv.org/abs/1511.06434) guidelines for stable Deep Convolutional GANs.  
This training loop is based off the mini-batch stochastic gradient descent algorithm proposed in the original GAN paper (https://arxiv.org/abs/1406.2661)  
A brief report is provided. 

# Reinforcement Learning:  
A Deep Q Learning (DQN) agent including prioritized experience replay memory and a target network. The DQN uses a 4-frame stack of greyscale 84x84 images as states, to learn movement and accomodate efficient learning. The architecture and parameters are based off the original DQN paper, https://storage.googleapis.com/deepmind-media/dqn/DQNNaturePaper.pdf  
  A rank-based (prioritized) experience replay is used, first discussed in https://arxiv.org/abs/1511.05952  
Due to RAM restrictions on colab we use a 50000 buffer limit. Preferbly this would be larger. Preferbly we would train for much longer (>10mil frames)  
Code inspired by https://github.com/higgsfield/RL-Adventure/blob/master/4.prioritized%20dqn.ipynb
