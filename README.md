# Deep Reinforcement Learning on Navigation

## Introduction
This repository contains a simple Deep Q-Network (DQN) agent running in Unity ML Agent that can be used to train
and evaluate the result of the training.

I created this for the purpose of learning the basic of Deep Q-Network (DQN).

The DQN is implemented in Python 3 using PyTorch.

### Environment
The agent will navigate in a 3D world created in Unity ML where there are yellow bananas and blue bananas.

### Goal
The goal is to train an DQN agent to navigate and collect as many yellow bananas as possible in a large, square world.


### Rewards
* A reward of +1 will be provided for getting a yellow banana
* A reward of -1 will be provided for collecting a blue banana

### Actions
4 discreate actions are allowed:

    0 - move forward.
    1 - move backward.
    2 - turn left.
    3 - turn right.

### Spaces
The state space has 37 dimensions.

They contains:
    
    * the agent's velocity
    * ray-based perception of objects around agent's forward direction


## Getting Started
1. Download the environment from one of the links below.  You need only select the environment that matches your operating system:
    - Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip)
    - Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip)
    - Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip)
    - Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip)

2. Install Dependencies


## How to run the agent
Trained model weights is included for quickly running the agent and see the result in Unity ML Agent.

To start from training, simply open Navigation.ipynb in Jupyter Notebook and follow the instructions there.
