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
1. Install Unity ML
https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Installation.md

2. Download the Unity ML environment from one of the links below based on your OS:
    - Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip)
    - Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip)
    - Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip)
    - Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip)

Then unzip the file and place the file in this folder.

3. Create Conda Environment   

Install conda from conda.io. Create a new Conda environment with Python 3.6.

```bash
conda create --name deeprl python=3.6
source activate deeprl
```

4. Install Dependencies
```bash
cd python
pip install .
```


## How to run the agent
To start training, simply open *Navigation.ipynb* in Jupyter Notebook and follow the instructions there:

Start Jupyter Notebook
```bash
jupyter notebook
```
Trained model weights is included for quickly running the agent and see the result in Unity ML Agent.
Simply skip the training step and run the last step of the *Navigation.ipynb*
