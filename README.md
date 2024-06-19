# Reinforcement-Learning-Experiment-With-Simple-Bandit-Learning-Algorithms
Our goal is to experiment with some simple bandit learning algorithms by implementing them from scratch and comparing their performance in terms of (1) the average accumulated reward and (2) the proportion of time the optimal action, i.e., the one with the highest expected reward, is taken.

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

## Additional Practice: Reinforcement Learning for Classification
As an additional practice for how bandits can be used for more complex problems, this repository includes a notebook that demonstrates the application of bandit algorithms to a classification problem using the Iris dataset. This practice is based on the following papers:
- [Efficient Online Bayesian Inference for Neural Bandits](https://proceedings.mlr.press/v151/duran-martin22a/duran-martin22a.pdf)
- [Learning Methodology for Neural Bandits](https://proceedings.mlr.press/v232/chang23a/chang23a.pdf)

The Iris dataset, which can be found [here](https://archive.ics.uci.edu/dataset/53/iris), is used to convert a classification problem into a bandit problem where the goal is to learn a classifier online to maximize cumulative reward.

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
    - Open the `Assignment_1.ipynb` or `Additional.ipynb` notebook.
  
3. **Run the Notebooks**:
    - Execute the cells in the notebooks to reproduce the results.

## Repository Structure
- `Assignment_1.ipynb`: Main notebook containing the implementation and analysis of bandit algorithms.
- `Additional.ipynb`: Notebook for additional practice, demonstrating the application of bandit algorithms to the Iris dataset.
- `iris.data`: Dataset used in `Additional.ipynb`.
- `README.md`: Instructions for running the notebooks.
