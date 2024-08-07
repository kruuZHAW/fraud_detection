# fraud_detection
Bank account fraud detection project. It will be presented at a technical interview for a Data Scientist position at the FIA. 

The dataset can be found on [Kaggle](https://www.kaggle.com/datasets/sgpjesus/bank-account-fraud-dataset-neurips-2022/data?select=Base.csv). Please add it by yourself in the data folder. 

Requirements:
- Develop 2 ML models to compare their performances.
- Use Jupyter Notebook for the presentation.
- Prepare a 10mins demo.
- 5h assignement.
- Take into account explainability of the model.
- Develop further ideas as conclusion. 


## Prerequisites
**Python Environment Setup**
The python environement for this project is managd through [Poetry](https://python-poetry.org/). Poetry can be installed with the following command:
```sh
pip install poetry
poetry --version
```

Install the Poetry env with:
```sh
poetry install
```
The poetry virtual environment should be selectable as a kernel in a Jupyter Notebook. 

## Description
The project took about 5 hours to complete. Due to this time limit we had to prioritise certain tasks and make decisions about the development. We focused mainly on the initial exploration of the data, the comparison of two different models and their analysis in the context of explanatory power. We did not concentrate on optimising the visualisations or the hyperparameters of the models. The project is composed of two jupyter notebooks: 

- data_exploration: This notebook brings together the exploration of the dataset studied and any data cleansing. We focused mainly on understanding the features and their distribution conditional on the Fraud variable.
- training: In this notebook, we have implemented two different models for fraud prediction: logistic regression and LightGBM. We have compared their performance in terms of the area under the ROC curve: In addition, we have compared the importance of each feature in decision making. 


