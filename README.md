# Udacity - Deep Reinforcement Learning Nanodegree (Continuous Control)


## Project Description
This project involves working with the Reacher environment. In this environment, a double-jointed arm can move to target locations. There are 1,000 time steps and a reward of +0.1 is provided for each step that the agent's hand is in the goal location. Thus, the goal of the agent is to maintain its position at the target location for as many time steps as possible.

The observation space consists of 33 variables corresponding to position, rotation, velocity, and angular velocities of the arm. Each action is a vector with four numbers, corresponding to torque applicable to two joints. Every entry in the action vector should be a number between -1 and 1.

![43851024-320ba930-9aff-11e8-8493-ee547c6af349 (1)](https://user-images.githubusercontent.com/19903898/179446479-29bb5eea-5812-4110-9030-db56188c3369.gif)

The assignment is to train a single agent or 20 agents in parallel to get an average score of 30+ over 100 consecutive episodes.


## Python Environment Set-Up
To set up your python environment to run the code in this repository, follow the instructions below.

1. Download and install [Anaconda](https://www.anaconda.com/download/), if you don't already have it.

2. Create (and activate) a new environment with Python 3.6.

- Linux or Mac:
  ```
  conda create --name drlnd python=3.6
  conda activate drlnd
  ```
- Windows:
  ```
  conda create --name drlnd python=3.6 
  activate drlnd
  ```

3. Clone the repository and navigate to the root folder.
  
  ```
  git clone https://github.com/suesuyeonlim/unity_reacher.git
  cd unity_reacher
  ```

## Requirements to Run the Code in Repository
In order to prepare the environment, follow the next steps after downloading this repository:

1. Download the environment from one of the links below. You need only select the environment that matches your operating system:

Version 1: One (1) Agent
  - Linux: click [here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Linux.zip)
  - Mac OSX: click [here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher.app.zip)
  - Windows (32-bit): click [here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Windows_x86.zip)
  - Windows (64-bit): click [here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/one_agent/Reacher_Windows_x86_64.zip)

Version 2: Twenty (20) Agents
  - Linux: click [here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher_Linux.zip)
  - Mac OSX: click [here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher.app.zip)
  - Windows (32-bit): click [here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher_Windows_x86.zip)
  - Windows (64-bit): click [here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P2/Reacher/Reacher_Windows_x86_64.zip)
  
Place the file in the unity_reacher/reacher_apps/ folder, and unzip (or decompress) the file(s).

2. To install the mlagents Python package, run from the command line:
  
  ```
  python -m pip install mlagents==0.28.0
  ```
3. Install the following packages:
  
  - Numpy
  - Torch
  - Random
  - Copy
  - Collections

4. Run the following command:

  ```
  $ jupyter notebook
  ```
  
  This will open the Jupyter Notebook software and notebook in your browser which you can use to explore and reproduce the experiments that have been run.

## Code and Resources
- Report.pdf: A document that describes the results, details of the implementation, and things future ideas.
- ppo_solutions: A folder that contains the PPO code and trained model weights.
- ddpg_solutions: A folder that contains the DDPG code and trained model weights.
