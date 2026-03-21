# Linear Programming: Simplex vs Neural Network Solver
 
Studying deterministic and probabilistic approaches to solving LPPs. Comparing simplex method with machine learning, and analyzing the time-accuracy tradeoff between the two.
 
---
 
## Project Overview
 
This project is built in three stages:
 
**Simplex Method (Deterministic)**
Implementing the simplex algorithm from scratch in Python using NumPy. Takes a standard LPP in the form of an objective function and constraints, builds the tableau, and iterates to the optimal solution. Handles edge cases including unbounded and infeasible problems.
 
**Neural Network Solver (Probabilistic)**
Training a neural network to approximate solutions to LPPs. The network learns patterns from a dataset of LPPs and their known optimal solutions.
 
**Benchmarking: Time vs Accuracy**
A comparison of the time required for both algorithms to run, and the accuracy of the neural network. 
 
---
 
## Motivation
 
The simplex method is exact but can be slow for large problems. Neural networks can approximate solutions near-instantly. We compare the accuracy of the neural network to the time saved.
 
---
 
## Repository Structure
 
```
├── simplex.ipynb         
├── neural_network.ipynb   
├── benchmarking.ipynb     
└── README.md
```
 
---
 
## Requirements
 
```
import matplotlib
import seaborn
import pandas as pd
import torch
import numpy as np
```
