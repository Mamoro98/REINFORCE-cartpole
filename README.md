
# 🎮 Reinforcement Learning: REINFORCE for CartPole 🚀

Welcome to the **REINFORCE CartPole Project**! This repository showcases a simple reinforcement learning implementation using the REINFORCE algorithm to solve the classic **CartPole** environment. 🏗️

---

## 🌟 Features
- **Environment**: CartPole-v1 from OpenAI Gym 🤖
- **Algorithm**: Policy Gradient-based REINFORCE 🧠
- **Library**: Implemented using JAX and Haiku for speed and flexibility ⚡
- **Goal**: Balance a pole on a cart for as long as possible. The environment is considered solved with an average score of **500**! 🏆

---

## 📂 File Structure
- `cartpole.ipynb` 📒: The core implementation with training, evaluation, and visualization.
- 📊 Includes reward plotting for training performance monitoring.

---

## 📦 Dependencies
Ensure you have the following installed:
- JAX 🦎
- Gym 🏋️‍♂️
- Haiku 🌲
- Optax ⚙️
- Matplotlib 📈

Install them with:
```bash
pip install jaxlib jax gym[box2d] git+https://github.com/deepmind/dm-haiku optax matplotlib
```

---

## 🚀 Getting Started
1. Clone this repository:  
   ```bash
   git clone https://github.com/Mamoro98/REINFORCE-cartpole.git
   ```
2. Navigate to the directory:  
   ```bash
   cd REINFORCE-cartpole
   ```
3. Run the notebook:  
   ```bash
   jupyter notebook cartpole.ipynb
   ```

---

## 🧠 How It Works
1. **State Space**: 🖥️ The agent observes:
   - Pole angle 📐
   - Angular velocity ⏱️
   - Cart position ➡️
   - Cart velocity ⬅️
2. **Action Space**: 🤔 Two possible actions:
   - Move cart **left** ⬅️
   - Move cart **right** ➡️
3. **Reward**: 🎯
   - +1 for each timestep the pole remains upright.

The REINFORCE algorithm optimizes a neural network policy through the **Policy Gradient Theorem**.

---

## 🛠️ Training Tips
- Experiment with hyperparameters like learning rate or neural network architecture. 🔧
- Monitor reward trends to detect overfitting or undertraining. 📈

---

## 🌐 Credits
Developed during the **Reinforcement Learning (from Zero to One)** course at AIMS South Africa. Adapted from the Deep Learning Indaba series. 📚

---

## 🎉 Results
The trained agent achieves an average score of **500**, solving the environment successfully! 💯
Video: https://github.com/user-attachments/assets/8f7e12d9-c828-4f71-8151-d4c6e62dc567


Feel free to fork, star ⭐, or contribute to this project! 

--- 

