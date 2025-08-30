# ReinFLY – Flappy Bird with Deep Reinforcement Learning

This project implements **Deep Q-Network (DQN)**, a value-based deep reinforcement learning algorithm, to train an AI agent that autonomously plays a **custom Flappy Bird game** built in **Pygame**.

The work was carried out as part of the **Summer of Code 2024** organized by the **Web and Coding Club, IIT Bombay**, during my 2nd year of Aerospace Engineering at IIT Bombay.

---

## Project Highlights

- Developed a custom Flappy Bird environment in Pygame for reinforcement learning experiments.  
- Implemented a Deep Q-Network (DQN) to enable autonomous gameplay.  
- Trained the model for around 40 hours – the agent consistently achieves an average score of 20–25 points.  
- Explored Policy Gradient methods, Temporal Difference learning, and other RL techniques for optimization.  
- Performance can be further improved by tuning hyperparameters and longer training runs.  

---

## Demo

Video explanation: [Watch here](https://drive.google.com/file/d/1UooX2iDVryXO7kBxtMGlHnjs36iM23XB/view?usp=sharing)

---

## Repository Structure

ReinFLY/
│── flappy_env.py # Custom Flappy Bird environment using Pygame
│── dqn_agent.py # Deep Q-Network implementation
│── train.py # Training loop for the RL agent
│── test.py # Run the trained agent
│── models/ # Saved DQN models
│── assets/ # Game sprites and assets
│── requirements.txt # Dependencies
│── README.md # Project documentation


---

## Installation, Training, Testing, and Requirements

```bash
# Clone this repository
git clone https://github.com/<your-username>/ReinFLY.git
cd ReinFLY

# Install dependencies
pip install -r requirements.txt

# Train the agent
python train.py

# Test a trained model
python test.py

## Acknowledgement
This project was developed under the Summer of Code 2024 program by the Web and Coding Club, IIT Bombay. Suggestions for further improvements are welcome.
