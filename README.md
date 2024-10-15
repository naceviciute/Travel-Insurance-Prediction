# Travel Insurance Prediction

### Introduction

This notebook analyses Travel Insurance Prediction dataset downloaded from [Kaggle](https://www.kaggle.com/datasets/tejashvi14/travel-insurance-prediction-data). 

Identifying characteristics of individuals interested in travel insurance is crucial for targeting new customers efficiently and saving resources.

### Goal

The goal of this project is to create a model that identifies clients that are most likely to buy travel insurance.

### Objectives

To achieve this goal, the following objectives have been established:

- Download, load and clean the dataset.
- Conduct exploratory data analysis and visualize data to identify underlying patterns.
- Perform statistical inference to validate findings.
- Apply linear machine learning models to predict which customers would be interested to buy travel insurance.
- Summarize results and provide actionable recommendations based on the analysis.

## Exploratory Data Analysis

In this section, the dataset is explored by performing the following:

- Uploading and providing an overview of the dataset
- Generating charts and summaries to visualize key insights
- Analyzing statistics to identify correlations between features and the target variable

## Feature Engineering 

Before training machine learning models, the dataset is prepared by:

- Generating new features to uncover valuable patterns
- Reducing missing data by establishing rules based on passenger relationships and filling values logically
  
## Statistical Inference

This section focuses on statistical inference to evaluate:

- The significance of the correlation between categorical independent variables.
- The significance of the correlation between categorical independent variables and the dependent variable.
- The significance of the correlation between between continuous independent variables and the dependent variable.
  
## Statistical Modeling

In this section, statistical modeling is performed by:

- Utilizing a dummy classifier as a benchmark
- Training and evaluating multiple classifiers
- Conducting hyperparameter tuning using Grid Search
- Analyzing feature importance to identify the most influential variables in predictions

## Conclusions

- **Dataset Overview**: Analyzed nearly 2,000 customers, with 36% purchasing travel insurance, revealing slight dataset imbalance and key features like age, income, and employment type.

- **Influencing Factors**: Significant correlations were found between travel insurance purchases and factors such as employment type, frequent flyer status, and annual income.

- **Statistical Inference**: Significant relationships emerged between categorical variables (e.g., EverTravelledAbroad, FrequentFlyer) and travel insurance purchases, alongside correlations with continuous variables like AnnualIncome.

- **Model Performance**: The benchmark classifier achieved 54% accuracy but had low recall (34%). Random Forest outperformed other complex models after hyperparameter tuning.

- **Feature Importance**: Income-related features were consistently important across classifiers, informing feature selection for better model performance.
  
## License

This project is licensed under the [MIT License](LICENSE).

