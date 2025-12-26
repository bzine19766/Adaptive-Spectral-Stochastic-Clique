# Adaptive-Spectral-Stochastic-Clique
Official implementation of the Adaptive Spectral-Stochastic Search (ASSS) framework for the Maximum Clique Problem, designed to overcome topological stagnation in deceptive graph landscapes.

# Adaptive Spectral-Stochastic Search (ASSS) for Maximum Clique

This repository contains the source code for the paper:  
**"Adaptive Spectral-Stochastic Search for Maximum Cliques: Overcoming Stagnation in Deceptive Graph Landscapes"**

## 🚀 Overview
Traditional Min-Conflict heuristics often suffer from **topological stagnation**, becoming trapped in near-clique local optima (meta-stable states). This solver introduces a dual-engine approach to navigate these challenges:

1.  **Analytical PageRank Mapping:** Uses spectral centrality to bias the search toward the structural core, neutralizing deceptive "spectral mirages" in adversarial graphs.
2.  **Strategic Penalty Oscillation:** Implements thermodynamic "vibrations" in the energy function to tunnel through high-conflict barriers and escape local minima.



## 📊 Key Results
The ASSS framework successfully identifies maximum cliques in diverse topological benchmarks where standard uninformed searches fail:
* **Hamming 8-4:** Breaks the rigid symmetry of vertex-transitive graphs.
* **C125.9:** Leverages spectral honesty for rapid convergence.
* **Brock200-2:** Successfully navigates deceptive degree-equalized traps.
