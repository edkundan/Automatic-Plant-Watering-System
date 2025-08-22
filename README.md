Automatic Plant Watering System - Data Analysis
This repository contains the data analysis and visualization project for an automatic plant watering system, completed as part of an internship. The goal of this project is to preprocess sensor data, uncover key insights, and visualize the findings using Python and Power BI.



📊 Project Overview
This project follows a structured data analysis workflow:

Data Gathering: The dataset used is the "TARP" dataset from Kaggle, containing sensor readings like soil moisture, temperature, and humidity.

Data Cleaning: The raw data was cleaned to handle missing values, remove duplicates, and correct data types, ensuring data integrity.

Feature Engineering: A new, meaningful feature called 'Moisture Level' (Low, Medium, High) was created from the 'Soil Moisture' data to provide better insights.

Data Visualization: Key charts were created using Python (Matplotlib & Seaborn) to discover patterns and understand the system's behavior.

🚀 How to Run the Project
Prerequisites
Python 3.8+

Pandas

Matplotlib

Seaborn

Setup
Clone the repository:

git clone <your-repository-url>
cd <your-repository-name>

Place the dataset:
Download the TARP.csv file and place it inside the /data folder.

Install the required libraries:

pip install pandas matplotlib seaborn

Running the Analysis Script
To generate the cleaned CSV file and all the visualizations, run the Python script from the root directory:

python scripts/analysis_script.py

This will create cleaned_for_powerbi.csv in the /data folder and all the .png chart files in the /visualizations folder.

📈 Key Findings
The analysis revealed a clear and logical story about the system's operation:

Soil Moisture is Key: The most significant finding is that Soil Moisture is the primary factor that determines when the watering system turns ON or OFF. The system activates when moisture is high and deactivates when it's low.

Balanced Data: The dataset is well-balanced between "ON" and "OFF" states, which makes the analysis reliable.

Independent Features: The main sensor readings (temperature, humidity, etc.) do not have a strong correlation with each other, meaning they provide independent value to the analysis.

🛠️ Tools Used
Data Analysis: Python, Pandas

Data Visualization: Matplotlib, Seaborn

Dashboarding: Power BI
