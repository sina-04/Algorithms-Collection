# Algorithms-Collection

This is a collection of famous and useful algorithms used in computer science and engineering problems.

---

## Overview

This repository organizes algorithms into three broad categories — **Exact**, **Heuristic**, and **Metaheuristic** — each representing a different philosophy of problem-solving.
From guaranteed-optimal methods to intelligent search strategies inspired by nature, this collection provides a reference point for both theoretical understanding and practical implementation.

---

## 🧮 Exact Algorithms

These algorithms **guarantee the optimal solution**, often through mathematical formulations and systematic exploration of the solution space.
They are precise but can become computationally expensive for large or NP-hard problems.

| #   | Algorithm                     | Typical Application                                        |
| --- | ----------------------------- | ---------------------------------------------------------- |
| 1   | **Simplex Method**            | Linear Programming                                         |
| 2   | **Branch and Bound (B&B)**    | Integer / Mixed-Integer Programming                        |
| 3   | **Branch and Cut**            | Combinatorial Optimization (TSP, VRP)                      |
| 4   | **Dynamic Programming (DP)**  | Sequential Decision Problems (Knapsack, Shortest Path)     |
| 5   | **Cutting Plane Method**      | Integer Programming, Polyhedral Optimization               |
| 6   | **Branch and Price**          | Column Generation, Vehicle Routing                         |
| 7   | **Network Simplex Algorithm** | Minimum Cost Flow, Transportation Problems                 |
| 8   | **Interior Point Method**     | Large-scale Linear and Nonlinear Programming               |
| 9   | **Hungarian Algorithm**       | Assignment Problem                                         |
| 10  | **Dijkstra’s Algorithm**      | Shortest Path in Graphs (exact under non-negative weights) |

---

## ⚙️ Heuristic Algorithms

Heuristics aim to **find good enough solutions quickly**, using intuitive rules or problem-specific strategies.
They are particularly useful when exact algorithms become infeasible due to problem size or complexity.

| #   | Algorithm                                               | Typical Application                           |
| --- | ------------------------------------------------------- | --------------------------------------------- |
| 1   | **Greedy Algorithm**                                    | Scheduling, Knapsack, MST (Prim’s, Kruskal’s) |
| 2   | **Nearest Neighbor Heuristic**                          | Traveling Salesman Problem (TSP)              |
| 3   | **2-opt / 3-opt**                                       | Route Optimization (TSP, VRP)                 |
| 4   | **Insertion Heuristic**                                 | Vehicle Routing, Scheduling                   |
| 5   | **Savings Algorithm (Clarke & Wright)**                 | Vehicle Routing Problem (VRP)                 |
| 6   | **Local Search**                                        | General improvement of existing solutions     |
| 7   | **Hill Climbing**                                       | Function optimization (simple landscapes)     |
| 8   | **Greedy Randomized Adaptive Search Procedure (GRASP)** | Combinatorial Optimization                    |
| 9   | **Best-First Search / A\***                             | Pathfinding, Robotics                         |
| 10  | **Constructive Scheduling Heuristics (SPT, LPT)**       | Job Scheduling Problems                       |

---

## 🧠 Metaheuristic Algorithms

Metaheuristics are **higher-level frameworks** that guide the search process to explore the solution space effectively.
They often combine randomness, adaptation, and biological or physical inspiration to escape local optima and find near-optimal solutions for large, complex problems.

| #   | Algorithm                             | Inspiration / Concept                    |
| --- | ------------------------------------- | ---------------------------------------- |
| 1   | **Genetic Algorithm (GA)**            | Natural Selection, Evolution             |
| 2   | **Simulated Annealing (SA)**          | Metallurgy Cooling Process               |
| 3   | **Tabu Search**                       | Adaptive Memory and Forbidden Moves      |
| 4   | **Ant Colony Optimization (ACO)**     | Ant Foraging Behavior                    |
| 5   | **Particle Swarm Optimization (PSO)** | Bird Flocking / Fish Schooling           |
| 6   | **Differential Evolution (DE)**       | Population-based Continuous Optimization |
| 7   | **Artificial Bee Colony (ABC)**       | Honeybee Foraging Behavior               |
| 8   | **Harmony Search (HS)**               | Musical Improvisation                    |
| 9   | **Firefly Algorithm (FA)**            | Bioluminescent Communication             |
| 10  | **Cuckoo Search (CS)**                | Brood Parasitism Behavior                |

---

## Summary

| Type              | Optimality            | Typical Scope                                 | Famous Examples        |
| ----------------- | --------------------- | --------------------------------------------- | ---------------------- |
| **Exact**         | Guaranteed            | Small–medium, structured problems             | Simplex, B&B, DP       |
| **Heuristic**     | Near-optimal          | Medium–large, specific problems               | Greedy, 2-opt, Savings |
| **Metaheuristic** | Near-optimal (robust) | Very large, complex, or unstructured problems | GA, SA, PSO, ACO       |

---

### 🌐 Purpose of This Repository

This repository serves as:

- A **reference hub** for well-known algorithms across disciplines.
- A **learning resource** for students and practitioners of optimization, computer science, and data science.
- A **code collection** for implementing and benchmarking algorithms in real-world problem contexts.

---

## 📁 Repository Structure

The repository is organized into three main directories, each representing one class of algorithms.
Every folder contains well-documented implementations, examples, and references for further study.

```
Algorithms-Collection/
│
├── exact/
│   ├── simplex/
│   ├── branch_and_bound/
│   ├── dynamic_programming/
│   └── ...
│
├── heuristic/
│   ├── greedy/
│   ├── nearest_neighbor/
│   ├── local_search/
│   └── ...
│
├── metaheuristic/
│   ├── genetic_algorithm/
│   ├── simulated_annealing/
│   ├── particle_swarm_optimization/
│   └── ...
│
└── README.md
```

Each implementation includes:

- **Explanation** – a brief description of the algorithm’s logic and mathematical foundation.
- **Code** – a clean, modular implementation (preferably in Python).
- **Example** – a sample use case or test problem demonstrating how it works.
- **References** – academic or practical resources for deeper understanding.

---

### 🧭 Future Extensions

Planned expansions include:

- Benchmark comparisons between algorithms on classic datasets (e.g., TSP, Knapsack).
- Visualizations of search processes for metaheuristics.
- Links to Jupyter notebooks for interactive learning.
