# Snake AI

A deep reinforcement learning agent trained to play the classic Snake game using PyTorch and Pygame.

## Features

* **Custom Game Environment:** Built from scratch using Pygame with configurable grid sizes and rendering speeds.
* **Reinforcement Learning Agent:** Implements Q-learning with a deep neural network (Deep Q-Network / DQN) using PyTorch for state evaluation and action selection.
* **State Representation:** Encodes directional danger checks, relative food positions, and current movement vectors.
* **Training & Evaluation:** Supports live rendering toggles during training to monitor loss convergence and high-score progression.

## Tech Stack

* **Language:** Python 3.10+
* **Deep Learning:** PyTorch
* **Graphics & UI:** Pygame

## Getting Started

### Prerequisites

Ensure you have Python installed along with an active virtual environment setup:

```bash
python3 -m venv venv
source venv/bin/activate

```

### Installation

Clone the repository and install dependencies:

```bash
git clone https://github.com/Jayantraj299/snake-ai.git
cd snake-ai
pip install -r requirements.txt

```

### Running the Project

Train a new agent from scratch:

```bash
python train.py

```

Run inference with a trained model:

```bash
python agent.py

```
