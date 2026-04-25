# Reinforcement Learning Lab

## Overview
This lab focuses on the concepts and techniques related to reinforcement learning, including the implementation of tile coding, the semi-gradient SARSA algorithm, and various visualizations and feature design experiments.

## Tile Coding Implementation
Tile coding is a form of function approximation that helps to generalize learning across similar states. In this lab, we implement tile coding to discretize continuous state spaces, allowing the agent to better estimate value functions.

## Semi-Gradient SARSA Algorithm
The semi-gradient SARSA algorithm combines the benefits of SARSA with the efficiency of gradient descent. In this module, we explore its implementation and how it applies to the lab's reinforcement learning tasks.

## Visualizations
Visualizing the learning process and outcomes is crucial for understanding agent behavior. We include various plots that depict the performance of the learning agent over time, along with the value functions learned during training.

## Feature Design Experiments
Feature design is integral to the success of reinforcement learning algorithms. We conduct experiments testing different feature sets to analyze their impact on agent performance.

## Setup Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/rvallaboju/MSDS684_Week-5-Lab-5.git
   cd MSDS684_Week-5-Lab-5
   ```
2. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the lab scripts:
   ```bash
   python main.py
   ```

## Requirements
- Python version 3.6 or higher
- numpy
- matplotlib
- gym
- [Any additional packages if applicable]  

Make sure to check the requirements.txt file for the complete list of dependencies.