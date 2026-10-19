# Python Algorithms Collection

A collection of Python algorithm implementations covering linked lists, recursion, graph search, binary trees, and probability simulation.

## Features

- **task_01.py** — singly linked list: reverse, insertion sort, and merge of two sorted lists
- **task_02.py** — Pythagoras tree fractal drawn recursively with `turtle`
- **task_03.py** — Dijkstra's shortest path algorithm on a weighted graph, with visualization (`graph.py`, `dijkstra.py`)
- **task_04.py** — binary heap converted to a tree and visualized with `networkx`
- **task_05.py** — DFS and BFS traversal of a binary heap tree, visualized with a color gradient by visit order
- **task_06.py** — budget-constrained item selection via a greedy algorithm and dynamic programming, optimizing calories per cost
- **task_07.py** — Monte Carlo simulation of two-dice rolls, comparing simulated vs. theoretical probabilities (see `monte-carlo.png`)

## Technology

- Python 3
- networkx, matplotlib (graph/tree visualization)
- turtle (fractal drawing)

## Running

Each task is a standalone script:

```
python task_01.py
python task_02.py
python task_03.py
python task_04.py
python task_05.py
python task_06.py
python task_07.py
```

Install dependencies first:

```
pip install networkx matplotlib
```
