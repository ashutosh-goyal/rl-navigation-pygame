# Exploring the Potential of the PPO Reinforcement Learning Algorithm for Efficient Navigation with Obstacle Avoidance

This repository contains the code for training a reinforcement learning agent to navigate through a simulated environment toward a target while avoiding obstacles. The agent is trained using the PPO (Proximal Policy Optimization) algorithm via Stable-Baselines3, with a custom environment built using OpenAI Gym and Pygame for rendering.

The project covers both discrete and continuous action/observation spaces. In the discrete setting, the agent achieved 100% success rate across randomized scenarios. The continuous setting introduced additional complexity around action smoothness and hyperparameter tuning, which is discussed in detail in the report.

For a detailed explanation of the project and its implementation, please refer to `main.pdf`.

## 📽️ Demo

| Fixed Obstacle | Random Obstacle |
|:-:|:-:|
| <video src="https://github.com/user-attachments/assets/07860864-9cc8-43aa-9d6d-5eeb6f28334c" controls width="300" height="200"></video> | <video src="https://github.com/user-attachments/assets/a98c96b2-419d-48d2-90ff-b6af7a7b702c" controls width="300" height="200"></video> |

---
