# BlueBerry Yield Prediction

## Project Overview
Objective: Fit a regression model to predict the target variable using the provided training data and then make predictions on the test data.

## Dataset
The dataset consists of two parts:

Training Dataset: Contains features and labels.
Test Dataset: Contains features only, without labels.
You will need to prepare the data carefully, ensuring that the same data preparation steps applied to the training data are also applied to the test data.

## Data Preparation
Data preparation is a crucial step before fitting your model. Here are some key steps to consider:

- Missing Data: Handle missing values appropriately.
- Encoding: Convert categorical variables into numerical values if necessary.
- Scaling: Normalize or standardize your features.
- Splitting: Optionally, split your training data into training and validation sets to fine-tune your models.
- Feature Engineering: Create or transform features that might improve your model's performance.
- Ensure that these steps are consistently applied to both the training and test datasets.

## Model Training and Evaluation
I used Linear regression model

The evaluation metric for this project is Mean Absolute Error (MAE). This metric was used during model training to fine-tune and select the best model.

