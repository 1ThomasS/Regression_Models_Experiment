# Engineering Students' Salary Prediction Project

## Project Overview
The goal of this study is to anticipate engineering students' pay by examining a dataset that includes a variety of characteristics, such as personality traits, levels of education, and academic achievement. The project's conclusions are meant to help companies determine appropriate compensation during hiring procedures, institutions customize their curricula, and students evaluate the return on their educational investment.

## Objective
The aim is to build a predictive model that effectively estimates the salaries of engineering graduates, helping stakeholders make informed decisions based on the projected return on educational investment.

## Hypothesis
We hypothesize that factors like academic achievement and institutional reputation significantly impact salary outcomes, which will be explored through different machine learning models.

## Dataset Description
The dataset comprises student records with details on personal attributes, academic scores, and post-graduation salaries. It is segregated into training, validation, and testing subsets for model development and evaluation.

## Models Implemented
- Multivariate Linear Regression
- Ridge Regression
- Lasso Regression
- ElasticNet Regression
- k-Nearest Neighbors (kNN) Regression

Optimal parameters for the kNN model: `{'leaf_size': 1, 'metric': 'manhattan', 'n_neighbors': 90}`.

## Methodology
Key steps in the project include:
- Data preparation, including handling missing values and normalizing features.
- Feature engineering based on the correlation with salary.
- Model training with hyperparameter tuning via GridsearchCV.
- Evaluation based on RMSE to determine model performance.

## Results
A comprehensive analysis and comparison of each model's performance were conducted to pinpoint the most accurate estimator for engineering students' salaries.

## Insights and Recommendations
Findings suggest the kNN model shows considerable promise. Future directions involve expanding the feature set and testing more advanced modeling approaches.

## Future Experiments
Suggested future initiatives entail:
- Deeper analysis with an expanded feature set.
- Experimentation with advanced kNN techniques.
- A comparative analysis to affirm the kNN model's performance.

## Usage
Follow the instructions in each Jupyter notebook to utilize the models or analyze the dataset.

## Contributions
- Ngoc Quang Vinh Pham: Project lead, data analysis, modeling, and documentation.

## Contact Information
For inquiries or interest in collaboration, please contact Ngoc Quang Vinh Pham at [quangvinh432002@email.com].

## Acknowledgments
Appreciation goes to the various educational institutions and organizations for their data contributions and support in this research initiative especially University of Technology Sydney
