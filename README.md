# SnakeAI – Deep Q-Learning Based Snake Game AI

A reinforcement learning-based implementation of the classic Snake game using Deep Q-Learning (DQN). This project demonstrates how intelligent agents can learn to play and improve through experience and reward-based feedback, with no hardcoded rules.

---

## Project Overview

**SnakeAI** uses a neural network and the Deep Q-Learning algorithm to train an agent to play the Snake game autonomously. The model improves over time through trial and error, leveraging key RL concepts like exploration vs exploitation, experience replay, and temporal difference learning.

This project is a foundational application of reinforcement learning and is ideal for showcasing core concepts in AI decision-making and game intelligence.

---

## Key Features

- Implementation of Deep Q-Learning from scratch  
- Real-time visualization using Pygame  
- Replay memory for experience sampling  
- Adjustable training hyperparameters  
- Score tracking and performance metrics  

---

## Technologies Used

| Component           | Technology/Library          |
|---------------------|-----------------------------|
| Language            | Python                      |
| RL Algorithm        | Deep Q-Learning (DQN)       |
| Deep Learning       | PyTorch                     |
| Game Rendering      | Pygame                      |
| Plotting            | Matplotlib                  |

---

## Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/isam10/SnakeAI.git
cd SnakeAI
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Train the Agent
```bash
python train.py
```

### 4. Play or Evaluate the Trained Model
```bash
python play.py
```

---

## Project Structure

```
SnakeAI/
├── model.py          # Neural network model definition
├── agent.py          # DQN agent logic
├── game.py           # Snake game mechanics using Pygame
├── train.py          # Training loop
├── play.py           # Run a trained agent
├── utils.py          # Helper functions (replay memory, plotting)
├── requirements.txt
└── README.md
```

---

## Learning Algorithm: Deep Q-Learning (DQN)

- **State Representation**: Encodes the grid, direction, and danger into a feature vector  
- **Reward Function**: Positive reward for eating food, negative for dying  
- **Policy**: Epsilon-greedy strategy to balance exploration and exploitation  
- **Network**: Fully connected PyTorch network to approximate the Q-function  
- **Training**: Experience replay + stochastic mini-batch updates

---

## Sample Results

- The agent improves performance gradually and can score 50+ consistently after sufficient training.
- Visualization of scores and moving average is included after each training session.

---

## Roadmap

- [x] Implement DQN agent and environment  
- [x] Training and reward shaping  
- [ ] Add model checkpoint saving/loading  
- [ ] Implement curriculum learning  
- [ ] Deploy as a playable web app (optional)

---

## Educational Value

This project is ideal for:
- Students and practitioners learning reinforcement learning  
- AI project portfolios showcasing practical DQN application  
- Game AI prototypes for research and experimentation  

---

## Contact

**Isam Syed**  
Email: [isam.syed3@gmail.com](mailto:isam.syed3@gmail.com)  
GitHub: [https://github.com/isam10](https://github.com/isam10)

---

SnakeAI demonstrates how an agent can learn complex behavior purely through interaction with an environment. No rules, just learning.
