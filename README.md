This repository contains the Exploratory Data Analysis (EDA) performed on the Titanic Dataset as part of Task 5 – Data Analyst Internship.
Objective

To explore, analyze, and understand key patterns, trends, and relationships in the Titanic dataset using Python libraries such as Pandas, Matplotlib, and Seaborn.

Files in This Repository
File	Description
Titanic_EDA.ipynb	Jupyter Notebook containing the full EDA code
Titanic_EDA_Report.pdf	PDF report summarizing insights
train.csv	Titanic dataset used for analysis
README.md	Explanation of task, steps, and findings

Tools & Libraries Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Jupyter Notebook

Steps Performed
Loaded dataset and inspected structure using .info(), .describe(), .head().
Checked missing values and data types.
Univariate Analysis
Histograms (Age, Fare)
Countplots (Sex, Pclass, Embarked, Survived)
Bivariate Analysis
Survival vs Sex
Survival vs Pclass
Age vs Survival
Fare vs Survival
Correlation Analysis
Heatmap for numeric features
Pairplot for multivariate patterns
Insights & observations for every plot.
Final summary based on findings.
Exported the insights into a PDF report.

Key Insights
Females had a much higher survival rate than males.
1st class passengers survived significantly more than 3rd class passengers.
Passengers who paid higher fares had better survival chances.
Most passengers were between 20–40 years old.
The dataset contains missing values in Age, Cabin, and Embarked.

Conclusion
This analysis reveals that gender, passenger class, and fare were major factors influencing Titanic survival. The EDA helps understand social and demographic patterns behind the tragedy.

How to Run
Clone the repository
Install required libraries:
pip install pandas numpy matplotlib seaborn

Open Jupyter Notebook:
jupyter notebook
Run Titanic_EDA.ipynb
