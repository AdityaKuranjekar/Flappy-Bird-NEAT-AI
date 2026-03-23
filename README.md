# Flappy Bird AI Agent using NEAT

## Overview
This repository contains an Artificial Intelligence agent trained to autonomously play Flappy Bird. The project was developed as part of the CS2203: Artificial Intelligence coursework at IIT Patna, exploring applied machine learning and neural networks.

## How It Works
Instead of using hardcoded rules to jump, this project utilizes **NEAT (NeuroEvolution of Augmenting Topologies)**, a genetic algorithm that evolves artificial neural networks. 
* The AI starts with random behaviors.
* By simulating natural selection, the neural network adapts its structure and weights across multiple generations.
* It evaluates "fitness" based on distance traveled and pipes successfully passed, typically generating a flawless agent in under 5 generations.

## Technologies Used
* **Python** * **Pygame** (for the graphical game environment)
* **NEAT-Python** (for the genetic algorithm implementation)

## Installation & Usage
To see the AI train and play locally with the visual GUI:

1. Clone this repository:
   `git clone https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git`
2. Install the required dependencies:
   `pip install -r requirements.txt`
3. Run the AI model:
   `python flappy_ai.py`
