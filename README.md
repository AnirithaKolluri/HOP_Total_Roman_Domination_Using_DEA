# 🏛️ Hop Total Roman Domination Using Differential Evolution

### Research Internship Project – NIT Warangal

This project focuses on solving the **Hop Total Roman Domination (HTRD) problem** in graph theory using the **Differential Evolution (DE) optimization algorithm**.  

The goal is to assign labels to graph vertices such that every node is dominated within **two hops**, while minimizing the **total labeling weight**.

This work was completed as part of a **Research Internship at National Institute of Technology (NIT) Warangal** during my **2nd year of B.Tech**.

---


# 🛠 Languages & Technologies

![Python](https://img.shields.io/badge/Python-Programming-blue?style=for-the-badge&logo=python)
![NetworkX](https://img.shields.io/badge/NetworkX-GraphAnalysis-green?style=for-the-badge)
![NumPy](https://img.shields.io/badge/NumPy-NumericalComputing-purple?style=for-the-badge&logo=numpy)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange?style=for-the-badge)
![Jupyter](https://img.shields.io/badge/JupyterNotebook-Development-yellow?style=for-the-badge&logo=jupyter)

---
# 📌 Problem Statement

**Hop Total Roman Domination (HTRD)** is an advanced graph theory problem where nodes must be labeled such that domination constraints are satisfied within **two-hop distances**.

Each node can be assigned one of the following labels:

- **0 → Unlabeled node**
- **1 → Weakly labeled node**
- **2 → Strongly labeled node ensuring domination**

The challenge is to **minimize the total labeling weight** while maintaining valid domination constraints.

---

# ⚙️ Algorithm Overview

The project uses the **Differential Evolution (DE) Algorithm**, a population-based optimization technique, to find an optimal or near-optimal labeling.

### Graph Representation
Graphs are modeled using **adjacency lists** for efficient traversal and processing.

### HTRDF Validation
Ensures the generated labeling satisfies the **Hop Total Roman Domination constraints**.

### Weight Calculation
Computes the **total domination weight** of the graph labeling.

### Heuristic Initialization
A heuristic-based approach generates an **initial feasible solution** for the optimization process.

### Differential Evolution Process

1️⃣ **Initialization**  
Generate a population of candidate solutions.

2️⃣ **Mutation**  
Create variation among solutions.

3️⃣ **Crossover**  
Combine candidate solutions to explore new search regions.

4️⃣ **Selection**  
Retain the best-performing individuals for the next generation.

---

# 🎨 Graph Visualization

The graph visualization represents node labels using different colors:

🟥 **Red (0)** – Unlabeled nodes  
🟨 **Yellow (1)** – Weakly labeled nodes  
🟩 **Green (2)** – Strongly labeled nodes ensuring domination  

Visualization is implemented using **NetworkX and Matplotlib**.

---

# ✨ Key Features

✔ Optimization of Hop Total Roman Domination Function (HTRDF)  
✔ Differential Evolution based optimization approach  
✔ Heuristic-based solution generation  
✔ Graph representation using NetworkX  
✔ Visualization of labeled nodes  

---

# 📊 Results

The Differential Evolution algorithm successfully finds **optimal or near-optimal domination configurations** for graphs while minimizing total labeling weight.

Key outcomes:

- Efficient optimization of HTRDF
- Improved search performance using evolutionary techniques
- Visual representation of domination states

---

# 🧠 Technical Skills Demonstrated

This project demonstrates knowledge in:

- Graph Theory
- Evolutionary Algorithms
- Differential Evolution
- Optimization Techniques
- Graph Visualization
- Algorithm Design
- Scientific Computing

---
