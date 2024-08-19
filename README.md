Hello world;
Today I want to share with you a data science project from start to finish. This project was created as a miuul data scientist bootcamp graduation project.
The goal of our project is to make historical analyses and long-term sales predictions using three years of sales data from Rossmann, a retail brand that provides service worldwide.

1- Dataset Content
This dataset contains 3 years of data from 1115 unique stores. The dataset contains variables that affect sales status such as date, sale, customer, promotion, distance between stores. The dataset consists of 1,000,000+ rows and 17 columns.

2-🔍 Problem Identification:
Rossmann’s challenge was to optimize inventory management by accurately forecasting sales, which would reduce excess stock and minimize stock shortages across its stores.

3-📈 EDA and Data Preprocessing
At this stage, firstly the data set size was reduced to create a meaningful sample in order to facilitate the study and avoid loss of time.
In the EDA section, missing observations and anomalies were detected. Statistical tests were applied to answer the question of whether some variables have a direct relationship with sales.
In the Data Preprocessing section, these anomalies were eliminated and necessary actions were taken for missing observations. Type conversions of variables were made.

4.🛠️ Feature Engineering:
 We introduced new features such as lagged sales data, rolling averages, and interaction terms between promotions and holidays to enhance the prediction accuracy.
 Key Features Added:
📅 Temporal Variables: Day, Month, Year, IsWeekend, etc.
⏳ Lagged Features: Sales values lagged by 1, 7, and 30 days.
📈 Rolling Features: 7 and 30-day rolling means, sums, and standard deviations of sales.
📊 Exponential Moving Averages: For a more responsive trend analysis.

5-🤖Modeling
At this stage, models such as LGBM, ARIMA, SARIMAX were used for sales forecast modeling. By looking at the results of these models, the LGBM model gave the most appropriate sales forecast results for the targeted criteria.
6- 📊Analysis and Results
The LGBM model achieved lower MAE and SMAPE values compared to other models. Based on this, we can say that the results of the LGBM model can be taken into consideration in planning future sales, supply chain and logistics processes.
•Key Insights:
📉 Sales Trends: Varied significantly across different store types and were influenced by seasonal factors like the Christmas season.
•📆 Interaction Terms: Promotions during holidays had a noticeable impact on sales, effectively captured by our model.

5.📊 Visualization and Presentation:
Of course, when it comes to sales, colorful graphics have to be visible. We used PowerBI to create our charts and interactive tables, making the results visual and easy to explain and understand.


This project is maintained by Semih Angin, Mustafa Emircan Isik, Semih Babacan, Merve Ates and Okan Erkal. Contributions are welcome. Please open an issue first to discuss proposed changes.
