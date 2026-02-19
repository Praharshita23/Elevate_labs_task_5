# Exploratory Data Analysis – Titanic Dataset

## Internship Task
Data Analyst Internship – Elevate Labs - Task 5 
Task 5: Exploratory Data Analysis (EDA)

---

## Objective
- To perform exploratory data analysis on the Titanic dataset.
- To identify patterns, trends, and relationships affecting survival.
- To understand feature distributions and correlations.

---

## Dataset Overview
- Total Observations: 891 passengers
- Total Features (after preprocessing): 9
- Target Variable: Survived (0 = Did Not Survive, 1 = Survived)
- Dataset Type: Binary Classification Dataset

### Key Features:
- Pclass – Passenger Class
- Sex – Gender
- Age – Age in years
- SibSp – Number of siblings/spouses aboard
- Parch – Number of parents/children aboard
- Fare – Ticket fare
- Embarked – Port of boarding

---

## Data Cleaning & Preprocessing
- Dropped unnecessary columns: PassengerId, Name, Ticket
- Handled missing values
- Encoded categorical variables (Sex, Embarked)
- Checked skewness and outliers

---

## Exploratory Data Analysis

### Univariate Analysis
- Most passengers were aged 20–40 years.
- Fare distribution is highly positively skewed.
- Majority of passengers traveled alone.
- Most passengers embarked from Southampton (S).

### Bivariate Analysis
- Females had significantly higher survival rates than males.
- 1st class passengers had higher survival probability.
- Higher fare is associated with higher survival.
- Family size has limited impact on survival.

### Correlation Analysis
- Sex shows strong positive correlation with survival.
- Pclass has negative correlation with survival.
- Fare positively correlates with survival.
- Age has weak correlation with survival.

---

## Key Insights
- Overall survival rate is approximately 38%.
- Gender and passenger class are the strongest factors influencing survival.
- Socio-economic status (Fare & Pclass) played a major role.
- Fare distribution contains significant outliers.
- Age and family-related features have weaker influence compared to gender and class.

---

## 🛠 Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## 📁 Files Included
- task_5.ipynb
- task_5_EDA_Report.pdf
- Dataset file

---

## 📌 Conclusion
The EDA revealed clear survival patterns based on gender, passenger class, and fare. These insights provide a strong foundation for predictive modeling and further machine learning applications.
