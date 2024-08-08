# Quantum Algorithms Notebook

This repository contains implementations of five fundamental quantum algorithms. Each algorithm is presented in a Jupyter notebook, demonstrating practical applications, performance analysis, and visualizations.

## Algorithms Implemented
1. **Bernstein-Vazirani Algorithm**
2. **Deutsch-Jozsa Algorithm**
3. **Grover's Algorithm**
4. **Simon's Algorithm**
5. **Shor's Algorithm**

## Technologies Used
- **Qiskit**: A Python library for quantum computing provided by IBM.
- **IBM Quantum backend**: For executing quantum circuits on real quantum processors and simulators.
- **Jupyter Notebooks**: For creating and sharing documents that contain live code, equations, visualizations, and narrative text.
- **Matplotlib**: For creating visualizations in Python.
- **NumPy**: For numerical computations in Python.

## Notebooks Overview

### [Bernstein-Vazirani Algorithm](bernstein_vazirani.ipynb)
  Determines a hidden binary string by querying an oracle.

### [Deutsch-Jozsa Algorithm](deutsch_jozsa.ipynb)
  Solves the problem of determining whether a function is constant or balanced.

### [Grover's Algorithm](grovers.ipynb)
  Provides a quadratic speedup for unstructured search problems.

### [Simon's Algorithm](simons.ipynb)
  Solves Simon's problem exponentially faster than any classical algorithm.

### [Shor's Algorithm](scalable_shor_algorithm.ipynb)
  Factors integers in polynomial time, breaking RSA encryption.

## Getting Started

### Prerequisites
- Python 3.6 or higher
- Jupyter Notebook
- Qiskit
- Matplotlib
- NumPy

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/quantum-algorithms-notebook.git
    cd quantum-algorithms-notebook
    ```

2. Install the required packages:
    ```bash
    pip install qiskit matplotlib numpy
    ```

3. Start Jupyter Notebook:
    ```bash
    jupyter notebook
    ```

4. Open the desired notebook from the Jupyter interface.

## Usage
Each notebook contains step-by-step instructions, code, and explanations. Simply run the cells in the notebooks to see the algorithms in action and visualize the results.

## Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

## License
This project is licensed under the MIT License.

## Acknowledgements
- [IBM Quantum](https://quantum-computing.ibm.com/) for providing access to quantum processors and simulators.
- The Qiskit community for their excellent documentation and support.
