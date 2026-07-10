# Quantum Algorithms: Experimental Implementation & Fault Diagnosis of Quantum Logic Gates

<p align="center">

![Python](https://img.shields.io/badge/Python-3.11-blue)
![Qiskit](https://img.shields.io/badge/Qiskit-Latest-6929C4)
![IBM Quantum](https://img.shields.io/badge/IBM%20Quantum-Real%20Hardware-1261FE)
![License](https://img.shields.io/badge/License-MIT-green)
![Status](https://img.shields.io/badge/Status-Completed-success)

</p>

---

## 📌 Overview

This repository contains the complete implementation of my **Science Academies' Summer Research Fellowship Programme (SRFP-2025)** internship carried out at **Bose Institute, Kolkata**, under the supervision of **Prof. Somshubhro Bandyopadhyay**.

The project bridges the gap between **quantum computing theory** and **real-world quantum hardware** by implementing fundamental quantum algorithms using **Qiskit**, validating them on **IBM Quantum Computers**, and investigating the effects of **faulty quantum gates**.

Unlike conventional introductory quantum computing projects, this work includes both **mathematical derivations** and **experimental verification** on real quantum processors.

---

# ✨ Highlights

- Complete implementation of
  - Deutsch Algorithm
  - Deutsch–Jozsa Algorithm
  - Bernstein–Vazirani Algorithm

- Experimental verification on
  - IBM Brisbane
  - IBM Torino

- Quantum simulator implementation using
  - Aer Simulator
  - Statevector Simulator

- Experimental study of

  - Quantum Gates
  - Quantum Entanglement
  - Quantum Parallelism

- Stability comparison between different IBM quantum processors

- Novel analysis of coherent phase-flip errors in Hadamard gates

- Mathematical derivation of generalized faulty Hadamard operator

- Fidelity analysis of faulty quantum circuits

---

# 📚 Project Contents

```
.
│
├── Quantum Gates
│     ├── NOT
│     ├── CNOT
│     ├── Hadamard
│
├── Quantum Algorithms
│     ├── Deutsch
│     ├── Deutsch–Jozsa
│     ├── Bernstein–Vazirani
│
├── IBM Hardware Experiments
│
├── Stability Analysis
│
├── Fault Diagnosis
│
├── Fidelity Analysis
│
├── Figures
│
├── Source Codes
│
└── Report.pdf
```

---

# 🔬 Topics Covered

## Quantum Computing Fundamentals

- Qubits
- Qudits
- Qutrits
- Hilbert Space
- Quantum Registers
- Quantum Gates
- Quantum Circuits
- Quantum Oracle
- Superposition
- Entanglement
- Quantum Parallelism
- Quantum Interference

---

## Algorithms Implemented

### Deutsch Algorithm

✔ Mathematical derivation

✔ Oracle implementation

✔ Simulator execution

✔ IBM Quantum execution

---

### Deutsch–Jozsa Algorithm

✔ General theory

✔ Two-qubit implementation

✔ Multiple oracle constructions

✔ Real hardware implementation

✔ Performance comparison

---

### Bernstein–Vazirani Algorithm

✔ Hidden string recovery

✔ Oracle implementation

✔ Mathematical proof

---

# ⚛ Experimental Work

The following experiments are included:

- NOT Gate verification

- CNOT Gate verification

- Walsh–Hadamard transformation

- Bell-state generation

- Quantum entanglement visualization

- Quantum parallelism demonstration

- Deutsch Algorithm on IBM hardware

- Deutsch–Jozsa Algorithm on IBM hardware

- Stability comparison between IBM Brisbane and IBM Torino

---

# 🧪 Fault Diagnosis of Hadamard Gates

One of the major contributions of this work is the analysis of **coherent phase-flip errors** in the Hadamard gate.

The repository investigates

- Ideal Hadamard

- Faulty Hadamard

- Generalized Hadamard

- Bloch sphere evolution

- Output state fingerprints

- Experimental verification

- Fidelity calculations

The generalized faulty Hadamard operator is expressed as

\[
H(\theta)=
\frac{1}{\sqrt2}
\begin{bmatrix}
1&1\\
-e^{i\theta}&e^{i\theta}
\end{bmatrix}
\]

which smoothly interpolates between the ideal and faulty cases.

---

# 📊 Features

- Real quantum hardware execution

- Noise-aware experimentation

- Experimental vs theoretical comparison

- Mathematical derivations

- Publication-quality plots

- Heatmaps

- Bloch sphere visualizations

- Fidelity plots

---

# 🖥 IBM Quantum Hardware Used

- IBM Brisbane
    - Eagle r3 Processor
    - 127 Qubits

- IBM Torino
    - Heron r1 Processor
    - 133 Qubits

---

# 🛠 Technologies Used

- Python

- Qiskit

- NumPy

- Matplotlib

- IBM Quantum Runtime

- Jupyter Notebook

---

# 🚀 Getting Started

Clone the repository

```bash
git clone https://github.com/yourusername/Quantum-Algorithms-Fault-Diagnosis.git
```

Install dependencies

```bash
pip install qiskit
pip install matplotlib
pip install numpy
```

Run

```bash
python filename.py
```

or open the notebooks

```bash
jupyter notebook
```

---

# 📈 Results

The repository demonstrates

- Ideal simulation of quantum algorithms

- Successful execution on IBM Quantum hardware

- Experimental validation of quantum advantage

- Comparison of simulator vs hardware

- Stability analysis across quantum processors

- Detection of faulty Hadamard gates using unique measurement signatures

- Quantitative fidelity analysis

---

# 📄 Report

A detailed report describing

- theoretical derivations,

- circuit implementations,

- experimental observations,

- stability studies,

- mathematical proofs,

- and fault analysis

is included in this repository.

---

# 🎯 Future Work

Possible extensions include

- Multi-qubit fault diagnosis

- Qutrit and qudit implementations

- Quantum error mitigation

- Noise-aware oracle design

- Quantum error correction

- Fault diagnosis of multi-qubit gates

- Hardware-aware quantum compiler optimization

---

# 👨‍💻 Author

**Rangan Chakrabarty**

Department of Physics

Jadavpur University

Science Academies' Summer Research Fellow (2025)

Bose Institute, Kolkata

---

# 🙏 Acknowledgements

This work was carried out under the supervision of

**Prof. Somshubhro Bandyopadhyay**

Department of Physical Sciences

Bose Institute

Special thanks to the developers of

- IBM Quantum

- Qiskit

- Python Scientific Community

for making open quantum computing accessible to researchers worldwide.

---

# ⭐ If you find this repository useful...

Please consider giving it a **Star ⭐**.

It motivates future research and development in open-source quantum computing.
