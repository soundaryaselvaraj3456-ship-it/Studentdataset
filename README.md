Student Performance Analysis (250 Students) ** Overview**

The Student Performance Analysis project focuses on analyzing the academic performance of 250 students using data science and machine learning techniques. The dataset includes various attributes such as subject marks, attendance, department, and internal scores.

The main aim of this project is to identify patterns, understand the factors affecting student performance, and build a predictive model to estimate future performance. This helps in identifying high-performing and low-performing students and supports academic decision-making.

** Dataset Description**

The dataset used in this project is synthetically generated and contains 250 student records.

** Attributes Included: Student_ID → Unique identifier Name → Student name (generated using Faker) Gender → Male / Female Department → CSE / IT / ECE Year → 1st / 2nd / 3rd Maths → Marks (50–100) Science → Marks (50–100) English → Marks (40–100) Attendance (%) → 50–100 Internal Marks → 2–25

** The dataset simulates a real-world academic environment.

** Objectives To analyze student academic performance To identify key factors influencing marks To apply data preprocessing techniques To perform Exploratory Data Analysis (EDA) To build a machine learning model for prediction To generate insights for academic improvement

** Project Highlights

Synthetic dataset generation using Faker Data cleaning and preprocessing Detailed exploratory data analysis Machine learning model implementation Insightful visualizations and findings

Data preprocessing is an essential step to convert raw data into a clean and usable format.

** Steps Performed:

Checked missing values using isnull() Handled missing values using fillna() Removed duplicate records using drop_duplicates() Converted categorical variables into numerical using Label Encoding Applied feature scaling using StandardScaler Dropped unnecessary columns such as Student_ID and Name

EDA helps in understanding the structure, patterns, and relationships within the dataset.

** Analysis Performed:

Distribution of subject-wise marks Comparison across departments Gender-based performance analysis Relationship between attendance and marks Correlation between different features

** EDA provides meaningful insights and helps in better decision-making.

** Visualization

Visualization helps in presenting data insights in a clear and understandable way.

** Charts Used: Bar charts → Subject-wise performance Pie charts → Gender/Department distribution Scatter plots → Attendance vs Marks Heatmap → Feature correlation

** Tools and Technologies

Python Pandas NumPy Matplotlib Seaborn Scikit-learn Faker ** Results & Findings Students with higher attendance tend to score better marks Internal marks significantly influence overall performance Performance varies slightly across departments The machine learning model provides reliable predictions

** Pipeline Usage

Data Generation Data Loading Data Cleaning Data Preprocessing Exploratory Data Analysis Model Training Model Evaluation Prediction Generation ** Generating Predictions Input new student data (marks, attendance, etc.) The trained model predicts overall performance Helps in identifying students who may need improvement ** Future Improvements Use real-world datasets for better accuracy Apply advanced models (XGBoost, Neural Networks) Add more features (study hours, behavior, activities) Deploy as a web application Integrate dashboards using Power BI or Tableau ** Applications Academic performance monitoring Identifying weak students Supporting teachers in decision-making Improving educational strategies ** Limitations Dataset is synthetic (not real-world data) Limited number of features Small dataset size (250 records) ** Author



output screenshots


<img width="747" height="590" alt="image" src="https://github.com/user-attachments/assets/1a9954aa-16c0-4959-b9d0-73e1591937f6" />
<img width="790" height="686" alt="image" src="https://github.com/user-attachments/assets/22b40027-3b31-4f78-b2a5-2de4e4151df5" />
<img width="693" height="566" alt="image" src="https://github.com/user-attachments/assets/06bae954-c2ce-4f64-8856-199aa09972dd" />


** Conclusion

This project demonstrates how data science and machine learning can be used to analyze student performance and generate valuable insights. It helps in understanding academic patterns and provides a foundation for building intelligent educational systems.
