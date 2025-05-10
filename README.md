# Circuit Solver Using Tieset and Cutset Matrices

## Overview

This project is a Python-based circuit solver that utilizes tieset and cutset matrices to analyze RLC circuits in both the Laplace and time domains. The solver can handle circuits with resistors, inductors, capacitors, voltage sources, and current sources. It provides detailed analysis, including current and voltage solutions, and visualizes the results through plots.

## Features

- **Laplace Domain Analysis**: Solves circuits using Laplace transforms to determine currents and voltages.
- **Time Domain Analysis**: Converts Laplace domain solutions to time domain using inverse Laplace transforms.
- **Graphical Visualization**: Plots current and voltage responses over time for better understanding.
- **Interactive Input**: Allows users to input circuit parameters interactively.
- **Matrix Methods**: Uses tieset and cutset matrices for systematic circuit analysis.

## Requirements

- Python 3.x
- NumPy
- SymPy
- Matplotlib

## Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd circuit-solver
   ```

2. Install the required dependencies:
   ```bash
   pip install numpy sympy matplotlib
   ```

## Usage

1. **Run the Jupyter Notebook**:
   Open `Circuit Solver.ipynb` in Jupyter Notebook and execute the cells to interact with the solver.

2. **Input Circuit Parameters**:
   - Enter the number of nodes and elements (resistors, inductors, capacitors, voltage sources, current sources).
   - Specify each element's type, value, and connecting nodes.

3. **Analyze the Circuit**:
   - The solver will generate incidence, tieset, and cutset matrices.
   - It will compute currents and voltages in both Laplace and time domains.
   - Results are displayed numerically and graphically.

4. **Visualize Results**:
   - Plot current and voltage responses over specified time ranges.
   - Compare multiple branches' responses on the same graph.

## Example

The notebook includes an example analysis of an RLC circuit with:
- 4 nodes
- 5 elements (1 voltage source, 2 resistors, 1 inductor, 1 capacitor)

## Outputs

- **Matrices**: Incidence, tieset, and cutset matrices.
- **Currents and Voltages**: Solutions in both Laplace and time domains.
- **Plots**: Graphical representations of time-domain responses.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your improvements.

## License

This project is open-source and available under the MIT License.

## Contact

For questions or feedback, please open an issue on the repository.
