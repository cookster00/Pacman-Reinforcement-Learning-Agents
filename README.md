# Pacman Reinforcement Learning Agents

This repository contains implementations of reinforcement learning algorithms applied to the classic Pacman game and related environments. The project showcases how artificial intelligence can be trained to make optimal decisions through methods like value iteration and Q-learning.

## Features

- **Value Iteration**: Computes an optimal policy by iterating over states and actions to maximize rewards.
- **Q-Learning**: Enables agents to learn an optimal policy through exploration and updating action-value pairs based on rewards.
- **Test Environments**:
  - **Gridworld**: A grid-based environment for testing fundamental reinforcement learning concepts.
  - **Crawler**: Simulates a simple robotic movement problem.
  - **Pacman**: The ultimate challenge where agents navigate a maze, collect rewards, and avoid ghosts.

## Table of Contents

- [Getting Started](#getting-started)
- [Installation](#installation)
- [How It Works](#how-it-works)
- [Results](#results)
- [Technologies Used](#technologies-used)
- [License](#license)

---

## Getting Started

These instructions will help you set up the project and explore the results.

### Prerequisites

- Python 3.7+
- Required Python libraries (see `requirements.txt`)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/pacman-rl-agents.git
   cd pacman-rl-agents
Install dependencies:
 - pip install -r requirements.txt
Run the project scripts (e.g., training or evaluation):
 - python pacman.py -p [AgentName] -l [LayoutName]


Reinforcement Learning Overview:
 - Value Iteration: Iteratively computes a value function for all states, enabling the agent to determine the best policy.
 - Q-Learning: A model-free approach where the agent learns by interacting with the environment and updating its Q-values based on observed rewards.

Code Structure:
 - pacman.py: Main game interface.
 - value_iteration.py: Implementation of the value iteration algorithm.
 - q_learning_agent.py: Q-learning agent implementation.
 - environments/: Contains configurations for Gridworld, Crawler, and Pacman environments.

Results:
 -Gridworld: Optimal policies successfully derived using value iteration.
 -Crawler: Demonstrated effective learning of robotic movement.
 -Pacman: Agents successfully navigated mazes, collected rewards, and avoided ghosts.

Technologies Used:
 -Programming Language: Python
 -Libraries: NumPy, Matplotlib (for visualizations)
 -Pacman Framework: Provided by the Berkeley AI Pacman project

Acknowledgements
This project was inspired by the Berkeley AI Pacman Project, a comprehensive resource for understanding AI in practice. Worked with Nickolas Johnson to produce this code for University of Oregon course CS 471 - Introduction to Artificial Intelligence.
