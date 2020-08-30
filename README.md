# Quantum Experiments

This repository holds some notebook experiments with quantum algorithms.

You can run these experiments yourself by installing [Anaconda Python 3 distribution](https://www.anaconda.com/products/individual), and then installing the environment provided in this repository with

    conda env create -f environment.yml

The following notebooks are provided:

* [Quantum entanglement and quantum teleportation](quantum_teleportation.ipynb): shows the properties of quantum entangled states, and how this can be used to teleport quantum information (qubits) across space in a cryptographically secure manner.
* [SAT solver with Grover's algoriothm](sat_grover.ipynb): shows how Grover's algorithm for unsorted search can also be used to solve boolean satisfiability problems. The algorithm is also run on real quantum hardware.
