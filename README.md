# Reinforcement-Learning-Experiment-With-Simple-Bandit-Learning-Algorithms
Our goal will be to experiment with some simple bandit learning algorithms by implementing them from scratch and comparing their performance in terms of (1) the average accumulated reward as well as (2) the proportion of time the optimal action, i.e., the one with the highest expected reward, is taken.

This repository contains code for implementing and comparing various bandit algorithms as part of a reinforcement learning assignment.

## Bandit Algorithms Implemented
- Greedy with non-optimistic initial values
- Epsilon-greedy with different choices of epsilon
- Optimistic starting values with a greedy approach
- Gradient bandit algorithm with different learning rates

## Non-Stationary Bandit Problems
- Drift changes
- Mean-reverting changes
- Abrupt changes

## How to Run the Code
To run the code in this repository, follow these steps:

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/AzmolFK/Reinforcement-Learning-Experiment-With-Simple-Bandit-Learning-Algorithms.git
    cd Reinforcement-Learning-Experiment-With-Simple-Bandit-Learning-Algorithms
    ```

2. **Open in Google Colab**:
    - Go to [Google Colab](https://colab.research.google.com/).
    - Click on `File` > `Open notebook`.
    - Select the `GitHub` tab and enter `AzmolFK/Reinforcement-Learning-Experiment-With-Simple-Bandit-Learning-Algorithms`.
    - Open the `Assignment_1.ipynb` notebook.
  
3. **Run the Notebook**:
    - Execute the cells in the notebook to reproduce the results.

## Repository Structure
- `Assignment_1.ipynb`: Main notebook containing the implementation and analysis.
- `README.md`: Instructions for running the notebook.
