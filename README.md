# CS-370

# PROJECT OVERVIEW

This project features a deep Q-learning agent, known as the pirate, which explores an 8x8 maze in search of treasure before the game concludes. The maze setup and experience replay system were already in place, and the main goal was to finish the Deep Q-Learning training algorithm, enabling the pirate to discover the best route to the treasure by balancing exploration and exploitation.

# Code I Was Given

- I received the TreasureMaze.py code, which outlines the maze environment and its rules. It includes methods like reset(), act(), observe(), and valid_actions() to help simulate the environment.
- I also received the GameExperience.py code, which sets up an experience replay buffer to keep episodes for training.
- Finally, I received the Jupyter Notebook Starter code. This code helped in loading the maze, visualizing the state, and constructing the deep learning model. There were also helper functions like play_game() and completion_check() to assess how well the agent performed. Additionally, it features a partial outline of the qtrain() function, complete with pseudocode and TODO sections for putting the Q-learning logic into action.

# Code I Wrote

- I set up and finished the Deep Q-Learning Training (qtrain function) logic for randomly picking a starting position. I used epsilon-greedy exploration/exploitation to choose actions. I also recorded episodes into the experience replay buffer. The neural network is trained using batches from the replay memory. Plus, I kept an eye on the win rate, losses, and stopping criteria.
- I finished up the hyperparameter tuning too. I tweaked values such as epsilon, learning rate, and replay batch sizes to boost convergence speed and stability.
- At last, I made some debugging and output enhancements. I included logs for epochs, losses, and win rates to keep a closer eye on how the agent is doing.

# What Computer Scientists Do

- Computer scientists tackle intricate issues by creating smart systems that can learn from data, make predictions or decisions, and automate complicated tasks. This project reflects real-world uses such as robotics navigation, path planning for delivery systems, and game AI for adaptive, challenging opponents.

# Problem Solving Approach

- As a computer scientist, I tackled this issue by breaking it down. I started by getting a grip on the environment and replay memory. I implemented the Q-learning loop gradually, step by step. While testing and fine-tuning, I adjusted hyperparameters such as learning rate, epsilon decay, and batch sizes to ensure stable training. In analyzing the results, I utilized logs and visualizations to verify that the agent was making progress.

# Ethical Responsibilities

- Computer scientists carry a lot of ethical responsibilities. For the end user, they make sure systems are reliable, fair, and safe. They should steer clear of making biased or unsafe agents. For the organization, they create efficient, maintainable, and transparent systems. It's important to document code clearly so that others can replicate or audit the results. For society, they use AI in a responsible way, understanding how autonomous systems affect human life.
