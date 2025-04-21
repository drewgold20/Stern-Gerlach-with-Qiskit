# Quantum Computing and the Stern-Gerlach Experiment: A Qiskit-Based Study

This project simulates the Stern-Gerlach experiment using IBM's Qiskit quantum computing framework. The goal is to explore how quantum computers, which can only measure in the computational (Z) basis, can simulate spin measurements along arbitrary axes (X, Y, Z) through the application of quantum gates.

##  Project Overview

- **Topic:** Modeling spin angular momentum using quantum circuits.
- **Framework:** Qiskit (Python)
- **Experiment Simulated:** Stern-Gerlach experiment, a landmark demonstration of quantized spin.
- **Educational Goal:** To demonstrate how abstract quantum mechanics can be visualized and simulated using modern quantum programming tools.

##  What is the Stern-Gerlach Experiment?

The Stern-Gerlach experiment was the first to demonstrate the existence of quantized angular momentum (spin). Instead of producing a continuous spread, a beam of atoms split into two distinct paths, revealing the two-state nature of spin — an intrinsic property of particles like electrons.

##  Methods

- Simulated spin measurements along the:
  - **Z-axis** (default)
  - **X-axis** (using a Hadamard gate)
  - **Y-axis** (using a combination of S and H gates)
- Measurements were run on simulated quantum circuits with probability histograms used to visualize outcomes.



