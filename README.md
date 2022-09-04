# Udacity - Deep Reinforcement Learning Nanodegree (Collaboration and Competition)


## Project Description
This project involves working with the Tennis environment. In this environment, two agents control rackets to bounce a ball over a net. If an agent hits the ball over the net, it receives a reward of +0.1. If an agent lets a ball hit the ground or hits the ball out of bounds, it receives a reward of -0.01. Thus, the goal of each agent is to keep the ball in play.

The observation space consists of 8 variables corresponding to the position and velocity of the ball and racket. Each agent receives its own, local observation. Two continuous actions are available, corresponding to movement toward (or away from) the net, and jumping.

Untrained

![Alt Text](https://media.giphy.com/media/paJEEd7bCXdDK7ebcB/giphy.gif)

Trained

![Alt Text](https://media.giphy.com/media/ttdcNRnXx8XZJSywmu/giphy.gif)

The assignment is to train agents to get an average score of 0.5 over 100 consecutive episodes.


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
  git clone https://github.com/suesuyeonlim/unity_tennis.git
  cd unity_tennis
  ```

## Requirements to Run the Code in Repository
In order to prepare the environment, follow the next steps after downloading this repository:

1. Download the environment from one of the links below. You need only select the environment that matches your operating system:

  - Linux: click [here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Linux.zip)
  - Mac OSX: click [here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis.app.zip)
  - Windows (32-bit): click [here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Windows_x86.zip)
  - Windows (64-bit): click [here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Windows_x86_64.zip)
  
Place the file in the unity_tennis/apps/ folder, and unzip (or decompress) the file(s).

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
- Report.ipynb: A document that describes the results, details of the implementation, and things future ideas.
- Play Example.ipynb: A document where you can see the play of the agents trained with a DDPG algorithm.
- MAPPO: A folder that contains the PPO code and trained model weights.
- MADDPG: A folder that contains the DDPG code and trained model weights.
