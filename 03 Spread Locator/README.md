# 📊 Spread Locator

### Mathematics & Advanced Statistics

## 📌 Project Overview

**Spread Locator** is a statistical distribution analysis project based on e-commerce transaction data.

The project analyzes **daily transaction amounts and transaction behavior** to understand different probability distributions, data skewness, transformations, and probability patterns.

---

## 🎯 Objectives

The main objectives of this project are:

* Understand statistical distributions.
* Analyze transaction occurrence and frequency.
* Apply Bernoulli, Binomial, and Poisson distributions.
* Compare Log-Normal and Power Law distributions.
* Generate and interpret Q-Q plots.
* Apply Box-Cox transformation.
* Calculate Z-scores and probabilities.
* Analyze PDF and CDF.
* Identify the distribution that best represents the transaction data.

---

## 📊 Dataset

The dataset contains e-commerce transaction records with the following fields:

| Field                | Description                       |
| -------------------- | --------------------------------- |
| `transaction_id`     | Unique transaction ID             |
| `customer_id`        | Unique customer ID                |
| `transaction_amount` | Transaction amount in ₹           |
| `transaction_date`   | Date of transaction               |
| `transaction_count`  | Number of transactions            |
| `region`             | Customer region                   |
| `transaction_status` | Transaction status (Success/Fail) |

---

## 📚 Topics Covered

### Part A – Theory

The project covers:

* Statistical Distributions
* Q-Q Plot
* Discrete vs Continuous Distributions
* Bernoulli Distribution
* Binomial Distribution
* Log-Normal Distribution
* Power Law Distribution
* Box-Cox Transformation
* Poisson Distribution
* Z-score Probability
* PDF and CDF

### Part B – Practical Analysis

The following analyses are performed:

1. Bernoulli and Binomial distribution analysis.
2. Poisson distribution for daily transactions.
3. Log-Normal and Power Law modeling.
4. Q-Q Plot for normality analysis.
5. Box-Cox transformation.
6. Z-score and probability of transactions above ₹5000.
7. PDF and CDF visualization.
8. Distribution comparison and final interpretation.

---

## 🛠️ Technologies Used

* Python
* NumPy
* Pandas
* SciPy
* Statsmodels
* Matplotlib
* Seaborn
* Jupyter Notebook
* GitHub

---

## 📁 Project Structure

```text id="x6o6r8"
Spread-Locator/
│
├── README.md
├── transaction_data.csv
├── Spread_Locator.ipynb
└── Spread_Locator_Theory.pdf
```

---

## 📈 Analysis Output

The project includes:

* Distribution calculations
* Q-Q Plot
* Box-Cox transformation
* Z-score calculations
* Probability analysis
* PDF and CDF plots
* Distribution comparison
* Statistical interpretations

---

## 🔍 Final Analysis

The transaction amount data is analyzed using multiple statistical distributions and transformations.

The final conclusion identifies the distribution that provides the most suitable representation of the transaction data based on the analysis and visualizations.

---

## ✅ Conclusion

This project demonstrates how probability distributions and statistical transformations can be applied to e-commerce transaction data. It provides practical experience in analyzing transaction patterns, understanding skewed data, and deriving useful probability-based insights for decision-making.
