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

### System 2
```markdown
147.8801x1 + 61.5872x2 + 49.7739x3 + 86.1919x4 - 11.0202x5 = 1  
61.5872x1 + 79.2119x2 + 57.6460x3 + 92.9713x4 + 8.6421x5 = 2  
49.7739x1 + 57.6460x2 + 145.4756x3 - 0.2775x4 - 35.6829x5 = 1  
86.1919x1 + 92.9713x2 - 0.2775x3 + 162.5327x4 + 30.1183x5 = 2  
-11.0202x1 + 8.6421x2 - 35.6829x3 + 30.1183x4 + 39.3188x5 = 1  


### System 3
```markdown
1.6468x1 + 0.6047x2 + 0.3044x3 + 0.7368x4 + 0.6983x5 = 1  
0.6047x1 + 1.1352x2 + 0.7557x3 + 0.1261x4 + 0.8578x5 = 2  
0.3044x1 + 0.7557x2 + 1.4921x3 + 0.8154x4 + 0.3899x5 = 1  
0.7368x1 + 0.1261x2 + 0.8154x3 + 1.2139x4 + 0.3760x5 = 2  
0.6983x1 + 0.8578x2 + 0.3899x3 + 0.3760x4 + 1.0661x5 = 1  

### System 4
```markdown
2x1 = 1  
2x1 + 3x2 = 2  
3x1 + 4x2 + 4x3 = 1  
4x1 + 2x2 + 3x3 + 2x4 = 2  
2x1 + 2x2 + 2x3 + 2x4 + 2x5 = 1  

## Analysis of the Coefficient Matrix
For each system, the following properties are analyzed:

1. **Symmetry**:
    - Determine if the matrix is symmetric by comparing it to its transpose.

2. **Positive Definiteness**:
    - Check if all eigenvalues of the matrix are positive to confirm positive definiteness.

3. **Sparsity**:
    - Calculate the sparsity of the matrix, which is the proportion of zero elements.

## Solving Methods

### Cholesky Decomposition
- Applied to positive definite matrices.
- Decomposes the matrix into the product of a lower triangular matrix and its transpose.

### LU Decomposition with Partial Pivoting
- Suitable for general matrices.
- Decomposes the matrix into the product of a lower triangular matrix, an upper triangular matrix, and a permutation matrix.

### Direct Solve using `numpy/scipy` functions
- Uses optimized numerical libraries to directly solve the system of equations.

## Verification of Solutions
- The solutions obtained from Cholesky decomposition and LU decomposition are compared with the direct solve method to ensure correctness.

## Results
The solutions for each system are computed using the best method identified through the analysis. The correctness of each solution is confirmed by verifying consistency across different methods.

## Conclusion
This assignment successfully demonstrates the application of various numerical methods to solve systems of linear equations. The analysis of matrix properties helps in choosing the most appropriate method, ensuring accurate and efficient solutions.

