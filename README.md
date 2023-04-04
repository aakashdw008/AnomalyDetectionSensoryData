# Anomaly Detection on Sensory Data 
Problem Statement:
XYZ Company is a manufacturer of household cleaning products, operating across four different countries with an annual revenue of USD 800 million. Their manufacturing plant relies on over 30 industrial pumps to produce their range of detergents, shampoos, and other cleaning supplies. Recently, one of their pumps has failed unexpectedly seven times in the last six months, causing significant production losses estimated at USD 500,000, in addition to environmental damage caused by spilled toxic chemicals amounting to USD 300,000. To avoid such problems in the future, XYZ Company is keen to identify anomalies in pump behavior and take corrective action before the pump fails. By implementing a system that can detect and flag unusual pump behavior, the company aims to prevent any hard failures and minimize production losses and environmental damage.
Data: https://www.kaggle.com/datasets/nphantawee/pump-sensor-data
Problem Context:
Manufacturing industry relies on heavy machinery, including motors, pumps, pipes, furnaces, and conveyors. Asset Management programs prioritize equipment integrity and reliability to avoid production losses, which can result in financial losses of hundreds of thousands or millions of dollars. Robust Asset Management frameworks, including skilled Reliability Engineers, can detect anomalies and prevent unplanned downtime, unnecessary maintenance, and critical component shortages. These prevention measures can save manufacturing plants significant financial losses due to unplanned downtime, maintenance costs, and excess or shortage of critical components
Solution:
Model with good accuracy score with zero rework
Scope
This project focuses solely on identifying anomalies in the 53 sensors of the chosen pump and does not encompass other pumps. It also does not involve predicting potential pump failures.
Solution
My approach involves creating a benchmark model using the IQR technique, and then implementing two other unsupervised learning algorithms to compare their performances and accuracies. To achieve this, I will undertake the following steps:
•	Source and load the data
•	Perform data wrangling
•	Conduct Exploratory Data Analysis (EDA)
•	Carry out pre-processing and feature engineering
•	Develop models: IQR and K-Means
•	Evaluate the models:
Result of Analysis:
Kmeans comes on top v/s IQR model with accuracy of 87.7% v/s 86.6%

