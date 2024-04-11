# Reinforcement Learning Snake Game

This repository contains a reinforcement learning model designed to excel at the traditional Snake game.

## Overview

This project demonstrates the application of reinforcement learning for guiding an agent through a simplified gaming scenario. The agent, symbolized as the snake, incrementally learns to maximize rewards (by consuming food) and minimize penalties (by avoiding collisions with the game boundaries or itself).

## Getting Started

### Repository Cloning

```
git clone
```

### Dependency Installation

```
pip install -r requirements.txt
```

### Execution

```
python snakeagent.py
```

## Repository Structure

- **snakegame.py**: Manages the game environment for Snake, incorporating rules and how rewards are calculated.
- **snakemodel.py**: Designs the neural network and manages the training regimen via Deep Q-Learning.
- **snakeagent.py**: Builds and operates the reinforcement learning agent.
- **snakeplot.py**: Generates visual plots to illustrate the agent's progress during training.

## Usage Details

Running the `snakeagent.py` script will open two windows:

- The primary window showcases the Snake game, where the agent autonomously navigates and learns about its surroundings.
- A secondary window displays graphs charting the agent's scores and their average over time.

It's important to note that the agent might take about 5 to 10 minutes to start performing well in terms of scoring.

## Contact

For any questions, please contact: vinayk.posina@gmail.com
