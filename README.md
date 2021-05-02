# Reinforcement Learning - Policy Methods

## Cross Entropy

This repository is an exmaple implementation of cross entropy algorithm that can be used for Reinforcement Learning Policy Method.

## Background

The idea is to create a neural network but instead of using backpropogation, at each iteration, generate 50 new weights that are close to the current weights, evaluate the agent on these 50 weights, take the best 10 weights out of these 50 and use the mean of the best 10 weights as weights for the neural network for the next iteration.

Keep doing this till the environment is solved.

