The Taxi-v3 environment simulates a simple grid world where an agent (a taxi) must pick up a passenger at one location and drop them off at a destination. The environment is a 5x5 grid, and the taxi can move in four directions (north, south, east, west), pick up a passenger, and drop off the passenger.
Each episode starts with the taxi in a random position, a passenger at a random location, and a random destination. The agent receives a small negative reward (-1) for every time step to encourage faster solutions, a positive reward (+20) for a successful drop-off, and a penalty (-10) for illegal actions (like trying to pick up a passenger who isn't there).
The episode ends once the passenger has been successfully dropped off at the correct destination.

TAXI PROBLEM - REINFORCEMENT LEARNING (DP & MONTE CARLO)
This project includes two Jupyter Notebooks that solve the classic Taxi-v3 problem using Reinforcement Learning techniques. The Taxi problem is a standard environment in OpenAI Gym designed to teach the fundamentals of RL including MDPs, value functions, and policy learning.
FILES:
taxi_problem_dp.ipynb
Uses Dynamic Programming (DP) methods:
Policy Evaluation
Policy Improvement
Policy Iteration
Value Iteration
Suitable when the model of the environment (transition and reward functions) is fully known
taxi_problem_monte_carlo.ipynb
Uses Monte Carlo (MC) Control techniques:
First-Visit / Every-Visit MC Prediction
Epsilon-Greedy Action Selection
On-policy Monte Carlo Updates
Ideal for model-free environments where learning is based on sampling episodes.
REQUIREMENTS:
Python 3.7 or higher
Jupyter Notebook or Jupyter Lab
gymnasium or gym
numpy
matplotlib (optional, for visualizations)
To install required libraries:
pip install gymnasium numpy matplotlib
OBJECTIVE:
Compare and understand the performance of model-based (DP) vs model-free (MC) reinforcement learning methods in solving a simple MDP like the Taxi problem.
TOPICS COVERED:
Markov Decision Processes (MDP)
Bellman Equations
Value Function Estimation
Policy Iteration and Value Iteration
Monte Carlo Sampling
Epsilon-Greedy Exploration Strategy
Episode-Based Learning
OUTPUTS:
Learned policies
Converged value functions
Optional visualizations of the learning process
AUTHOR:
Asl1dd1n Choriev - AI Engineer 
LICENSE:
This project is free to use for educational and personal learning purposes. Feel free to modify and extend it.
