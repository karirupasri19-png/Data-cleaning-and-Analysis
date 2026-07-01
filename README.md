📌 1. Project Title

Titanic Dataset – Data Cleaning & Exploratory Data Analysis (EDA)

📖 2. Project Description

This project focuses on cleaning and analyzing the Titanic dataset using Python.
The main objective is to preprocess the data, handle missing values, and visualize survival patterns.

📂 3. Dataset Information

The project uses three datasets:

🔹 train.csv
Contains training data
Includes target variable: Survived
Used for:
Data Cleaning
EDA
Model Training
🔹 test.csv
Contains test data
Does NOT include Survived
Used for prediction
🔹 gender_submission.csv
Sample output dataset
Contains:
PassengerId
Survived
Used for result comparison
🛠️ 4. Tools & Libraries Used
Python 🐍
Pandas
NumPy
Matplotlib
🧹 5. Data Cleaning Process
✅ Train Dataset
Filled missing values:
Age → Median
Embarked → Mode
Dropped column:
Cabin
Removed duplicate rows
Checked and corrected data types
✅ Test Dataset
Filled missing values:
Age → Median
Fare → Median
Dropped:
Cabin
Ensured consistency
✅ Gender Submission Dataset
Checked for missing values (none found)
Verified Survived values (0 and 1 only)
Removed duplicates if present
📊 6. Exploratory Data Analysis (EDA)

Performed basic analysis and visualization:

✔ Survival Count (Bar Chart)
✔ Survival Percentage (Pie Chart)
📈 7. Results & Insights
Most passengers did not survive
Survival data is binary (0 = Not Survived, 1 = Survived)
Clean dataset is ready for machine learning
