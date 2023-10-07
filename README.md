# On Time Analysis of US Flight Delays

### Overview
This repository contains the code and resources for a comprehensive flight delay prediction project. Predicting flight delays accurately is a crucial task in the aviation industry, with implications for operational efficiency, customer satisfaction, cost savings, and gaining a competitive edge. This project provides a framework for:
1. Analyzing large volumes of historical flight data by outlining several key questions to better understand the impact of delays and predictive model-building.
2. And allows for practicing of efficient algorithmic approaches to optimise data manipulation in order to analyse large volumes of historical data.

### Data Source
We'll be using three years (2006-2007) of US domestic flight data was sourced from the ASA Statistical Computing Data Expo 2009: Airline on time data (https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/HG7NV7)

### Key Features & Project Structure
**Data Exploration**: The project begins with thorough data exploration and analysis, examining historical flight data to identify period patterns and trends in flight delay performance, route frequency weightage, and more.

**Cascading Delay Analysis**: Building upon the EDA, the project investigated the concept of cascading delays, where delays at one airport can impact subsequent flights. This analysis helped understand the ripple effects of delays in the aviation network.

**Predictive Modeling**: The core of the project involved building a predictive model for flight delays. The Support Vector Regression (SVR) model was selected based on evaluations of academic literature on its performance and suitability for applied delay prediction.

**Model Evaluation**: The model was rigorously evaluated using various metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared (R2) to assess their performance.

**Hyperparameter Tuning**: Hyperparameter tuning was applied to optimize the predictive models, ensuring they perform at their best.

**Cross-Validation**: Cross-validation was used to prevent overfitting and ensure the model generalized well to unseen data.

**--Getting Started--**
To get started with this project, follow these steps:

**Clone the Repository**: Begin by cloning this Git repository to your local machine.

type 'git clone https://github.com/wwh9345/On-Time-Analysis-US-Flight-Delays.git'

**Install Dependencies**: Make sure you have Python, R and the required libraries installed in order to run the relevant notebooks/markdowns properly. You can run the requirements.py script first to install the libraries. 

**Explore the Notebooks**: Dive into the Jupyter notebooks. These notebooks contain detailed code, explanations, and visualizations for each step of the project.

**Run the Code**: Feel free to run the code in the notebooks, experiment with different models, and explore the data. Customize the project to suit your specific requirements.

**Contribute**: If you find issues, have improvements to suggest, or want to contribute to this project, please open a pull request or issue on the repository.

### Conclusion
Due to the sheer amount of factors and data that influence operations in the commercial aviation sector, it can be mind-boggling to start on something. Feel free to explore the notebooks, experiment with different techniques, and adapt the project to your specific use cases. I hope this project gives you valuable insights in the process for data analysis and predictive modelling!
