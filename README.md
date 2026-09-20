📊 Student Performance Analytics & Machine Learning PipelineAn end-to-end Data Science and Machine Learning project analyzing student academic performance based on demographic, social, and educational factors.

📌 Project Overview

This project performs Exploratory Data Analysis (EDA) and predictive modeling on the Student Performance in Exams dataset
.It covers two core machine learning workflows:Regression Model: 
Predicts continuous average exam scores across Math, Reading, and Writing.

Classification Model: 
Predicts student Pass/Fail status ($\ge 50\%$).

🛠️ Tech Stack & ToolsLanguage:

Python 3.8+Data Analysis & Visualization: Pandas, NumPy, Matplotlib, SeabornMachine Learning Pipeline: Scikit-Learn (ColumnTransformer, StandardScaler, OneHotEncoder, RandomForestRegressor, RandomForestClassifier)

📂 Project Structure├── student performance.csv  # Input Dataset
├── main.py                  # Full Data Pipeline Script
├── README.md                # Project Documentation
└── requirements.txt         # Required Python Dependencies
🚀 Quick Start GuideClone the Repository:git clone https://github.com/your-username/student-performance-analysis.git
cd student-performance-analysis

Install Dependencies:pip install pandas numpy matplotlib seaborn scikit-learn

Run the Script:python main.py

📈 Key FindingsTest Preparation: 
Students who completed test preparation courses scored significantly higher across all subjects.
Parental Education: Students whose parents hold higher degrees perform consistently better in academic exams.
Socioeconomic Influence: Access to standard lunch serves as a strong indicator of overall academic readiness.

📄 LicenseThis project is licensed under the MIT License - see the LICENSE file for details.
