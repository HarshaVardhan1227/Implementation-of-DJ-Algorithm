# Implementation-of-DJ-Algorithm
Implementation of the Deutsch–Jozsa Algorithm using IBM Quantum and Qiskit to determine whether a function is constant or balanced with a single quantum evaluation. Demonstrates quantum parallelism, oracle construction, and circuit execution on a quantum simulator. ⚛️

# Project Overview

The Deutsch–Jozsa algorithm is an important example of quantum parallelism.

In this project:

1.Multiple qubits are initialized in superposition.

2.A custom oracle function encodes the Boolean function.

3.The algorithm processes all possible inputs simultaneously.

4.Measurement determines whether the function is constant or balanced.

This demonstrates how quantum algorithms can solve specific problems exponentially faster than classical algorithms.

# Key Concepts Used

->Qubits

->Superposition

->Quantum Parallelism

->Oracle Function

->Hadamard Gates

# Technologies Used

->Python

->Qiskit

->IBM Quantum Platform

->Jupyter Notebook

->Google Colab

# Algorithm Workflow
1. Initialize Qubits

Input qubits are initialized in the |0⟩ state, while the auxiliary qubit is initialized in |1⟩.

2. Apply Hadamard Gates

Hadamard gates create superposition, allowing the circuit to evaluate multiple inputs simultaneously.

3. Oracle Implementation

The oracle represents the Boolean function and modifies the phase of the quantum states depending on the function output.

4. Interference

Another layer of Hadamard gates creates interference between states.

5. Measurement

The result indicates whether the function is constant or balanced.


# Applications & Importance

Although mainly theoretical, the Deutsch–Jozsa algorithm demonstrates:

1.Quantum computational advantage

2.Quantum parallelism

3.Foundations of advanced algorithms like Simon's Algorithm and Shor’s Algorithm
