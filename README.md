# Non-Linear Equation Solver

This repository contains a Python implementation for solving non-linear equations using three numerical methods: Bisection, Newton-Raphson, and Secant. The goal of this project is to demonstrate the application of these methods in finding roots for a given set of non-linear equations.

## Overview

The solver allows the user to select one of the eight pre-defined non-linear equations and apply one of the three available methods to find the root. The methods used are:

1. **Bisection Method**: A simple and robust root-finding method that requires the function to change signs within the given interval.
2. **Newton-Raphson Method**: A faster, more efficient method that requires the function's derivative and initial guess.
3. **Secant Method**: A method that uses two initial guesses to approximate the root iteratively.

## Equations Solved

The following non-linear equations are included in the solver:

1. **Equation 1**: $y = \ln(x - 2)$
2. **Equation 2**: $y = e^{-x}$
3. **Equation 3**: $y = e^{x} - x$
4. **Equation 4**: $y = 10 \cdot e^{x / 2} \cdot \cos(2x)$
5. **Equation 5**: $y = x^{2} - 2$
6. **Equation 6**: $y = \sqrt{x - 2}$
7. **Equation 7**: $y = x \cdot \cos(y) + y \cdot \sin(x)$
8. **Equation 8**: $y = \frac{2}{x}$

## Usage

To use the solver, you will need to run the main script and input the value for $y$ and select one of the available methods. The script will then attempt to find the root for the selected equation using the chosen method.

Here is how the script works:

1. The user is prompted to input a value for $y$.
2. The user selects one of the three methods: **Bisection**, **Newton-Raphson**, or **Secant**.
3. The corresponding method is applied, and the root is displayed, if found.

### Example:

```bash
$ python solver.py
Enter the value of y: 1
Select the method (Bisection, Newton-Raphson, Secant): Bisection
