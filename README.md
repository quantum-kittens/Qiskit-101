# Qiskit 101
> Interactive Hands-on Jupyter Notebooks for Qiskit 101 Sessions & Workshops

[![Qiskit](https://img.shields.io/badge/Qiskit-1.0%2B-6929C4?style=flat&logo=ibm&logoColor=white)](https://qiskit.org/)
[![IBM Quantum Platform](https://img.shields.io/badge/IBM_Quantum-Platform-0062FF?style=flat&logo=ibm&logoColor=white)](https://quantum.cloud.ibm.com/)
[![License: Apache 2.0](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](LICENSE)

Welcome to the **Qiskit 101** hands-on educational repository! These notebooks guide beginners, university students, and workshop attendees through fundamental quantum computing concepts, modern Qiskit Patterns, variational algorithms, and practical coding exercises.

---

## 📚 Notebook Directory & Learning Path

| Step | Topic | Notebook | Description | Solutions / Answers |
| :---: | :--- | :--- | :--- | :--- |
| **00** | **Environment Setup** | [`Qiskit_install.ipynb`](Qiskit_install.ipynb) | Step-by-step installation of Qiskit, visualization tools, and IBM Quantum API token configuration. | — |
| **01** | **Qiskit Patterns 101** | [`HelloWorld_QiskitPatterns.ipynb`](HelloWorld_QiskitPatterns.ipynb) | The modern 4-step Qiskit workflow: Map, Optimize, Execute (Primitives), and Post-Process. | [`Answers _HelloWorld_QiskitPatterns.ipynb`](Answers%20_HelloWorld_QiskitPatterns.ipynb) |
| **02** | **Quantum Gates** | [`Hands-on with Qiskit - Quantum Gates.ipynb`](Hands-on%20with%20Qiskit%20-%20Quantum%20Gates.ipynb) | Single and multi-qubit Pauli gates, Hadamard, phase shifts, and entanglement circuits. | Built-in |
| **03** | **Entanglement & GHZ** | [`HelloWorld_QiskitPatterns_GHZstate.ipynb`](HelloWorld_QiskitPatterns_GHZstate.ipynb) | Constructing multipartite Greenberger–Horne–Zeilinger (GHZ) entangled states with Primitives. | Built-in |
| **04** | **Variational Algorithms** | [`Example_VariationalQuantumEigensolver.ipynb`](Example_VariationalQuantumEigensolver.ipynb) | Practical implementation of the Variational Quantum Eigensolver (VQE) for ground state estimation. | Built-in |
| **05** | **Hands-on Exercises** | [`Qiskit101_Coding_Exercises.ipynb`](Qiskit101_Coding_Exercises.ipynb) | Challenge problems covering circuit building, measurement, and algorithm workflows. | [`Qiskit101_Coding_Exercises_Solutions.ipynb`](Qiskit101_Coding_Exercises_Solutions.ipynb) |

---

## ⚡ Quick Start

### 1. Clone the repository
```bash
git clone https://github.com/quantum-kittens/Qiskit-101.git
cd Qiskit-101
```

### 2. Set up virtual environment
```bash
python3 -m venv .venv
source .venv/bin/activate  # On Windows: .venv\Scripts\activate
pip install qiskit qiskit-aer matplotlib pylatexenc jupyter
```

### 3. Launch Jupyter
```bash
jupyter notebook
```
Open [`Qiskit_install.ipynb`](Qiskit_install.ipynb) or [`HelloWorld_QiskitPatterns.ipynb`](HelloWorld_QiskitPatterns.ipynb) to get started!

---

## 🔗 Useful Links
- [IBM Quantum Platform](https://quantum.cloud.ibm.com/)
- [IBM Quantum Learning](https://quantum.cloud.ibm.com/learning/en)
- [Qiskit Advocate Program](https://www.ibm.com/quantum/qiskit#advocates)

---

## 👥 Contributors & Event History
Content contributed by **Junye Huang**, **Radha Pyari Sandhir**, **Marcel Pfaffhauser**, and **Jorge Martinez de Lejarza**, along with community updates from Qiskit Advocates.

**Used across international workshops & summer schools:**
- [MadQFF'25](https://uam-cpra.github.io/MadQFF25/)
- ["Quantum Computing: from fundamentals to applications 2025"](https://www.uik.eus/en/activity/quantum-computing-fundamentals-applications) summer school
- [ICFO Spring School 2025](https://www.icfo.eu/)
