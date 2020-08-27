# Algorithms-of-Numerical-Linear-Algebra
Implementations of the Algorithms from *Numerical Linear Algebra* lectures, from the *Masters Degree in Foundations of Data Science*, at *Universitat de Barcelona*.

Click [here](https://nbviewer.jupyter.org/github/alexfc14/Algorithms-of-Numerical-Linear-Algebra/blob/master/Algorithms_of_Numerical_Linear_Algebra.ipynb)  to view the rendered notebook with all the algorithm implementations.

Summary:
* **Lower-Upper** Triangular Linear systems:
  * **LU Decomposition** $$A=LU$$
    * Lower Triangular System $$LA=B$$ Solver
    * Upper Triangular System $$UA=B$$ Solver
    * Linear System $$Ax=b$$ Solver using $$A=LU$$ decomposition
  * **Cholesky Decomposition** $$A = L L^T$$
    * Least Squares Problem Solver using Cholesky Decomposition
* **QR Decomposition** $$A=QR$$:
  * QR Decomposition using **Gram-Schmidt orthogonalization**
    * Least Squares Problem Solver using QR Decomposition
  * QR Decomposition using **Householder reflections**
  * QR Decomposition using **Givens rotations**
* **SVD** Singular Value Decomposition $$A=USV^T$$
  * Least Squares Problem Solver using SVD
* **Iterative methods**:
  * **Power method** $$Ax/|Ax|$$ for the **Dominant Eigenvalue**
  * **Orthogonal Iteration** (Schur) for orthogonal transformation into upper triangular $$A=QRQ^T$$
  * **Linear System Solver** with iterative methods:
    * **Jacobi**
    * **Gauss-Seidel**
    * **Successive Over-Relaxation SOR(w)**
