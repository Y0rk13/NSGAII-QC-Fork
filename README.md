# Quantum Circuit Optimization with Genetic Algorithm

## Description
This project implements a genetic algorithm for the optimization and approximation of quantum circuits. The main objective is to use evolutionary techniques to generate quantum circuits that best approximate a target unitary matrix or to optimize the parameters of existing circuits.

The project uses **Qiskit** for the manipulation and simulation of quantum circuits, as well as scientific computing tools like **NumPy** and **SciPy**.

## Installation

To install the necessary dependencies, ensure you have Python installed, then run the following command:

```bash
pip install -r requirements.txt
```

## Usage

The project is mainly structured around Jupyter notebooks. To explore and run the code:

1. Launch Jupyter Notebook or JupyterLab:
   ```bash
   jupyter notebook
   ```
2. Open one of the main notebooks, for example:
   - `AG_mono/code_ag.ipynb`: Single-objective genetic algorithm.
   - `NSGA-II/AG_multi_objectifs_VF.ipynb`: Multi-objective genetic algorithm (NSGA-II).
   - `final_test_AG/code_travaille copy 3.ipynb`: Final tests of the optimization algorithm.

## Project Structure
- `AG_mono/`: Single-objective implementations.
- `NSGA-II/`: Multi-objective implementations.
- `Final_test/` & `final_test_AG/`: Validation scripts and performance tests.
- `m1*/`, `m2*/`: Test modules for different types of circuit blocks.