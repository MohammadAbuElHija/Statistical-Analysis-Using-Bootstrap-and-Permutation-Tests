# Statistical Analysis Using Bootstrap and Permutation Tests

## Project Overview
This project focuses on applying **Bootstrap resampling** and **Permutation tests** to analyze statistical hypotheses. The primary objective is to estimate confidence intervals, conduct hypothesis testing, and compare different statistical inference methods in cases where variance estimation is challenging.

## Dataset
- **Source:** The dataset used in this project is from Kaggle: [Higher Education Predictors of Student Retention](https://www.kaggle.com/datasets/thedevastator/higher-education-predictors-of-student-retention).
- **Sample Size:** A subset of **200 observations** is randomly selected for analysis.

## Project Structure
The project consists of two main sections:

### 1. Linear Regression Analysis (Part A)
- **Objective:** Estimate confidence intervals for regression coefficients using multiple methods:
  - Normal approximation-based confidence intervals.
  - Bootstrap confidence intervals using **Standard Error (SE), Percentile, and Pivotal** approaches.
- **Steps:**
  1. Compute **confidence intervals for regression coefficients** using the normal approximation.
  2. Implement **Bootstrap-based confidence intervals** and compare interval widths.
  3. Predict **new observations** and construct confidence intervals for the predictions.

### 2. Hypothesis Testing Using Permutation Tests (Part B)
- **Objective:** Test whether a predictor variable's distribution differs across categories of a binary outcome variable.
- **Steps:**
  1. Define the research question regarding mean or median differences between groups.
  2. Use **permutation tests** to test for significant differences.
  3. Compare results with **parametric methods (Wald test, t-test)** where applicable.
  4. Assess normality assumptions and decide whether normal approximations are appropriate.
  5. Conduct **rank-sum tests** and compare with permutation results.

## Methodology
- **Bootstrap Resampling:** Used for confidence interval estimation without relying on standard error assumptions.
- **Permutation Tests:** Applied to test the null hypothesis without assuming normality.
- **Comparison of Methods:** The effectiveness of Bootstrap and Permutation methods is compared with traditional parametric approaches.

## Requirements
To run this project, install the required Python libraries:
```bash
pip install numpy pandas matplotlib seaborn scipy statsmodels
```

## How to Run
1. **Download the dataset** from Kaggle and place it in the project directory.
2. **Run the Jupyter Notebook (`project_analysis.ipynb`)** or execute the Python scripts.
3. **Review the outputs**, including regression results, hypothesis test conclusions, and confidence intervals.

## Results & Insights
- Confidence intervals obtained using **Bootstrap methods** were compared to parametric methods.
- **Permutation tests** provided robust insights into categorical data comparisons.
- The project highlights the advantages of non-parametric methods in cases where normality assumptions do not hold.

## Acknowledgments
- **Course Assignment:** Inspired by statistical methods covered in coursework.
- **Data Source:** [Higher Education Predictors of Student Retention](https://www.kaggle.com/datasets/thedevastator/higher-education-predictors-of-student-retention).

## Contact
For further inquiries, contact [Your Name] at [your.email@example.com].
