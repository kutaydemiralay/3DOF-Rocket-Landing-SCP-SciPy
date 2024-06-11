# Fixed Time 3DOF Rocket Landing with Sequential Convex Programming and SciPy Optimization

This repository contains code and documentation for solving a fixed final time 3DOF rocket landing problem, comparing two different solving methods, Sequential Convex Programming (SCP) and general nonlinear solver available in free and open-source Python libraries, SciPy.

## Overview

In this project, we address the problem of landing a rocket with three degrees of freedom (3DOF) and fixed final time by employing Sequential Convex Programming (SCP) and comparing the results and performance with those obtained from a general nonlinear solver available in free and open-source Python libraries

## Documentation

You can find the detailed documentation in the PDF below:

[Project Poster](./Poster.pdf)

## Code Structure

- `rocket_landing_scp.ipynb`: Script for implementing SCP for the 3DOF rocket landing problem.
- `rocket_landing_nonlinear.ipynb`: Script for implementing a general nonlinear solver for comparison.
- `README.md`: This file.
- `Successive Convex Optimization.pdf`: Detailed documentation of the methods and results.


## Results

The optimization results, including plots of the rocket's trajectory, thrust vs.time  gimbal angles vs. time, and speed vs. time, will be generated and displayed for both approaches.


### Trajectory Plot from Cequential Convex Programming Algorithm

![Trajectory Plot](./images/SCP1.png)

### Thrust vs Time Plot from Cequential Convex Programming Algorithm

![Thrust Profile](./images/SCP2.png)

### Gimbal Angle vs.Time Plot from Cequential Convex Programming Algorithm

![Gimbal Angles](./images/SCP3.png)

### Speed vs. Time Plot from Cequential Convex Programming Algorithm

![Speed](./images/SCP4.png)

### Trajectory Plot from Cequential Convex Programming Algorithm

![Trajectory Plot](./images/NGA1.png)

### Thrust vs Time Plot from Cequential Convex Programming Algorithm

![Thrust Profile](./images/NGA2.png)

### Gimbal Angle vs.Time Plot from Cequential Convex Programming Algorithm

![Gimbal Angles](./images/NGA3.png)

### Speed vs. Time Plot from Cequential Convex Programming Algorithm

![Speed](./images/NGA4.png)

## Contributing

Feel free to fork this repository, make changes, and submit pull requests. Contributions are welcome!
