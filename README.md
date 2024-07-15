# Credit Card Application Prediction
This project aims to predict the approval of credit card applications using a dataset with various features about the applicants. The model employs machine learning techniques to determine the likelihood of a credit card application being approved.

## Requirements
Python 3.9
pandas
numpy
scikit-learn
matplotlib
tensorflow

## Setup

```git clone https://github.com/yourusername/credit-card-application-prediction.git```
```cd credit-card-application-prediction```

```conda create --name cc-prediction python=3.9```
```conda activate cc-prediction```

```pip install pandas numpy scikit-learn matplotlib tensorflow```

```jupyter notebook```

## Dataset
The dataset contains information about applicants, including the number of derogatory reports, collection accounts, inquiries, trade lines, and more. Key columns include:
TARGET: 1 if application for credit card accepted, 0 if not
ID: Applicant's unique identifier
DerogCnt: Number of major derogatory reports
CollectCnt: Number of collection accounts
BanruptcyInd: Indicator of bankruptcy
InqCnt06: Number of inquiries in the last 6 months
InqTimeLast: Time since the last inquiry
InqFinanceCnt24: Number of finance inquiries in the last 24 months
TLTimeFirst: Time since the first trade line
TLTimeLast: Time since the last trade line
TLCnt03: Number of trade lines opened in the last 3 months
TLCnt12: Number of trade lines opened in the last 12 months
TLCnt24: Number of trade lines opened in the last 24 months
TLCnt: Total number of trade lines
TLSum: Total sum of the trade lines
TLMaxSum: Maximum sum of the trade lines
TLSatCnt: Number of satisfactory trade lines
TLDel60Cnt: Number of 60 days delinquent trade lines
TLBadCnt24: Number of bad trade lines in the last 24 months
TL75UtilCnt: Number of trade lines with utilization over 75%
TL50UtilCnt: Number of trade lines with utilization over 50%
TLBalHCPct: Percentage of high credit balance on trade lines
TLSatPct: Percentage of satisfactory trade lines
TLDel3060Cnt24: Number of trade lines 30-60 days delinquent in the last 24 months
TLDel90Cnt24: Number of trade lines 90 days delinquent in the last 24 months
TLDel60CntAll: Number of 60 days delinquent trade lines in all time
TLOpenPct: Percentage of open trade lines
TLBadDerogCnt: Number of bad or derogatory trade lines
TLDel60Cnt24: Number of 60 days delinquent trade lines in the last 24 months
TLOpen24Pct: Percentage of open trade lines in the last 24 months

## Data Preprocessing
Load the dataset
Handle missing values
Convert percentage strings to floats

## Model Training
Split the dataset into training and testing sets
Normalize the data
Train a Logistic Regression model
Evaluate the model

## Advanced Model: Convolutional Neural Network (CNN)
Build the CNN
Train the CNN
Evaluate the CNN

## Conclusion
This project demonstrates how to preprocess data, train machine learning models, and use deep learning techniques to improve model performance. Further improvements can be made by experimenting with different architectures, hyperparameters, and additional data preprocessing techniques.
