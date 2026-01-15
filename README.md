AI & ML Internship Task 1 – Dataset Understanding
Dataset Understanding & Data Types Analysis
🔍 Objective

The objective of this task is to understand the structure of a dataset, identify different types of data, analyze data quality, and evaluate the dataset’s suitability for Machine Learning.

📊 Dataset Used

Titanic Dataset

Source: Kaggle

🛠 Tools & Technologies

Python

Pandas

NumPy

Jupyter Notebook

VS Code

📌 Tasks Performed

Loaded the dataset using Pandas

Displayed first and last records of the dataset

Identified numerical, categorical, binary features

Analyzed data types using df.info()

Generated statistical summary using df.describe()

Checked missing values and data quality issues

Identified target variable and input features

Evaluated dataset size and ML suitability

🎯 Target Variable

Survived – Indicates whether a passenger survived or not

📈 Key Observations

Dataset contains 891 rows and 12 columns

Numerical features include: Age, Fare, SibSp, Parch

Categorical features include: Sex, Embarked, Ticket

Missing values found in Age, Cabin, and Embarked columns

Dataset is suitable for Machine Learning after preprocessing

Class imbalance is observed in the target variable

🧠 Learning Outcome

Understood importance of data exploration before modeling

Learned to identify different data types

Gained hands-on experience with Pandas for EDA

📂 Project Structure
AI_ML_Task_1/
│
├── dataset/
│   └── titanic.csv
│
├── task1_analysis.ipynb
├── README.md

✅ Conclusion

This task helped in understanding dataset characteristics, data quality issues, and Machine Learning readiness. Proper data understanding is a crucial step before applying any ML algorithms.
