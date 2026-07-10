<div align="center">

# Quantum Algorithms: Detailed Study, Experimental Implementation & Fault Diagnosis of Quantum Logic Gates

**A research project on quantum algorithms, real quantum hardware, and coherent gate error diagnosis using Qiskit and IBM Quantum**

![Python](https://img.shields.io/badge/Python-3.11-blue)
![Qiskit](https://img.shields.io/badge/Qiskit-Latest-6929C4)
![IBM Quantum](https://img.shields.io/badge/IBM-Quantum-1261FE)
![License](https://img.shields.io/badge/License-MIT-success)

</div>

---

## About

Quantum computers promise computational advantages for problems that are difficult or impossible for classical machines. While many introductory projects focus solely on simulations, this work extends beyond theory by validating quantum algorithms on **real IBM Quantum processors** and investigating how hardware imperfections influence computational outcomes.

This repository contains the complete implementation of my **Science Academies' Summer Research Fellowship Programme (SRFP-2025)** internship carried out at **Bose Institute, Kolkata**, under the supervision of **Prof. Somshubhro Bandyopadhyay**.

The project combines theoretical analysis, mathematical derivations, numerical simulations, and experimental implementation to study both the capabilities and limitations of present-day quantum computers.

---

## Key Contributions

✔ Implementation of the **Deutsch**, **Deutsch–Jozsa**, and **Bernstein–Vazirani** algorithms

✔ Experimental execution on **IBM Brisbane** and **IBM Torino**

✔ Comparative study between ideal simulators and real quantum hardware

✔ Experimental verification of quantum gates and Bell-state entanglement

✔ Stability analysis of IBM quantum processors

✔ Development of a coherent phase-flip error model for the Hadamard gate

✔ Mathematical derivation of a generalized faulty Hadamard operator

✔ Fidelity analysis for quantifying algorithmic robustness

---

## Repository Structure

```text
.
├── Algorithms/
│   ├── Deutsch/
│   ├── Deutsch-Jozsa/
│   └── Bernstein-Vazirani/
│
├── Quantum_Gates/
│   ├── NOT/
│   ├── CNOT/
│   └── Hadamard/
│
├── IBM_Hardware/
│
├── Fault_Analysis/
│
├── Figures/
│
├── Report/
│
└── README.md
```

---

# Project Overview

The project is organized into four major components.

### 1. Foundations of Quantum Computing

A brief theoretical introduction covering

- Qubits and quantum registers
- Qutrits and higher-dimensional quantum systems
- Hilbert spaces
- Quantum gates
- Quantum circuits
- Quantum superposition
- Entanglement
- Quantum parallelism
- Quantum interference

---

### 2. Quantum Algorithm Implementation

The following algorithms were implemented from first principles.

| Algorithm | Simulator | IBM Hardware |
|-----------|-----------|--------------|
| Deutsch | ✅ | ✅ |
| Deutsch–Jozsa | ✅ | ✅ |
| Bernstein–Vazirani | ✅ | ✅ |

Each implementation includes

- Mathematical derivation
- Circuit construction
- Oracle implementation
- Experimental validation
- Performance analysis

---

### 3. Experimental Investigation

This repository contains experimental implementations of

- NOT gate
- CNOT gate
- Hadamard gate
- Bell-state generation
- Quantum entanglement
- Quantum parallelism
- Deutsch Algorithm
- Deutsch–Jozsa Algorithm

Both simulated and hardware-generated measurement statistics are included.

---

### 4. Fault Diagnosis of Quantum Gates

One of the major objectives of this project was to investigate how coherent gate imperfections influence quantum algorithms.

Instead of treating hardware noise as a black box, a controlled error model was introduced into the Hadamard gate and its effect on the Deutsch–Jozsa algorithm was analyzed both mathematically and experimentally.

The work includes

- Bloch sphere analysis
- Error propagation
- Unique output-state fingerprints
- Heatmap visualization
- Generalized phase-error model
- Fidelity analysis

---

# Generalized Faulty Hadamard

The generalized faulty Hadamard operator is defined as

\[
H(\theta)=
\frac{1}{\sqrt2}
\begin{bmatrix}
1&1\\
-e^{i\theta}&e^{i\theta}
\end{bmatrix}
\]

where

- **θ = 0** corresponds to the ideal Hadamard gate
- **θ = π** represents the coherent phase-flip error model

This parameterization provides a continuous transition between ideal and faulty quantum operations.

---

# Experimental Platforms

The algorithms were executed on

| Platform | Purpose |
|-----------|---------|
| Qiskit Aer Simulator | Ideal simulations |
| IBM Brisbane | Real hardware validation |
| IBM Torino | Stability comparison |

---

# Software Stack

- Python
- Qiskit
- NumPy
- Matplotlib
- IBM Quantum Runtime
- Jupyter Notebook

---

# Highlights

- Mathematical derivations from first principles

- Real quantum hardware implementation

- Hardware vs simulator comparison

- Noise-aware analysis

- Publication-quality plots

- Experimental validation

- Fault diagnosis framework

- Fidelity-based performance evaluation

---

# Sample Results

The repository demonstrates

- Accurate implementation of fundamental quantum algorithms

- High agreement between theoretical predictions and simulations

- Successful execution on IBM Quantum processors

- Effects of decoherence and gate imperfections

- Experimental identification of faulty Hadamard gates

- Comparative stability analysis across quantum devices

---

# Future Research Directions

Potential extensions of this work include

- Multi-qubit fault diagnosis

- Qutrit and qudit implementations

- Quantum error mitigation

- Noise-resilient oracle design

- Quantum error correction

- Hardware-aware circuit optimization

---

# Citation

If you use this repository in your research or academic work, please cite it appropriately.

```bibtex
@misc{chakrabarty2025quantum,
  author = {Rangan Chakrabarty},
  title = {Quantum Algorithms: Detailed Study, Experimental Implementation and Fault Diagnosis of Quantum Logic Gates},
  year = {2025},
  institution = {Bose Institute},
}
```

---

# Acknowledgements

This work was completed during the **Science Academies' Summer Research Fellowship Programme (SRFP-2025)** at **Bose Institute, Kolkata**.

The project made extensive use of the open-source **Qiskit** ecosystem and IBM Quantum cloud resources, whose contributions to quantum computing education and research are gratefully acknowledged.

---

<div align="center">

### If you found this project useful, consider giving it a ⭐

It helps others discover the project and supports and motivates open research in quantum computing.

</div>
