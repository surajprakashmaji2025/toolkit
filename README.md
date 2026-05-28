# Normality Test Toolkit
## Tools and Methods of Data Analysis
### Overview
This toolkit tests whether a dataset follows a normal distribution using statistical tests and visualizations.

### Dataset
AI Dependency, Career Anxiety and Student Burnout, https://www.kaggle.com/datasets/sridipbasu/ai-depndency-career-anxiety-and-student-burnout

Column analysed: burnout_score (n = 200 random samples)

### Toolkit Contents
1. PDF Plot — KDE curve of the data
2. Fitted Normal Distribution — red curve overlay + goodness of fit
3. Q-Q Plot — visual normality check
4. Normality Tests — Shapiro-Wilk, Kolmogorov-Smirnov, Anderson-Darling
5. Conclusion — interpretation of results

### Results Summary
| Test               | Statistic | p-value |
|--------------------|-----------|---------|
| Shapiro-Wilk       | 0.9682    | 0.0002  |
| Kolmogorov-Smirnov | 0.1244    | 0.0037  |
| Anderson-Darling   | 2.3107    | < 0.05  |

### How to Run
Open Normality_toolkit.ipynb in Google Colab or Jupyter Notebook. Upload the dataset file and run all cells in order.

### Libraries Used
- pandas
- numpy
- matplotlib
- scipy
