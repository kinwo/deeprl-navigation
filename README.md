# Deep Reinforcement Learning on Navigation

## Introduction
This repository contains a simple Deep Q-Network (DQN) agent running in Unity ML Agent that can be used to train
and evaluate the result of the training.

I created this for the purpose of learning the basic of creating Deep Q-Network (DQN).

### Goal
The goal is to train an DQN agent to navigate and collect as many yellow bananas as possible in a large, square world.

### Environment
The agent will naviate in a 3D world created in Unity ML where there are yellow bananas and blue bananas.

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


## How to run the agent
