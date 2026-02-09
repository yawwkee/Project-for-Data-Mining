# Project-for-Data-Mining
💤 Sleep Health and Lifestyle Analysis
📌 Project Overview
This project analyzes the impact of lifestyle and physiological factors on sleep quality and duration. Using the Sleep Health and Lifestyle Dataset, I investigated how variables such as stress levels, occupation, physical activity, and BMI affect sleep patterns.

The project covers the entire Data Science pipeline: data acquisition, preprocessing, Exploratory Data Analysis (EDA), and building a Machine Learning model to predict sleep disorders.

📂 Dataset
The dataset was obtained from Kaggle.
Rows: 374
Columns: 13
Key Features: Age, Occupation, Sleep Duration, Quality of Sleep, Physical Activity Level, Stress Level, BMI Category, Heart Rate, Daily Steps, Blood Pressure.
🛠️ Technologies Used
Python (Data Analysis & Modeling)
Pandas & NumPy (Data Manipulation)
Matplotlib & Seaborn (Data Visualization)
Scikit-Learn (Machine Learning: Decision Tree Classifier)
⚙️ Key Steps & Methodology
1. Data Preprocessing 
Blood Pressure: Split the Blood Pressure column (e.g., "126/83") into two numerical columns: Systolic_BP and Diastolic_BP.
BMI Standardization: Merged duplicate categories ("Normal" and "Normal Weight") into a single category.
Missing Values: Handled NaN values in the Sleep Disorder column by replacing them with "None" (indicating no disorder).
2. Exploratory Data Analysis (EDA) 
I created several visualizations to understand the data relationships:
Correlation Matrix: Revealed a strong negative correlation (-0.90) between Stress Level and Quality of Sleep.
Occupation Analysis: Sales Representatives have the shortest average sleep duration (< 6 hours), while Engineers sleep the most.
BMI Impact: Confirmed that Overweight and Obese individuals are significantly more likely to suffer from Sleep Apnea and Insomnia.
3. Machine Learning Model 
Goal: Predict whether a person has a sleep disorder based on lifestyle factors.
Algorithm: Decision Tree Classifier.
Data Split: 80% Training / 20% Testing.
Result: The model achieved an Accuracy of 88% on the test set.
📊 Key Insights
Stress is the biggest enemy of sleep: High stress levels drastically reduce reported sleep quality.
Weight matters: There is a clear link between high BMI and sleep disorders like Apnea.
Career influence: High-pressure jobs (Sales) correlate with less sleep compared to more stable professions (Engineering).
🚀 How to Run
Clone the repository:
Bash
git clone https://github.com/your-username/sleep-health-analysis.git
Install dependencies:
Bash
pip install pandas matplotlib seaborn scikit-learn
Open the Jupyter Notebook:
Bash
jupyter notebook Projekt_Kod.ipynb
👨‍💻 Author
Pavlo Mysiuk

Data Engineering Student at WSIiZ Rzeszów.
