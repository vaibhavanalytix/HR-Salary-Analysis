# HR Salary Analysis using Hypothesis Testing

## Project Overview
This project analyzes employee salary data to determine whether salary differences are statistically significant based on gender and department.

## Dataset
- Source: IBM HR Analytics Employee Attrition Dataset (Kaggle)
- Records: 1470 employees
- Features used: Gender, Department, JobRole, MonthlyIncome

## Tools & Libraries
- Python, Pandas, NumPy
- Matplotlib, Seaborn
- SciPy (Stats)

## Key Findings
- No significant gender pay gap found (T-Test, P-Value = 0.2222)
- Department is a significant salary driver (ANOVA, P-Value = 0.0410)
- Sales department has the highest average salary

## Project Structure
HR_Salary_Analysis/
├── Data/
├── Images/
├── Notebooks/
│   └── hr_salary_analysis.ipynb
└── README.md