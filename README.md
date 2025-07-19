⚡ 5G Energy Consumption Modeling using Machine Learning

📡 A Predictive Approach to Optimize Energy Use in Telecom Base Stations

📍 Project Overview

This project was developed as part of a global data science challenge hosted by the International Telecommunication Union (ITU) in 2023. The objective was to design a machine learning regression model to accurately estimate energy consumption across 5G base stations (BSs) — the primary energy consumers in telecom networks.

📌 Context:
Network Operational Expenditure (OPEX) accounts for approximately 25% of telecom operators' total cost, with 90% of that tied to energy bills. Base stations alone consume over 70% of this energy, particularly within the Radio Access Network (RAN).

The aim was to model energy consumption using real operational data and identify patterns across network load, transmission power, and energy-saving configurations.

📊 Dataset Overview

The dataset, provided by the ITU, includes the following key variables:

Feature	Description:

BS	Base Station ID
ENERGY	Target variable: Energy consumed
LOAD	Network traffic or demand
ESMODE	Energy-saving mode setting
TX POWER	Transmission power
TIME IN SECONDS	Time of day (in seconds)
YEAR	Year of record
MONTH	Month of record
DAY	Day of the month

🧠 Machine Learning Approach

1. Data Preprocessing

Cleaned and explored the dataset using pandas profiling

Handled missing values, outliers, and duplicates

Encoded categorical features and prepared time-based variables


2. Model Development

Selected ENERGY as the target variable (y)

Used variables like LOAD, ESMODE, TX POWER, TIME IN SECONDS, and date components as features (X)

Split the data into training and testing sets

Trained a regression model (e.g., Random Forest Regressor) based on exploratory insights

3. Evaluation Metrics

Metric	Value	Interpretation

MAE	1.552	Avg. prediction error is ~1.55 units
MSE	6.469	Low squared error; large errors are rare
RMSE	2.543	Typical error in actual units (energy usage)
R² Score	0.959	Model explains 95.9% of the variance in ENERGY

** Business & Environmental Impact

This model can empower telecom operators to:

🔍 Predict and manage energy consumption

💰 Reduce OPEX by optimizing energy usage

🌱 Promote sustainable operations with data-driven energy-saving strategies


🛠 Tools & Technologies Used

Python

Pandas, NumPy, Matplotlib, Seaborn

Scikit-learn for model building

YData Profiling for exploratory data analysis

Jupyter Notebook for development and presentation


📫 Contact & Collaboration

If you're interested in collaborating on real-world ML solutions for energy optimization or telecom sustainability, feel free to connect!

👩‍💻 Gom Mirian 
📧 gommirian88@gmail.com
