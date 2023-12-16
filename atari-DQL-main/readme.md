# Atari Deep Reinforcement Learning Agent

![Trained Agent Video](pong.gif)
![Trained Agent Video](breakout.gif)

This repository contains code for training and testing an Atari reinforcement learning agent based on [Deepminds orignal paper](https://arxiv.org/pdf/1312.5602.pdf), modified to use the [Double Deep Q-Network algorithm](https://arxiv.org/pdf/1509.06461.pdf). The agent is capable of learning to play various Atari games provided by the Gymnasium environment. Pytorch is used for the Deep Q-Networks, with tensorboard to display training metrics.

## Overview

The Atari reinforcement learning agent is implemented using PyTorch and Gymnasium, and it follows the DQN algorithm. The agent learns to play Atari games by interacting with the environment, storing experiences in a replay memory, and optimizing its Q-network.

The codebase includes the following components:

- `dqn.py`: Definition of the Deep Q-Network (DQN) model.
- `replay_memory.py`: Implementation of the replay memory for storing and sampling experiences.
- `agent.py`: The main Atari agent class that encapsulates the training and testing logic.
- `train.py`: Script for training the agent.
- `test.py`: Script for testing the trained agent.
- `utils.py`: Utility functions for preprocessing observations and other tasks.
- `videos/`: A directory where recorded videos of the trained agent's gameplay are saved.

