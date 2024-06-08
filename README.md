# Solving-Systems-of-Linear-Equations-in-Python
Given a system of 4 linear equations, solving each of them  with the best method after careful analysis 

## Overview
This assignment involves solving a given system of 4 linear equations using various numerical methods. Each method is chosen based on a careful analysis of the system's properties to determine the most suitable approach. The correctness of the solutions is verified by comparing the results from different methods.

## Project Structure
The project consists of the following key components:

1. **Matrix and Vector Definition**: 
    - Define the coefficient matrices and the right-hand side vectors for the systems of linear equations.

2. **Analysis of the Coefficient Matrix**: 
    - Check properties such as symmetry, positive definiteness, and sparsity of the matrices.

3. **Solving Methods**:
    - Cholesky Decomposition
    - LU Decomposition with Partial Pivoting
    - Direct Solve using `numpy/scipy` functions

4. **Verification of Solutions**:
    - Ensure the correctness of solutions by comparing the results obtained from different methods.

## Systems of Linear Equations
The following systems of linear equations are solved:

### System 1
```markdown
4.8356x1 - 0.4872x2 - 1.2887x3 - 0.1702x4 - 1.6765x5 = 1  
-0.4872x1 + 6.3591x2 - 0.2362x3 - 0.6004x4 + 0.9641x5 = 2  
-1.2887x1 - 0.2362x2 + 9.3849x3 + 1.5144x4 - 0.3445x5 = 1  
-0.1702x1 - 0.6004x2 + 1.5144x3 + 1.3349x4 - 0.0560x5 = 2  
-1.6765x1 + 0.9641x2 - 0.3445x3 - 0.0560x4 + 5.5854x5 = 1  

