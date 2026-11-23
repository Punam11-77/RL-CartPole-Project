# RL-CartPole-Project

## Project overview
This project explores Reinforcement Learning (RL) using the CartPole balancing tasks. The main goal is to understand RL concepts and train an agent using PPO (Proximal Policy Optimization) algorithm.

## Progress Completed
### Day 1- Reinforcement Learning Fundamentals
• Studied RL loop
• Learned concepts of agents, environment, state, action and reward
• Reviewed cartpole as a RL example

### RL Loop
Reinforcement Learning (RL) is a type of machine learning where an agent learns by interacting with an environment. The agent observes the current situation, chooses an action, and receives a reward based on that action. The reward helps the agent understand whether its decision was good or bad. By repeating this process many times, the agent gradually learns how to achieve the best outcome.

The RL loop consists of four main components: the agent, environment, action, and reward. First, the agent observes the current state of the environment. Based on this information, it selects an action. The environment responds to the action and returns a reward along with a new state. This cycle continues until the task is completed or the episode ends.

A simple example is the CartPole balancing task. In this task, the agent controls a cart that can move left or right. The goal is to keep a pole balanced on top of the cart. If the pole remains upright, the agent receives a positive reward. If the pole falls, the episode ends. Through trial and error, the agent learns which actions help keep the pole balanced for the longest time
...

### Day 2- RL Algorithm
• Studied Q-learning, Deep Q-Networks (DQN)
• Studied Proximal policy optimization (PPO)
• Value based vs policy based algorithm
• Learned the role of policy networks

### RL Algorithm
Several reinforcement learning algorithms can be used to train an agent to make decisions. One of the simplest methods is Q-Learning, which stores expected rewards in a Q-table. The agent chooses actions based on these values and gradually learns the best action for each state. While Q-Learning works well for small problems, it becomes difficult to use when the number of possible states grows large.

Deep Q-Networks (DQN) improve upon Q-Learning by replacing the Q-table with a neural network. Instead of storing every state-action value directly, the network estimates them. This allows DQN to handle more complex environments with larger state spaces.

Proximal Policy Optimization (PPO) is a policy-based reinforcement learning algorithm and is widely used in robotics and control tasks. Unlike Q-Learning and DQN, PPO learns a policy directly rather than estimating action values. A policy network takes observations from the environment as input and determines which action should be taken. During training, the policy is updated using rewards received from the environment. PPO performs these updates gradually, which helps maintain stable learning and prevents large changes that could reduce performance.

PPO is commonly used for tasks such as robot control and balancing problems because of its stability and reliability. For the CartPole project, PPO is an appropriate choice because it can effectively learn how to keep the pole balanced through repeated interactions with the environment.
...

### Day 3- PPO and Policy networks
• Investigated PPO in more detail
• Studied policy networks and action selected
• Summary of RL concepts and algorithm comparison deliverable

### Day 4- Environment Setup
• Installed python 3.12
• Created virtual environment
• Installed Gymanasium
• Installed Stable-Baselines3
• Installed NumPy, Matplotlib, and Pygame
• Tested CartPole environment setup

## Structure

RL_CartPole_Project/
│
├── README.md          <- Main project documentation
├── docs/
│   ├── daily_log.md   <- Day-by-day progress
│   └── notes.md       <- Theory notes
│
├── src/
│   ├── test_cartpole.py
│   └── (future code files)
│
└── screenshots/


<img width="777" height="701" alt="image" src="https://github.com/user-attachments/assets/a5f90331-453d-49ca-aed1-286e7a5ac9ba" />


