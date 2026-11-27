# project Daily Log

## Day 1 (4.5 h)
## Reinforcement Learning Fundamentals
•Studied the basics of Reinforcement Learning (RL).
•Learned the concepts of agent, environment, state, action, and reward.
•Explored how the RL loop works through interactions between an agent and an environment.
•Reviewed examples of RL applications and the CartPole balancing problem.
•Created notes summarizing key RL concepts.     

## Progress
Gained a foundational understanding of reinforcement learning and prepared notes for future implementation.
...

## Day 2 (3 h)
## RL Algorithm
•Studied Q-Learning and its use of Q-tables.
•Learned the limitations of Q-Learning in larger environments.
•Explored Deep Q-Networks (DQN) and how neural networks are used to estimate action values.
•Compared Q-Learning and DQN through personal notes and examples.

## Progress
Obtained an overview of value-based reinforcement learning algorithms and their practical use cases.
...
## Day 3 (3 h)
## PPO and Policy Networks
•Studied Proximal Policy Optimization (PPO).
•Learned how a policy network maps observations to actions.
•Compared PPO with Q-Learning and DQN.
•Reviewed why PPO is widely used in robotics and control tasks.
•Prepared notes focusing on PPO and policy-based learning.

## Progress
Developed a better understanding of PPO and its suitability for the CartPole balancing task.
...

## Day 4 (2.5 h)
## Development Environment Setup
• Python 3.12 for project compatibility.
•Created a virtual environment for the project.
•Configured PowerShell execution settings to activate the environment.
•Began installing required reinforcement learning libraries.

## Progress
Successfully prepared the project development environment for further implementation
...

## Day 5 (3,5 h)
## Library Installation and trouble shooting
•Installed Gymnasium.
•Installed Stable-Baselines3.
•Installed NumPy, Matplotlib, and PyGame.
•Verified package installation and environment setup.
•Attempted to install PyBullet.
•Investigated compatibility and build issues related to PyBullet installation.
•Explored alternative approaches to continue project development while troubleshooting PyBullet.

## Progress
Core reinforcement learning libraries have been installed successfully and the environment is ready for CartPole experimentation and PPO training.
...

## Day 6 (3 h)
## PPO Agent Training
•Created a PPO training script using Stable-Baselines3.
•Initialized the CartPole-v1 environment.
•Used the MlpPolicy neural network provided by Stable-Baselines3.
•Trained the agent for 10,000 timesteps.
•Observed training statistics and policy updates during execution.
•Saved the trained model for future testing and evaluation.

## Outcome
Successfully completed the first PPO training run and generated a trained CartPole agent capable of learning
from environment interactions.


## Day 7 (3 h)

<img width="808" height="458" alt="image" src="https://github.com/user-attachments/assets/b1bf4fc7-ab37-4ccc-9a12-5d4803ce7731" />

## PPO Training Evaluation
•Reviewed PPO training results.
•Analysed training statistics generated during learning.
•Investigated model loading and serialization issues.
•Verified that PPO training completed successfully.
•Continued experimentation with CartPole and Stable-Baselines3.

## Outcome
The PPO training workflow was successfully executed. Training metrics were produced and learning behaviour was observed. Further work is required to evaluate saved models.

<img width="595" height="618" alt="image" src="https://github.com/user-attachments/assets/80043770-937a-4606-8118-d2f7854ada58" />

## Status
Gymnasium-based CartPole environment has been successfully tested and PPO training has been completed. However, PyBullet-specific implementation tasks, including loading cartpole.urdf, joint-state access, and Pygame visualization, are still pending due to PyBullet installation issues. These tasks will be completed in the next phase of the project.

## PyBullet Setup
Successfully installed PyBullet.
Verified PyBullet installation using a connection test.
Confirmed that the PyBullet physics engine can be initialized successfully.

## getJointState() ra stepSimulation() successfully complete

<img width="623" height="588" alt="image" src="https://github.com/user-attachments/assets/1e2dae55-f7a0-44b3-8eb4-e84ed3c8a4ae" />


## PyGame Window run
<img width="1186" height="871" alt="image" src="https://github.com/user-attachments/assets/98412964-78e3-4eec-aa3a-726a02dcb3a0" />


## Day 7 (3 h)
Progress
Installed PyBullet and Pygame
Loaded cartpole.urdf using PyBullet DIRECT mode
Retrieved joint states with getJointState()
Advanced physics using stepSimulation()
Applied cart movement using velocity control
Created Pygame visualization
Implemented keyboard control (left/right)
Added scene reset functionality
Tested random-action demonstration

### Status: Completed





