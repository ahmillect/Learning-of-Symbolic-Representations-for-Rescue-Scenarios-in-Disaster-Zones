# Learning of Symbolic Representations for Rescue Scenarios in Disaster Zones

This repository contains the code and resources for my Bachelor's Thesis titled "Learning of Symbolic Representations for Rescue Scenarios in Disaster Zones". The project focuses on the application of Neuro-Symbolic AI to extract symbolic interpretable knowledge in disaster response scenarios.

## Project Overview

The project aims to train an AI agent to navigate complex disaster scenarios, such as the aftermath of an earthquake or a flood, and extract valuable symbolic knowledge from its experiences. The methodology involves two main steps:

1. **Q-Learning**: A type of reinforcement learning used to train the agent to navigate a grid-based environment representing a disaster zone.
2. **Symbolic Knowledge Extraction**: A process of transforming the learned knowledge into a human-readable format, providing interpretable insights into the agent's decision-making process.

## Repository Structure

- `Knowledge Extraction (QLearning)`: Contains the source code for the project.
- `output_demo`: Contains a sample demo the results of the experiments.

## Getting Started

### Prerequisites

- Python 3.7 or higher
- NumPy
- OpenAI Gym

### Installation

1. Clone the repository:
```bash
git clone https://github.com/ahmillect/Learning-of-Symbolic-Representations-for-Rescue-Scenarios-in-Disaster-Zones.git
```
2. Navigate to the project directory:
```bash
cd Learning-of-Symbolic-Representations-for-Rescue-Scenarios-in-Disaster-Zones
```
3. Install the required packages:
```bash
pip install gym numpy
```

### Usage

- To train and validate the agent, run: `python Knowledge Extraction (QLearning).ipynb`

## Results

The agent showed significant improvement in performance over 1 million episodes of training, with a substantial increase in cumulative reward. The extracted symbolic knowledge, validated using a rule validation script, showed that a significant percentage of the extracted rules were valid.

## Future Work

Potential areas for further research include exploring different reinforcement learning algorithms, refining the rule validation process, expanding the complexity of the environment, and enhancing the symbolic knowledge extraction process.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

I would like to express my deepest appreciation to my supervisor, Dr. Nourhan Ehab, for her guidance and support throughout the course of this thesis.
