﻿# TSP_throughMetaHeuristicOptimization
Problem Statement
The Travelling Salesman Problem (TSP) is a fundamental optimization problem in operations
research and computer science. It involves finding the shortest possible route for a salesman to
visit a given set of cities exactly once and return to the starting city. This combinatorial problem
is important due to its applications in logistics, transportation, and network design and its role in
testing optimization algorithms.
This project applies the TSP to a dataset of 30 cities distributed across India. The goal is to
identify the most efficient route that minimizes the total travel distance while ensuring that each
city is visited exactly once. The problem is particularly challenging due to the factorial growth in
the number of possible routes as the number of cities increases, making it computationally
infeasible to solve through brute force methods.
To address this challenge, the project leverages three advanced metaheuristic algorithms:
1. Genetic Algorithm (GA): Inspired by the principles of natural selection, GA uses
operations like selection, crossover, and mutation to iteratively evolve a population of
candidate solutions toward an optimal route.
2. Simulated Annealing (SA): This probabilistic technique mimics the process of
annealing in metallurgy, where a solution is gradually refined by exploring the solution
space while occasionally accepting worse solutions to escape local minima.
3. Ant Colony Optimization (ACO): Modeled on ants' foraging behavior, ACO uses
artificial pheromones to guide a population of agents toward the shortest path by
simulating collaborative learning.
