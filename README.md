# AI Strategies for Taxi-v3 Environment

## Authors
- Michele Leggieri
- Thienlong Ly
- Hongdu Wei

## Overview
This project provides a comprehensive comparison of three AI strategies—Reinforcement Learning (RL), Deep Learning, and a Genetic Algorithm combined with Reinforcement Learning (GA + RL)—within the Taxi-v3 environment from OpenAI Gym.

## Files in the Repository
- `deep_learning_plots.pdf`: Plots showing score progression for the deep learning model.
- `genetic_algorithm_reinforcement_learning_plots.pdf`: Plots showing score progression for the GA + RL model.
- `reinforcement_learning_plots.pdf`: Plots showing score progression for the RL model.
- `deep_learning_taxi.ipynb`: Jupyter Notebook for deep learning implementation.
- `dl&ga_taxi.ipynb`: Jupyter Notebook for GA + RL implementation.
- `reinforcement_learning_taxi.ipynb`: Jupyter Notebook for RL implementation.
- `report.pdf`: Detailed report comparing the three AI strategies.
- `taxi_learnt.mp4`: Visualization of the RL model at optimal performance.

## Usage
Run the Jupyter notebook (Jupyter with Gymnasium package installed)
    jupyter notebook deep_learning_taxi.ipynb
    jupyter notebook dl&ga_taxi.ipynb
    jupyter notebook reinforcement_learning_taxi.ipynb

## Results and Analysis
The project includes training and evaluation of different AI strategies. Key findings include:

- **Reinforcement Learning (RL):** Demonstrated the best performance, quickly converging to an optimal policy.
- **Deep Learning:** Showed steady improvement but at a slower pace compared to RL.
- **Genetic Algorithm with RL (GA + RL):** Stabilized quickly but did not significantly improve beyond initial convergence.

## Visualization
The `taxi_learnt.mp4` file provides a visualization of the RL model's optimal performance, showcasing the agent's ability to efficiently navigate the Taxi-v3 environment.