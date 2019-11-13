# Readme

##  Continuous Control - Deep Reinforcement Learning

### Udacity - Nanodegree Program

### 1. Introduction

The code contained in the ```Continuous-Control.ipynb``` file trains an agent representing a mechanical arm that keeps the end of the arm on a tagert sphere as much time as possible. A reward of +0.1 is provided for each step that the agent's hand is in the goal location. The Unity Reacher Environment is used.

The observation space consists of 33 variables corresponding to position, rotation, velocity, and angular velocities of the arm. Each action is a vector with four numbers, corresponding to torque applicable to two joints. Every entry in the action vector should be a number between -1 and 1.

The training is performed on ```n_episodes = 5000``` and is interrupted if the mean average score is equal or greater than 30.0 

### 2. Getting Started

The following packages are necessary to run the code:
- ```UnityEnvironment```. The executable file of the environment is available at (for Windows x64): https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Windows_x86_64.zip.
- ```gym```
- ```matplotlib```
- ```numpy```
- ```torch```
- ```collections```

The following files are necessary to run the code:
- ```model.py```
- ```ddpg_agent.py```

### 3. Instructions

In order to run the code, execute the steps provided on the ```Continuous-Control.ipynb``` notebook

### 4. More about the method

The ```Report.md``` contains more information about the deep deterministic policy gradient method.

