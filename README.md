# QuantumCompResearch


This repository is dedicated to the exploration and implementation of various quantum computing algorithms using Qiskit, IBM's open-source quantum computing software development framework. The aim is to provide clear examples and tutorials for quantum algorithms that can be executed on simulated quantum computers.

## About Qiskit

Qiskit is an open-source SDK for working with quantum computers at the level of pulses, circuits, and algorithms. It provides tools for creating and manipulating quantum programs and running them on prototype quantum devices and simulators. Learn more about Qiskit at [Qiskit.org](https://qiskit.org/).

## Implemented Algorithms

The following quantum algorithms are implemented in this repository:

- **Quantum Fourier Transform (QFT)** - The quantum analogue of the discrete Fourier transform.
- **Shor's Algorithm** - An algorithm for integer factorization.
- **Grover's Algorithm** - A search algorithm that runs quadratically faster than any possible classical algorithm.
- **Quantum Phase Estimation** - Used to estimate the phase (or eigenvalue) of an eigenstate of a unitary operator.
- **Variational Quantum Eigensolver (VQE)** - An algorithm designed to find the ground state energies of molecules and other Hamiltonians.
- **Quantum Walks** - Implementation of both discrete and continuous quantum walks.

Each folder in the repository contains the following:

- A Python script with the Qiskit implementation of the algorithm.
- A Jupyter notebook that provides a detailed tutorial on how to use and understand the algorithm.

## Getting Started

### Prerequisites

Before you can run these quantum algorithms, you'll need to install Python and Qiskit. Here's how to set up your environment:

1. **Install Python**: Download and install Python 3.8 or higher from [python.org](https://www.python.org/).

2. **Install Qiskit**: Once Python is installed, run the following command to install Qiskit:

   ```bash
   pip install qiskit
   ```

## Contributing

Contributions to this repository are welcome. Please read `CONTRIBUTING.md` for details on our code of conduct, and the process for submitting pull requests to us.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE) file for details.
