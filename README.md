# Advancing Healthcare with AI-PyTorch-based Deep Learning Model and AutoML
This repository contains the code and analysis for a project focused on disease prevalence in the United States. The project utilizes two separate datasets: one containing estimates of chronic illness for various age groups, states, populations, and health categories, and the other containing variables such as states, race, ten-year age groups, and population percentages.

# Introduction

The aim of this project is to analyze disease prevalence in the United States between 2019 and 2020 across different groups and measures. The project involves identifying patterns and trends in the data, building predictive models using Random Forest and Deep Neural Networking techniques, and exploring the factors that contribute to disease prevalence. The insights and predictions from this analysis can aid in decision-making processes related to public health interventions, resource allocation, and policy development.

# Data Sources: -
1.) https://wonder.cdc.gov/controller/datarequest/D176

2.) https://chronicdata.cdc.gov/500-Cities-Places/PLACES-Local-Data-for-Better-Health-County-Data-20/swc5-untb

1. **First Dataset:**
- This dataset appears to contain information related to various health measures or indicators across different states and between 2019-2020.
2. **Second Dataset:**
- This dataset seems to provide information about population demographics, specifically focusing on age groups and racial categories within different states.
   
Both datasets contain different types of information, with the first dataset focusing on health measures and the second dataset focusing on population demographics. They can potentially be used for analyzing health trends, studying population characteristics, or conducting research related to health and demographics.

## 🔗 Links
[Code](https://github.com/Abhiashu10/Advancing-Healthcare-PyTorch-DeepLearningModel-AutoML/blob/83da50fcd990fa356dff371ddaa4614fca2cf2ac/Healthcare-Disease_Analysis.ipynb)

# Data Preprocessing 
To prepare the data for further analysis and modeling, data manipulation and feature engineering techniques are applied. This involves:

Merging the two datasets based on the state category.
Dropping unnecessary columns and renaming columns for better clarity.
Melting and pivoting the data to transform it from wide format to long format.
Converting categorical variables into dummy variables for modeling purposes.
Splitting the geolocation column into longitude and latitude columns for mapping purposes.
Predictive Analysis

The predictive analysis phase focuses on building models to predict disease prevalence. The models used in this project include Random Forest and Deep Neural Network models. The steps involved in predictive analysis are:

# Data Modelling
1.) Analyzing the feature importance of the Random Forest models.
2.) Implementing AutoML to select the best model option.
3.) Building Deep Neural Network models with various architectures and training them using the dataset.
4.) Evaluating the performance of the trained models using metrics such as Mean Squared Error and R-squared.
5.) Comparing the predicted values with the actual values and visualizing the results.

# Conclusion

The project provides valuable insights into disease prevalence in the United States and develops predictive models to estimate disease prevalence based on various factors. The analysis and models can support decision-making processes related to public health interventions, resource allocation, and policy development. It is important to note that further research, data refinement, and model optimization may be necessary to improve the accuracy and generalizability of the predictive models in real-world scenarios.
