# DQN_LunarLander
The goal of this project is to implement and compare two reinforcement learning algorithms, DQN and DDQN, for solving the LunarLander problem.
# 
•  Q-learning is a popular algorithm in RL that learns a value function, called Q-function, that estimates the expected future reward for each state-action pair. The agent follows an epsilon-greedy policy that explores new actions with some probability and exploits the best action according to the Q-function with the remaining probability. The Q-function is updated using the Bellman equation, which expresses the optimal value as the sum of the immediate reward and the discounted value of the next state.

•  Deep neural networks are powerful function approximators that can learn complex nonlinear mappings from inputs to outputs. They consist of multiple layers of neurons that apply activation functions and weights to the inputs. They are trained using gradient descent and backpropagation algorithms that minimize a loss function.

•  Experience replay is a technique that improves the stability and efficiency of Q-learning by storing the agent's experiences (state, action, reward, next state, done) in a memory buffer and sampling mini-batches of experiences to update the Q-function. This reduces the correlation and variance of the samples and allows for multiple updates from a single experience.
# environment
![101](https://github.com/mamad-hosn/DQN_LunarLander/assets/90955072/09f6ff02-886a-40f1-af7a-0c02528c0426)
![102](https://github.com/mamad-hosn/DQN_LunarLander/assets/90955072/5c902d3e-487c-47c1-80e7-27e673c50597)


