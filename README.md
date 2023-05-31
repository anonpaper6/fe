# Benchmarks for Custom Feature Engineering (FE) Paper

This repository provides the benchmarks utilized in the submitted paper on custom feature engineering (FE). The contents of the repository are as follows:

* The `Benchmarks` folder contains 31 benchmarks in `*.csv` format, which were used in the study. Additionally, two large datasets can be downloaded from the following links:
  * PUBG Finish Placement: https://www.kaggle.com/competitions/pubg-finish-placement-prediction/data?select=train_V2.csv
  * IEEE-CIS Fraud Detection: https://www.kaggle.com/competitions/ieee-fraud-detection/data?select=train_transaction.csv
* The `Column_desc` folder includes column descriptions for a few benchmarks. These descriptions are optional for datasets with semantically meaningful column names.
* The `ML_task_definition.json` file defines the task specifications for each machine learning (ML) task. It includes details such as the target dataset, target columns, task type (classification or regression), and columns to be ignored (e.g., ID columns) for each ML task.
