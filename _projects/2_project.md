---
layout: page
title: Double Deep Q-Learning Robocode Agent
description: Reinforcement learning agent using DDQN for autonomous robot combat in Robocode environment
img: assets/img/3.jpg
importance: 2
category: AI
---

## Project Overview

This project implements a **Double Deep Q-Learning (DDQN)** agent for the Robocode environment, developed as part of a Deep Reinforcement Learning course. The agent learns autonomous combat strategies through trial-and-error interactions with the game environment, demonstrating the power of deep reinforcement learning in complex, real-time decision-making scenarios.

## Methodology

### Double Deep Q-Network (DDQN) Architecture

The project employs DDQN to address the overestimation bias inherent in standard DQN algorithms. The architecture consists of:

- **Primary Network**: Selects actions based on current state
- **Target Network**: Evaluates the Q-values for selected actions
- **Experience Replay Buffer**: Stores and samples past experiences for training
- **ε-greedy Exploration**: Balances exploration vs exploitation during training

### State Representation

The agent's state space includes:
- Robot position (x, y coordinates)
- Robot heading and velocity
- Enemy robot positions and movements
- Radar and gun bearings
- Energy levels (self and enemies)
- Battlefield boundaries and obstacles

### Action Space

The agent can perform the following actions:
- Move forward/backward
- Turn left/right
- Rotate gun left/right
- Fire bullets (different power levels)
- Scan for enemies
