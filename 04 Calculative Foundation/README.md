# Calculative Foundation: Linear Algebra in Student Performance Analytics

## 🎯 Project Overview
This project applies fundamental **Linear Algebra concepts** to analyze and transform a dataset of student academic performance across multiple subjects. By leveraging mathematical foundations such as vector operations, matrix operations, geometric interpretations, and spectral decomposition (Eigenvalues & Eigenvectors), this project demonstrates how core mathematical tools underpin applied Data Science, Machine Learning, and Artificial Intelligence algorithms.

---

## 📑 Problem Statement
A research institute shared a dataset containing students' performance scores across multiple subjects. As a Data Analyst, the task is to apply Linear Algebra techniques to:
1. **Represent & Manipulate Data**: Map student scores into multi-dimensional vector spaces.
2. **Execute Core Operations**: Compute vector norms, dot products, angles ($\theta$), cross products, and vector projections.
3. **Perform Matrix Algebra**: Evaluate Matrix addition, transpose ($\mathbf{M}^T$), multiplication ($\mathbf{M}\mathbf{M}^T$), determinant ($\det(\mathbf{A})$), and matrix inversion ($\mathbf{A}^{-1}$).
4. **Geometric Analysis**: Explain spatial transitions across dimensions from 2D Lines to 3D Planes and multi-dimensional Hyperplanes ($\mathbf{w}^T\mathbf{x} + b = 0$).
5. **Spectral Decomposition**: Extract Eigenvalues and Eigenvectors from the covariance matrix to analyze variance and lay the foundation for Principal Component Analysis (PCA).

---

## 🛠️ Project Tasks & Methodology

### Part A: Vector & Matrix Fundamentals
- **Vector Representation**: Represented each student's score profile as an $n$-dimensional vector $\mathbf{v} \in \mathbb{R}^n$.
- **Vector Norms**:
  - **Norm-1 ($L_1$ Norm / Manhattan Distance)**: $\Vert{}\mathbf{v}\Vert{}_1 = \sum \vert{}v_i\vert{}$ — Measures total cumulative score.
  - **Norm-2 ($L_2$ Norm / Euclidean Distance)**: $\Vert{}\mathbf{v}\Vert{}_2 = \sqrt{\sum v_i^2}$ — Measures overall vector magnitude/distance from origin.
- **Dot Product & Angle**: Computed $\mathbf{a} \cdot \mathbf{b} = \sum a_i b_i$ and the angle $\cos(\theta) = \frac{\mathbf{a} \cdot \mathbf{b}}{\Vert{}\mathbf{a}\Vert{}_2 \Vert{}\mathbf{b}\Vert{}_2}$ to evaluate performance profile similarity.
- **Cross Product & Projection**: Evaluated spatial orthogonality ($\mathbf{a} \times \mathbf{b}$) in 3D subject space and calculated orthogonal projection $\text{proj}_{\mathbf{b}}\mathbf{a} = \left(\frac{\mathbf{a} \cdot \mathbf{b}}{\Vert{}\mathbf{b}\Vert{}_2^2}\right)\mathbf{b}$.

### Part B: Matrix Operations
- Formed a $5 \times 4$ matrix ($\mathbf{M}$) representing 5 Students across 4 Subjects.
- Executed Matrix Addition ($\mathbf{M} + \text{Bonus}$) and Transpose ($\mathbf{M}^T$).
- Computed the Gram Matrix ($\mathbf{M}\mathbf{M}^T$) to obtain pair-wise student inner products.
- Extracted a $4 \times 4$ square matrix to compute Determinant ($\det(\mathbf{A})$) and verified Matrix Inverse ($\mathbf{A}\mathbf{A}^{-1} = \mathbf{I}$).

### Part C: Linear Transformations & Geometry
- **2D Geometry (Line)**: Linear relationship across 2 subjects defined by equation $w_1 x_1 + b = 0$.
- **3D Geometry (Plane)**: Linear surface across 3 subjects defined by equation $w_1 x_1 + w_2 x_2 + b = 0$.
- **Higher Dimensions (Hyperplane)**: Multi-dimensional linear boundary across all 4 subjects defined by equation $\mathbf{w}^T\mathbf{x} + b = 0$.
- Demonstrated how hyperplanes serve as decision boundaries in Machine Learning models (e.g., SVMs and Linear Regression).

### Part D: Eigenvalues & Decomposition
- Calculated the $4 \times 4$ Subject Covariance Matrix ($\mathbf{\Sigma}$).
- Solved the characteristic equation $\mathbf{\Sigma}\mathbf{v} = \lambda\mathbf{v}$ to derive Eigenvalues ($\lambda$) and Eigenvectors ($\mathbf{v}$).
- Calculated the Explained Variance Ratio (%) to identify principal directions of maximum dataset spread (PCA foundation).

---

## 📊 Dataset Structure

The dataset contains performance marks across 4 core academic subjects:

| Student | Mathematics | Physics | Chemistry | Computer Science |
| :--- | :---: | :---: | :---: | :---: |
| **Student A** | 85 | 90 | 78 | 92 |
| **Student B** | 70 | 65 | 80 | 75 |
| **Student C** | 95 | 88 | 92 | 90 |
| **Student D** | 60 | 55 | 65 | 70 |
| **Student E** | 88 | 92 | 85 | 89 |

---

## ⚙️ Tech Stack & Dependencies

- **Language**: Python 3.x
- **Libraries Used**:
  - `numpy` — Linear algebra operations, matrix transformations, and eigenvalue decomposition.
  - `pandas` — Data structuring and tabular manipulation.
  - `matplotlib` — 2D and 3D spatial geometry plotting.

---
