# Reward Hacking in Reinforcement Learning

This project studies reward hacking and proxy misalignment in reinforcement learning using an Actor–Critic agent in the MiniGrid DoorKey environment.

## What this shows
- Agents can optimize proxy rewards without solving the true task
- Higher reward does not always imply correct behavior
- Misalignment can be detected and mitigated

## Approach
- A2C-style Actor–Critic with CNN-based observations
- Parallel environment rollouts
- Multiple proxy reward designs
- Correlation-based reward hacking detection
- Finish-only reward gating mitigation

## Experiments
- Compared true vs proxy reward across conditions
- Evaluated success rate, reward gap, and episode length
- Multi-seed evaluation for robustness

## Why this project
Built to explore failure modes in RL systems and understand how reward design affects learned behavior.

## Tech Stack
PyTorch, MiniGrid, Actor–Critic, Reinforcement Learning
