## Predicting the Unpredictable: Double Pendulum Chaos Modeling

### Project Description
This project explores the cross section of classical mechanics and computational probability. 
The goal is to model the deterministic chaos of a Double Pendulum. The double pendulum (nicknamed the chaos pendulum) is a system famously sensitive to initial conditions where 
even the tiniest measurement errors lead to vastly different outcomes.
By utilizing Monte Carlo simulations, this project moves beyond a single "best guess" prediction. 
Instead, it generates a probabilistic cloud of potential trajectories, allowing us to visualize the "divergence point" where the system transitions from predictable motion into pure chaos.

This project uses:
<p></p>
Lagrangian Mechanics: Derivation of motion equations using the difference between Kinetic (T) and Potential (V) energy to handle complex physical constraints.
<p></p>
Numerical Integration: Using scipy.integrate.odeint to solve non-linear second-order differential equations.
<p></p>
Monte Carlo Method: Understanding uncertainty by running hundreds of simulations simultaneously with randomized initial states ($\theta$ and $\omega$).
<p></p>
Data Extraction: Creating a bridge between physical experiments with digital models by tracking diode movement from video footage.
<p></p>

### Installation
You will need a Python environment (3.7+) and the following libraries:

NumPy: For numerical arrays and trigonometry.

SciPy: Specifically for the ODE solver.

Matplotlib: For generating trajectory plots.
