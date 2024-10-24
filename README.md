# Employee-Turnover-Prediction

It's a Binary Classification problem: Turnover V.S. Non Turnover

Objective:
> - To understand what factors contributed most to employee turnover.
> - To perform clustering to find any meaningful patterns of employee traits.
> - To create a model that predicts the likelihood if a certain employee will leave the company or not.
> - To create or improve different retention strategies on targeted employees.

The implementation of this model will allow management to create better decision-making actions.

We'll be covering:
> - Descriptive Analytics - What happened?
> - Predictive Analytics - What might happen?
> - Prescriptive Analytics - What should we do?

The dataset is taken from Kaggle: https://www.kaggle.com/code/jacksonchou/hr-analytics/input.

The goal of the machine learning model is to capture as much of the minority class as possible (turnover group). Our objective is to catch ALL of the highly probable turnover employee at the risk of flagging some low-risk non-turnover employee.

I have used 4 dataset to compare their performance and find out which one works the best:
> 1. Original data
> 2. Upsampled data
> 3. SMOTE data
> 4. Downsampled data
Out of which, SMOTE outperforms all other dataset so I have used SMOTE for the training of the Machine Learning model.

For this project, I have used 3 Machine Learning models:
> 1. Logistic Regression
> 2. Random Forest Classifier
> 3. Gradient Boosting Classifier.
Out of all 3 ML models, Random Forest Classifier performs the best with 0.99 F1-score. 
