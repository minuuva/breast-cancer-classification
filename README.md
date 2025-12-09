# Breast Cancer Classification
In this project, we aim to predict the presence of malignant or benign breast cancer given information about tumorous cell nuclei characteristics. This is a relevant and important issue because breast cancer accounts for one-fourth of all cancer cases and is the most common cancer among women. 

Dataset: https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data 

Using this dataset, we randomly split the data into a train(80%)/test(20%) sets. We then applied four different machine learning models - logistic regression, support vector machines, XGBoost, and a neural network - and compared their performance. The best performing model was used to be evaluated on the test set to report final results. 

## Software and Tools

Python: Python 3.8+

Notebook Environment: Jupyter Notebook 

Operating Systems: compatible with Windows, macOS, and Linux

Required Python Packages
- pandas
- numpy 
- matplotlib
- seaborn
- scikit-learn 
- xgboost 
- PyTorch

## Repository Structure 
```bash
└───Data
|    └───breast_cancer_testset.csv
|    └───breast_cancer_trainset.csv
| 
└───Notebooks
|    └───EDA.ipynb
|    └───logistic_regression.ipynb
|    └───svm.ipynb
|    └───xgboost.ipynb
|    └───neural_network.ipynb
|    └───test_evaluation.ipynb
|
└───Output
|    └───nn_test_results.png
|
└───requirements.txt
|
└───final_report.pdf
