# Salary-Prediction-Using-Linear-Regression
Simple Regression Analysis using Power BI and DAX to calculate regression coefficients (slope and intercept) using the Least Squares Method and predict salary based on years of work experience.

---
### 1. Project Overview
---
This project applies Simple Linear Regression to analyse the relationship between years of work experience and salary, to predict salary based on an individual's years of experience.

The analysis was performed entirely in Microsoft Power BI, using DAX measures to calculate the regression components, establish the regression equation, and generate salary predictions.

Rather than relying on an automatically generated trendline, I calculated the slope and intercept using the Least Squares Method and applied the resulting equation to the prediction analysis.

---
### 2. Project Objectives
---
Analyse the relationship between years of experience and salary.

Apply Simple Linear Regression using the Least Squares Method.

Calculate the slope and intercept using DAX measures.

Develop a regression equation for salary prediction.

Estimate salaries based on different years of experience.

Present the analytical results through Power BI visualizations.

----
### 3. Dataset
---
The dataset contains two primary variables:

Years of Experience (X): The independent variable representing an individual's work experience.

Salary (Y): The dependent variable representing the corresponding salary.

---
### 4. Tools and Technologies
---
Microsoft Power BI

DAX (Data Analysis Expressions)

Data Visualization

Statistical Analysis

Simple Linear Regression

----
### 5. Analytical Methodology
---
Step 1: Data Preparation
Imported and examined the salary dataset to understand its structure and identify the variables required for the analysis.

Step 2: Regression Components Using DAX
Created DAX measures to calculate the statistical values required for Simple Linear Regression.

The measures included:

Measure	Description

n	Total number of observations

xy	Product of experience and salary

Exy	Sum of experience-salary products

Ex	Sum of years of experience

Ey	Sum of salaries

X²	Squared years of experience

Ex²	Sum of squared experience values

These calculations provided the necessary components for determining the regression coefficients.

Step 3: Calculating the Slope (A)
The slope was calculated using the Least Squares formula:

A = [nΣxy − (Σx × Σy)] / [nΣx² − (Σx)²]

The slope determines how much the predicted salary changes for each additional year of experience.


#Step 4: Calculating the Intercept (B)
The intercept was calculated using:

B = [(Σy × Σx²) − (Σx × Σxy)] / [nΣx² − (Σx)²]

The intercept represents the estimated salary when years of experience is zero.


Step 5: Developing the Regression Equation
After calculating the slope and intercept, the regression equation was established:

Y = AX + B

Where:

Y = Predicted salary

X = Years of experience

A = Slope

B = Intercept


Step 6: Salary Prediction
The calculated regression coefficients were applied to estimate salaries based on different years of experience.


Step 7: Visualization
Power BI was used to communicate the relationship between experience and salary and present the salary prediction analysis.

---

### 6. 

---
### 7. Key Analytical Concepts
---
Simple Linear Regression

Least Squares Method

DAX Measures

Regression Coefficients

Predictive Analysis

Data Visualization

---
### 8. Salary Prediction by Years of Experience


*This visualization illustrates the relationship between years of work experience and predicted salary outcomes.*


![Salary Prediction Analysis](Salary%20Prediction%20Analysis%20Prediction.png)






---
### 9. Conclusion
---
This project shows how you can implement mathematical and statistical concepts in Power BI using DAX.

By calculating the slope and intercept through the Least Squares Method, I developed a linear regression equation to estimate salaries based on years of work experience.

The project highlights the use of statistical analysis, DAX calculations, and data visualization to solve a real-world analytical problem.



---
Author: Esther Iyowu Olamide

Project: Salary Prediction Using Simple Linear Regression

Tool: Microsoft Power BI




