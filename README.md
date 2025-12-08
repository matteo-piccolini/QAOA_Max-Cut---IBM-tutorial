# Quantum Approximate Optimization Algorithm (QAOA) for Max-Cut

This Jupyter Notebook demonstrates the application of the **Quantum Approximate Optimization Algorithm (QAOA)** to solve the classical optimization problem known as **Max-Cut**.

The Max-Cut problem seeks to partition the vertices of a graph into two sets such that the number of edges between the sets is maximized. QAOA provides a heuristic approach to find near-optimal solutions on quantum hardware.

### Key Concepts Covered:
* **Problem Mapping:** Representing the classical Max-Cut problem as a quantum Hamiltonian.
* **QAOA Ansatz:** Construction of the quantum circuit (ansatz) involving alternating mixer and cost layers.
* **Classical Optimization Loop:** Using a classical optimizer (like COBYLA or similar) to find the optimal parameters for the quantum circuit.
* **Execution:** Running the circuit and sampling the output to determine the best classical solution.

### ⚠️ Important: Tutorial Reference

This notebook is a **personal reproduction of the code provided in the official IBM Quantum tutorial** for educational purposes, ensuring compliance and fidelity to the source material.

**Original Tutorial Link:**
[QAOA Tutorial](https://quantum.cloud.ibm.com/docs/en/tutorials/quantum-approximate-optimization-algorithm)
