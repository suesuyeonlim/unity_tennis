# Udacity - Deep Reinforcement Learning Nanodegree (Continuous Control)


## Project Description
This project involves working with the Reacher environment. In this environment, a double-jointed arm can move to target locations. There are 1,000 time steps and a reward of +0.1 is provided for each step that the agent's hand is in the goal location. Thus, the goal of the agent is to maintain its position at the target location for as many time steps as possible.

The observation space consists of 33 variables corresponding to position, rotation, velocity, and angular velocities of the arm. Each action is a vector with four numbers, corresponding to torque applicable to two joints. Every entry in the action vector should be a number between -1 and 1.

![43851024-320ba930-9aff-11e8-8493-ee547c6af349 (1)](https://user-images.githubusercontent.com/19903898/179446479-29bb5eea-5812-4110-9030-db56188c3369.gif)

The assignment is to train a single agent to get an average score of 30+ over 100 consecutive episodes.


## Requirements to Run the Code in Repository
In order to prepare the environment, follow the next steps after downloading this repository:

Download the environment from one of the links below. You need only select the environment that matches your operating system:

- Linux: click [here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Linux.zip)
- Mac OSX: click [here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher.app.zip)
- Windows (32-bit): click [here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Windows_x86.zip)
- Windows (64-bit): click [here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Windows_x86_64.zip)

Place the file in the reacher_ddpg/ folder, and unzip (or decompress) the file.

In a terminal or command window, navigate to the top-level project directory reacher_ddpg/ (that contains this README) and run the following command:

```
$ jupyter notebook
```
This will open the Jupyter Notebook software and notebook in your browser which you can use to explore and reproduce the experiments that have been run.

## Code and Resources
- report.pdf: A document that describes the details of the implementation and things to explore in the future.
- Continuous_Control.ipynb: Training the agent using the DDPG algorithm.
- test.py: Entry point for testing the agent using the trained networks.
- dqn.pth, policy.pth: Model weights.
