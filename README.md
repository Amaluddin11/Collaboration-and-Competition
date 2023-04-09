# Collaboration-and-Competition
Udacity Deep Reinforcement Learning Project 3

### Introduction

For this project, you will work with the [Tennis](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Learning-Environment-Examples.md#tennis) environment.

In this environment, two agents control rackets to bounce a ball over a net. If an agent hits the ball over the net, it receives a reward of +0.1.  If an agent lets a ball hit the ground or hits the ball out of bounds, it receives a reward of -0.01.  Thus, the goal of each agent is to keep the ball in play.

The observation space consists of 8 variables corresponding to the position and velocity of the ball and racket. Each agent receives its own, local observation.  Two continuous actions are available, corresponding to movement toward (or away from) the net, and jumping. 

The task is episodic, and in order to solve the environment, your agents must get an average score of +0.5 (over 100 consecutive episodes, after taking the maximum over both agents). Specifically,

- After each episode, we add up the rewards that each agent received (without discounting), to get a score for each agent. This yields 2 (potentially different) scores. We then take the maximum of these 2 scores.
- This yields a single **score** for each episode.

The environment is considered solved, when the average (over 100 episodes) of those **scores** is at least +0.5.


# Instructions
Follow the instructions in Continuous_Control.ipynb to get started with training your the agent.

# License
This project is licensed under the MIT License - see the [**LICENSE**](https://opensource.org/license/mit-license-php/) file for details.

# Acknowledgments
This project was completed as part of the [**Udacity Deep Reinforcement Learning**](https://www.udacity.com/course/deep-reinforcement-learning-nanodegree--nd893) Nanodegree program.
