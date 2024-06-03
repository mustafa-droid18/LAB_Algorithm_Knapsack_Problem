# Solving the 0-1 Knapsack Problem Using the LAB Algorithm

This repository contains the implementation of the LAB (Leader Advocate Believer) Algorithm to solve the 0-1 Knapsack Problem.

## Overview

The LAB Algorithm is a metaheuristic optimization algorithm inspired by human social behavior. It is used to find optimal or near-optimal solutions for combinatorial problems, such as the 0-1 Knapsack Problem. The repository is divided into two main sections:
1. Single Knapsack Problem
2. Multiple Knapsack Problem

## LAB Algorithm

The LAB Algorithm is designed to mimic the decision-making process of a group of individuals classified as leaders, advocates, and believers:
- **Leaders**: Explore new solutions and set high aspirations.
- **Advocates**: Evaluate solutions proposed by leaders and advocate for the most promising ones.
- **Believers**: Follow the solutions proposed by advocates and refine them to find the optimal solution.

This collaborative approach allows the LAB Algorithm to efficiently explore and exploit the solution space.

## Repository Structure

- **Single Knapsack Problem**
  - `Single_Knapsack_Problem.ipynb`: Jupyter notebook implementing the LAB Algorithm for the single knapsack problem.
  
- **Multiple Knapsack Problem**
  - `Multiple_Knapsack_Problem.ipynb`: Jupyter notebook implementing the LAB Algorithm for multiple knapsacks.

## Getting Started

### Prerequisites

- Python 3.x
- Jupyter Notebook
- Additional Python libraries: `numpy`, `pandas`, `statistics` (installable via pip)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/mustafa-droid18/Solving-the-0-1-Knapsack-Problem-Using-the-LAB-Algorithm.git
   cd Solving-the-0-1-Knapsack-Problem-Using-the-LAB-Algorithm
   ```
   
2. Install required libraries:
   ```bash
   pip install numpy pandas statistics
   ```
## Single Knapsack Problem
The notebook `Single_Knapsack_Problem.ipynb` contains:

- Initialization of item weights, values, and knapsack capacity.
- Implementation of the LAB Algorithm to maximize the total value without exceeding the knapsack's capacity.
- Output of the optimal solution and various statistics.

## Multiple Knapsack Problem
The notebook `Multiple_Knapsack_Problem.ipynb` contains:

- Initialization of multiple knapsacks with their respective capacities, weights, and values of items.
- Implementation of the LAB Algorithm to maximize the total value across all knapsacks without exceeding their capacities.
- Output of detailed results and statistics.

## Contributing
Contributions are welcome! If you find any issues or have suggestions for improvements, feel free to open an issue or submit a pull request.

## Acknowledgments
Inspired by various metaheuristic algorithms and the need to solve optimization problems efficiently.

