# Statistics & Linear Algebra Assignment

This repository contains theory answers and practical Python implementations for core concepts in Statistics, Probability, and Linear Algebra.

---

## 📌 Project Overview

- **Part A (Theory):** Fundamental concepts of central tendency, dispersion, probability distributions, Bayes' Theorem, and Linear Algebra[cite: 2].
- **Part B (Practical):** Python implementation using Pandas, NumPy, Matplotlib, Seaborn, and SciPy for data analysis, visualizations, and vector operations.

---

## 📚 Part A: Theory Summary

### 1. Central Tendency
- **Mean:** Average of all values[cite: 2].
- **Median:** Middle value when data is ordered[cite: 2].
- **Mode:** Most frequent value in the dataset[cite: 2].

### 2. Measures of Dispersion
- **Variance:** Average squared difference from the mean (unit²)[cite: 2].
- **Standard Deviation:** Square root of variance (same unit as data)[cite: 2].

### 3. Distributions & Shapes
- **Normal Distribution:** Bell-shaped continuous distribution where Mean = Median = Mode[cite: 2]. Follows the 68–95–99.7 Empirical Rule[cite: 2].
- **Skewness:** Measures asymmetry (Positive = Right tail, Negative = Left tail)[cite: 2].
- **Kurtosis:** Measures peak sharpness and tail heaviness[cite: 2].

### 4. Probability Concepts
- **Theoretical vs. Empirical:** Theoretical uses mathematical logic ($P(E) = \frac{\text{Favorable}}{\text{Total}}$); Empirical uses experimental/historical data[cite: 2].
- **Independent vs. Dependent:** Independent events do not affect each other; Dependent events do[cite: 2].
- **Bayes' Theorem:** Prior belief updating using new evidence:
  $$P(A\vert{}B) = \frac{P(B\vert{}A) \cdot P(A)}{P(B)}$$
[cite: 2]

### 5. Linear Algebra
- **Eigenvector:** Vector whose direction remains unchanged during a linear transformation[cite: 2].
- **Eigenvalue ($\lambda$):** Scaler factor by which the eigenvector stretches or shrinks[cite: 2].
  $$A\mathbf{v} = \lambda\mathbf{v}$$
[cite: 2]

---

## 💻 Part B: Practical Tasks (Python)

### Step 1: Central Tendency & Dispersion
- Mean, Median, and Mode calculation for `Math_Score`.
- Range, Variance, and Standard Deviation calculation for `Science_Score`.

### Step 2: Probability Basics
- Overall probability of passing ($P(\text{Pass\Fail} = 1)$).
- Contingency table creation between `Pass_Fail` and `Hours_Studied > 5`.
- Conditional Probability: $P(\text{Pass} \mid \text{Hours\Studied} > 5)$.

### Step 3: Distribution & Visualization
- Histogram overlaid with fitted Normal Curve for `Math_Score`.
- Skewness & Kurtosis calculation for `Science_Score`.
- Quantile-Quantile (Q-Q) plot for `English_Score`.

### Step 4: Linear Algebra Mini Task
- Vector representation of the first 5 students' `Math_Score` and `Science_Score`.
- Dot Product computation between vectors.
- $L_1$ Norm (Manhattan) and $L_2$ Norm (Euclidean) of `Math_Score` vector.
- Angle calculation (in radians and degrees) between vectors using Cosine Similarity.

---

## 🛠️ Tech Stack & Requirements

- **Language:** Python 3.x
- **Libraries Required:**
  ```bash
  pip install numpy pandas matplotlib seaborn scipy
