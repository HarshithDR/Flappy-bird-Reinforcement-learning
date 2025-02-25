# Flappy Bird with Reinforcement Learning

This project implements the classic Flappy Bird game in Python and uses **NEAT (NeuroEvolution of Augmenting Topologies)**, a reinforcement learning algorithm, to train an AI agent to play the game autonomously. The agent learns to navigate the game environment by evolving through generations, optimizing its decision-making to survive longer and score higher. 

---

## Features
- **Game Development**: A fully functional Flappy Bird game built using Python.
- **Self-Playing Agent**: The AI agent learns to play Flappy Bird using the NEAT reinforcement learning algorithm.
- **NeuroEvolution**: The NEAT algorithm evolves the bird's neural network by adjusting weights and topology, improving its performance with every generation.
- **Dynamic Learning**: The AI adapts to game dynamics, such as obstacle positioning and speed, by maximizing its fitness function.

---

## Key Technologies
1. **Python**: Core language for game development and AI implementation.
2. **Pygame**: Used for building the Flappy Bird game visuals and mechanics.
3. **NEAT-Python**: A Python library for implementing the NEAT reinforcement learning algorithm.

---

## How It Works
1. **Game Environment**:
   - Flappy Bird game mechanics such as bird motion, gravity, and pipes are recreated using Pygame.

2. **Reinforcement Learning**:
   - The AI agent is controlled by a neural network trained using **NEAT**.
   - NEAT evolves the neural network through generations, improving the bird’s decision-making based on fitness scores.

3. **Fitness Function**:
   - The fitness score is determined by the distance traveled by the bird, rewarding longer survival and penalizing collisions.

4. **Training Process**:
   - A population of neural networks is initialized, each controlling a separate bird.
   - Through simulation and competition, the top-performing networks evolve into the next generation.

---

## Installation Guide

### Prerequisites
- Python 3.x installed on your system.
- Basic understanding of Pygame and reinforcement learning concepts is helpful.

### Steps to Install
1. **Clone the Repository**:
  ```bash
  git clone https://github.com/HarshithDR/Flappy-bird-Reinforcement-learninig.git
  cd Flappy-bird-Reinforcement-learninig
  ```


2. **Install Dependencies**:
Install all required Python packages using:
  ```bash
  pip install -r requirements.txt
  ```

3. **Run the Game and Training**:
Start the training process by running:
  ```bash
  python flappy_bird_neat.py
  ```


---

## Usage Instructions

1. **Play the Game**:
 - Use the basic game script to play the game manually (optional).

2. **Train the AI**:
 - Run the training script to watch the AI agent learn and evolve over generations.

3. **Monitor Learning**:
 - Observe how the agent improves with each generation, learning to avoid obstacles and score higher.

4. **Test the AI**:
 - Use the trained model to let the AI autonomously play the game.

---

## Project Details
- **Reinforcement Learning Algorithm**: NEAT (NeuroEvolution of Augmenting Topologies)
- **Fitness Function**: Maximizes survival time and penalizes collisions.
- **Generations**: The AI evolves over multiple generations to optimize its gameplay.

---

## Future Scope
- **Advanced Neural Networks**: Experiment with more complex neural network architectures for improved decision-making.
- **Dynamic Obstacles**: Introduce new challenges, such as moving or random-sized pipes.
- **Visualizations**: Add performance graphs to track the progress of training over generations.

---

## Contributors
- **Harshith Deshalli Ravi**  
[GitHub](https://github.com/HarshithDR)

---

## Contact
For any inquiries, feedback, or contributions, feel free to reach out to [Harshith Deshalli Ravi](https://github.com/HarshithDR).

