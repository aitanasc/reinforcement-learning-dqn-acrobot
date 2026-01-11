# Reinforcement Learning with DQN (Acrobot)

## Goal
Train a Deep Q-Network (DQN) agent to solve the Acrobot-v1 environment and analyze how different hyperparameters affect learning performance and stability.

## Context
Reinforcement learning systems are highly sensitive to hyperparameter choices. This project focuses not only on training an agent, but on understanding how design decisions influence convergence, stability, and overall behavior.

## What I did
- Implemented a DQN agent for the Acrobot-v1 environment
- Tested multiple hyperparameter configurations (learning rate, batch size, memory size, target network update frequency)
- Fixed random seeds to ensure fair and reproducible comparisons
- Monitored reward evolution and training stability across experiments

## Key findings
- Smaller learning rates generally led to more stable learning
- Target network update frequency had a strong impact on convergence
- Some configurations achieved higher rewards but were less stable over time
- Stability and performance do not always improve together

## What this project shows
- Solid understanding of reinforcement learning fundamentals
- Ability to design controlled experiments
- Critical analysis of model behavior, not just final rewards
- Experience working with non-trivial training dynamics

## Possible next steps
- Implement Double DQN
- Compare results with policy-based methods (e.g. PPO)
- Improve evaluation metrics for stability analysis
