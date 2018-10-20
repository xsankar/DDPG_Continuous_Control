[//]: # (Image References)

[image1]: https://user-images.githubusercontent.com/10624937/43851024-320ba930-9aff-11e8-8493-ee547c6af349.gif "Trained Agent"
[image2]: https://user-images.githubusercontent.com/10624937/43851646-d899bf20-9b00-11e8-858c-29b5c2c94ccc.png "Crawler"


# Reinforcement Learning : DDPG Algorithm : Continuous Control

### Introduction

Applying DDPG to the [Reacher](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Learning-Environment-Examples.md#reacher) environment.

![Trained Agent][image1]

In this environment, a double-jointed arm can move to target locations. A reward of +0.1 is provided for each step that the agent's hand is in the goal location. Thus, the goal of your agent is to maintain its position at the target location for as many time steps as possible.

The observation space consists of 33 variables corresponding to position, rotation, velocity, and angular velocities of the arm. Each action is a vector with four numbers, corresponding to torque applicable to two joints. Every entry in the action vector should be a number between -1 and 1.

The task is episodic, and in order to solve the environment,  the agent must get an average score of +30 over 100 consecutive episodes. 

### Getting Started

1. Clone this repository. I am running on mac, so the unity runtime environment (Reacher.app) is already in the repository

2. If you are running in Linux or windows, download the appropriate environment from one of the links below.  You need only select the environment that matches your operating system:

    - **_Version 1: One (1) Agent_**
        - Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Linux.zip)
        - Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher.app.zip)
        - Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Windows_x86.zip)
        - Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Windows_x86_64.zip)

2. Place the file in the `DDPG_Continuous-Control/` folder, and unzip (or decompress) the file. 

### Instructions

Follow the instructions in `DDPG_CC.ipynb` to get started. 

* One can run the iPython notebook & train the agent (slow) or 
* use the iPython notebook to run a saved model (fast) or 
* watch the two videos viz. `p2_cc_no_learning_02.m4v` and `p2_cc_after_learning_02.m4v` (fastest)

### Report

The `Report.pdf` has a summary of the algorithm, the implementation and the experimentation (network architecture, hyp=erparameter search et al)
