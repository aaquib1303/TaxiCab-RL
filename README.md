#Project Description:

This project builds a Q-learning agent that learns to navigate a grid-based Taxi environment (Taxi-v3) using tabular Q-Learning. The agent learns to pick up and drop off passengers at the correct locations by maximizing long-term reward.
A grid search over the learning rate (alpha), discount factor (gamma), and exploration rate (epsilon) is used to find the best combination of hyperparameters. The agent trains over 1000 episodes, with rewards tracked per episode. After training, the agent is evaluated over several test episodes to calculate its success rate and render a demo run in text-based simulation.

