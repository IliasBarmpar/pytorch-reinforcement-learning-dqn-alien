# Reinforcement Learning Agent for AlienDeterministic-v4 Environment

This repository contains a Python implementation of a reinforcement learning agent designed to learn and play the AlienDeterministic-v4 game environment using Deep Q-Networks (DQN), Prioritized Replay Buffer, and Intrinsic Curiosity Module (ICM).

## Contents

- [Introduction](#introduction)
- [Setup](#setup)
- [Components](#components)
- [Usage](#usage)
- [Results](#results)

## Introduction

The goal of this project is to develop a reinforcement learning agent that can learn to play the AlienDeterministic-v4 game using the DQN algorithm, with optional enhancements such as Prioritized Replay Buffer and the Intrinsic Curiosity Module (ICM).

The code includes implementations of various components such as Q-Network architecture, Replay Buffers, Prioritized Replay Buffers, ICM, and an agent that interacts with the environment and learns over episodes.

## Components

The main components implemented in this code include:
- QNetwork: A neural network architecture used to approximate the Q-values of states.
- Replay Buffer: A class for storing experiences for experience replay during training.
- Prioritized Replay Buffer: An extension of the Replay Buffer that prioritizes experiences based on their TD errors.
- Intrinsic Curiosity Module (ICM): A framework for incorporating intrinsic reward signals to encourage exploration.
- Agent: An agent class that interacts with the environment, performs actions, and learns using the chosen algorithm.



## Results

After training the agent, the provided code generates a graph showing the scores achieved over episodes. These scores represent the performance of the agent in the environment, illustrating how well it has learned to play the game.

Feel free to modify hyperparameters, experiment with different components, and observe how they affect the agent's learning and performance!

