🐍 Python Fundamentals Capstone Project
📌 Project Overview

This repository contains my solution to the Python Fundamentals Capstone Project.
The project focuses on data cleaning, transformation, and analysis of a retail-oriented dataset using Pandas and NumPy.

The goal was to apply fundamental Python concepts to derive key business insights while practicing real-world data wrangling tasks.

📓 The solution is implemented in a Jupyter Notebook: capstone.ipynb
Each section of the notebook tackles a specific data task step by step.

📂 Dataset

The project uses three CSV files representing different aspects of the business:

📑 project_df.csv → Project details, including costs & completion status.

👥 employee_df.csv → Employee information (name, gender, city, age).

🎖 seniority_df.csv → Maps employee IDs to their designation levels.

🛠 Tasks Performed

This capstone covered 10 key tasks, showcasing practical data wrangling & manipulation skills:

📥 Data Ingestion → Created and saved datasets as CSV files.

🔧 Missing Value Imputation → Replaced missing values in Cost with the running average using a for loop.

✂️ Data Transformation → Split the Name column into First Name & Last Name and dropped the original.

🔗 Data Integration → Merged all three DataFrames into a single Final DataFrame.

💰 Conditional Calculations → Added a Bonus column (5% bonus for employees who completed their projects).

📉 Conditional Updates & Filtering → Demoted employees from failed projects and removed records with designation level > 4.

🏷 Categorical Data Handling → Added "Mr." or "Mrs." prefix to names based on gender, then dropped the Gender column.

⬆️ Conditional Promotion → Promoted employees older than 29 years.

📊 Data Aggregation → Calculated total project cost per employee and saved results in a new DataFrame.

🔍 Pattern Matching → Filtered employees whose city name contained the letter "o".

⚙️ Technologies & Skills

🐍 Python → Core programming language

🐼 Pandas → Data manipulation, cleaning, joining & aggregation

🔢 NumPy → Handling missing values & numerical operations

📓 Jupyter Notebook → Interactive environment for coding & analysis

✨ Key Takeaways

Learned how to handle missing data with custom logic.

Applied joins, filters, and conditional updates for real-world scenarios.

Strengthened skills in data wrangling and business insight generation.

🔗 This project reflects my journey of applying Python fundamentals to solve structured business problems. 🚀

