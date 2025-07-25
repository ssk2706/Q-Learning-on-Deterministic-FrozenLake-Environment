# Q-Learning-on-Deterministic-FrozenLake-Environment
Explores the application of the Q-learning algorithm over a deterministic 5x5 FrozenLake grid. The agent begins at top-left and must find its way to the bottom-right goal while avoiding holes that are placed immovably. Rewards are in place to encourage optimal path-following: +10 for target achievement, -5 for falling in the hole, and -1 per step.

This repository contains a Q-Learning implementation for the Deterministic 5x5 FrozenLake environment using OpenAI Gym. The agent learns to navigate from the start to the goal while avoiding holes using reinforcement learning techniques.

🧠 Project Overview
The goal is to train an agent using Q-Learning to solve a gridworld environment where:

+10 reward is given for reaching the goal.

-5 penalty for falling into a hole.

-1 penalty per step taken.

The project explores various Q-Learning hyperparameter strategies and evaluates their impact on learning performance and final policy.

📁 Contents
main.ipynb: Python notebook implementing and analyzing Q-Learning on FrozenLake.

Reinforcement Learning Assignment Report.pdf: Detailed report discussing experiment setup, analysis, and comparison of different strategies.

README.md: You're reading it!




🧪 Requirements
To run the notebook:

pip install numpy matplotlib gym

Note: This implementation uses FrozenLake-v1 from gym with is_slippery=False.

🚀 How to Run
Clone the repo:

git clone https://github.com/ssk2706/Q-Learning-on-Deterministic-FrozenLake-Environment

Launch the notebook:
jupyter notebook main.ipynb
Run cells to simulate training and visualize results.
