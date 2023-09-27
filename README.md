# Credit_card_Fraud_Detection

dataset link -- https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud
## Dataset Description

The dataset utilized in this project comprises credit card transactions conducted by European cardholders during September 2013. This dataset spans a two-day period and encompasses a total of 284,807 transactions. Within this dataset, there are 492 instances of fraudulent transactions. It is imperative to note that this dataset exhibits a substantial class imbalance, with fraudulent transactions accounting for only 0.172% of the total transactions.


## Requirements

To execute this project successfully, you will need to have the following dependencies installed, as outlined in the `requirements.txt` file:

- pandas
- numpy
- python
- joblib
- sklearn (Scikit-learn)

## Preprocessing

### Data Preprocessing

In the data preprocessing phase, several important steps were undertaken:

1. **Data Cleaning:** Missing values were handled appropriately, and data cleaning procedures were applied to ensure data quality.

2. **Feature Engineering:** New relevant features were created, and existing ones were transformed to enhance model performance.

3. **Scaling/Normalization:** Feature scaling was performed to bring the features to a similar scale.

### Exploratory Data Analysis (EDA)

Exploratory Data Analysis provided valuable insights into the dataset:

1. **Data Distribution:** Visualizations of transaction amounts and times helped understand the data's distribution.

2. ## Addressing Class Imbalance![download](https://github.com/Rajveerdata/Credit_card_Fraud_Detection/assets/127951177/934757da-f7dd-4b0e-a3d3-c509c09c340b)





Given the severe class imbalance (99% normal transactions and 1% fraud transactions) within the dataset, oversampling and undersampling techniques were applied to mitigate this issue.

1. **Oversampling:** Oversampling techniques were employed, such as SMOTE or ADASYN, and their impact on the model was discussed.

2. **Undersampling:** Undersampling techniques were used to balance the dataset, and their effectiveness was explained.

## Results

### Undersampling

Three distinct machine learning models were evaluated using the dataset:

1. Logistic Regression (LR) achieved an accuracy of 94.21%.

2. Decision Tree (DT) attained an accuracy of 88.95%.

3. Random Forest (RF) demonstrated an accuracy of 93.16%.

### Oversampling

Oversampling was employed, and the following results were obtained:

1. Logistic Regression (LR) achieved an accuracy of 94.52%.

2. Decision Tree (DT) attained an exceptionally high accuracy of 99.81%.

3. Random Forest (RF) exhibited a near-perfect accuracy of 99.99%.

### Boxplots

The repository mentions the intention to provide boxplots for both oversampling and undersampling results. However, these boxplots are not included in the current version of the repository. To enhance the clarity of the analysis, consider adding the boxplots to visually represent the results.
### oversampling


![download](https://github.com/Rajveerdata/Credit_card_Fraud_Detection/assets/127951177/e60cc1a8-9a89-437f-a9b0-702d83b58f49)



### undersampling



![download](https://github.com/Rajveerdata/Credit_card_Fraud_Detection/assets/127951177/8e8df0ca-4b8a-4052-9769-8a1c83421388)
### Model Saving

To ensure the model's reproducibility and usability, clear instructions are provided for saving the trained**Random Forest classification model**:



---


