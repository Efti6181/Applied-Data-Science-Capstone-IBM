# Applied-Data-Science-Capstone-IBM
# Overview
The Applied Data Science Capstone Project serves as the culminating experience of the IBM Data Science Professional Certificate specialization. This project synthesizes the knowledge and skills acquired throughout the course series, culminating in a comprehensive analysis and predictive modeling exercise.

# Project Background
SpaceX has emerged as a pioneering force in the commercial space industry, revolutionizing space travel by significantly reducing costs. The company offers Falcon 9 rocket launches at a competitive price of 
626million,instarkcontrasttootherproviderswhosecostsexceed
62million,instarkcontrasttootherproviderswhosecostsexceed165 million. A key factor contributing to this cost efficiency is SpaceX's innovative approach to reusing the first stage of its rockets. By accurately predicting whether the first stage will successfully land, we can gain insights into the overall cost-effectiveness of a launch. This project aims to leverage publicly available data and machine learning techniques to forecast the likelihood of first-stage reusability.

# Research Questions
This project seeks to address several critical questions:

How do various factors, such as payload mass, launch site, number of previous flights, and orbital parameters, influence the success rate of first-stage landings?
Has there been a noticeable trend in the rate of successful landings over the years?
Which machine learning algorithms are most effective for binary classification in this context?
# Methodology
1. Data Collection
API Utilization: We will harness the capabilities of the SpaceX REST API to gather relevant data on launches, including details about payloads, launch sites, and landing outcomes.
Web Scraping: Additional data will be extracted from Wikipedia and other reputable sources to enrich our dataset and provide a comprehensive view of the factors influencing launch success.
2. Data Wrangling
Data Filtering: The collected data will undergo rigorous filtering to ensure relevance and accuracy.
Handling Missing Values: Strategies will be implemented to address any missing data points, ensuring the integrity of our analysis.
One-Hot Encoding: Categorical variables will be transformed using one-hot encoding to prepare the dataset for binary classification modeling.
3. Exploratory Data Analysis (EDA)
Visualization Techniques: We will employ various visualization tools to explore the data, identify patterns, and uncover insights.
SQL Analysis: SQL queries will be utilized to perform in-depth analyses of the dataset, facilitating a better understanding of the relationships between variables.
4. Interactive Visual Analytics
Folium and Plotly Dash: Interactive visualizations will be created using Folium for geographical data representation and Plotly Dash for dynamic dashboards, allowing for an engaging exploration of the data.
5. Predictive Analysis
Model Development: We will build, tune, and evaluate multiple classification models to determine the most effective algorithm for predicting first-stage landing success.
Performance Metrics: Various performance metrics, such as accuracy, precision, recall, and F1-score, will be employed to assess the models and ensure optimal results.
# Conclusion
This capstone project not only aims to predict the success of SpaceX's first-stage landings but also seeks to provide valuable insights into the factors that influence these outcomes. By leveraging advanced data science techniques and methodologies, we hope to contribute to the understanding of the commercial space industry and the innovative practices that drive its success.
