# Connecting-Four

Description :

This project implements a reinforcement learning (RL) agent to play Connect Four using a custom environment created with OpenAI Gym and Kaggle Environments. The agent uses a convolutional neural network (CNN) for feature extraction and the Proximal Policy Optimization (PPO) algorithm from the Stable-Baselines3 library.

Features :
1- Custom Connect Four Environment:

-Built using OpenAI Gym and Kaggle Environments.

-Defines action and observation spaces.

-Provides reward adjustments and game state updates.

2-Custom CNN for Feature Extraction:

-Uses PyTorch to define a CNN for processing game board observations.

-Integrates the CNN with Stable-Baselines3's PPO algorithm.

3-Training the RL Agent:

-Trains a PPO agent with the custom CNN as the policy network.

-Configurable training parameters and environment settings.



Files :

Project_Connecting_Four.ipynb: Main Jupyter notebook containing the implementation and training of the RL agent.
requirements.txt: List of required Python packages.

Dependencies :

gym

kaggle_environments

numpy

pandas

matplotlib

torch

stable-baselines3
