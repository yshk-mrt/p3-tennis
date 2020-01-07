# Project 3: Collaboration and Competition - Tennis

### Introduction

This project aimed at solving [Collaboration and Competition project at Udacity/Deep-Reinforcement-Learning](https://github.com/udacity/deep-reinforcement-learning/tree/master/p3_collab-compet).

The objective of the project is to train two agents control rackets to bounce a ball over a net as many times as possible. 

![Trained_agent](./results/final/tennis.gif?raw=true "Trained Agents")

If an agent hits the ball over the net, it receives a reward of +0.1. If an agent lets a ball hit the ground or hits the ball out of bounds, it receives a reward of -0.01.

The observation space consists of 8 variables corresponding to the position and velocity of the ball and racket. Two continuous actions are available, corresponding to movement toward (or away from) the net, and jumping.

### Getting Started

1. To setup the basic environment, please follow the instruction below.
 - https://github.com/udacity/deep-reinforcement-learning/blob/master/README.md
 - https://github.com/udacity/deep-reinforcement-learning/blob/master/p3_collab-compet/README.md

2. After you can successfully run [Tennis.ipynb](https://github.com/udacity/deep-reinforcement-learning/blob/master/p3_collab-compet/Tennis.ipynb) on your environment, clone the repository.

3. Copy the Reacher.app file at `p3_collab-compet/` into the `p3_tennis` folder. 

### Instructions

- [`TrainAgent.ipynb`](./TrainAgent.ipynb) trains agent and see the behavior of the trained agent.
- [`Report.ipynb`](./Report.ipynb) describes detailes of trained models, results and future ideas.