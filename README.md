# Fixed Time 3DOF Rocket Landing with Sequential Convex Programming and SciPy Optimization

This repository contains code and documentation for solving a fixed final time 3DOF rocket landing problem, comparing Sequential Convex Programming (SCP) with general nonlinear optimization using SciPy.

## Overview

In this project, we address the problem of landing a rocket with three degrees of freedom (3DOF) by employing Sequential Convex Programming (SCP) and compare it with a general nonlinear solver. We leverage SciPy's optimization capabilities to find the optimal control inputs that ensure a safe landing.

## Documentation

You can find the detailed documentation in the PDF below:

[Successive Convex Optimization](./Successive%20Convex%20Optimization.pdf)

## Code Structure

- `rocket_landing_scp.py`: Script for implementing SCP for the 3DOF rocket landing problem.
- `rocket_landing_nonlinear.py`: Script for implementing a general nonlinear solver for comparison.
- `README.md`: This file.
- `Successive Convex Optimization.pdf`: Detailed documentation of the methods and results.

## Dependencies

- Python 3.x
- NumPy
- SciPy
- CVXPY
- SymPy
- Matplotlib

## Usage

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/3DOF-Rocket-Landing-SCP-vs-Nonlinear-Optimization.git
    cd 3DOF-Rocket-Landing-SCP-vs-Nonlinear-Optimization
    ```

2. Install the dependencies:
    ```bash
    pip install numpy scipy cvxpy sympy matplotlib
    ```

3. Run the SCP script:
    ```bash
    python rocket_landing_scp.py
    ```

4. Run the general nonlinear solver script:
    ```bash
    python rocket_landing_nonlinear.py
    ```

## Results

The optimization results, including plots of the rocket's trajectory, thrust profile, gimbal angles, and speed, will be generated and displayed for both approaches.

## Contributing

Feel free to fork this repository, make changes, and submit pull requests. Contributions are welcome!
