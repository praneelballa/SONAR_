**SONAR DATA CLASSIFICATION USING LOGISTIC REGRESSION**
>  This notebook demonstrates a machine learning project to classify sonar data as either a rock ('R') or a mine ('M') using Logistic Regression.

**Project Overview**
>  The goal of this project is to build a predictive model that can distinguish between rocks and mines based on sonar readings. The dataset consists of 60 numerical features representing different sonar signal patterns and a target variable indicating whether the object is a rock or a mine.

**Dataset**
>  The dataset used in this notebook is a sonar dataset where each row represents a set of sonar readings, and the last column ('60') indicates the object type (M for Mine, R for Rock).

**Data Dimensions**
> Number of samples: 208
> Number of features: 60
> Class Distribution
> Mines (M): 111 samples
> Rocks (R): 97 samples

**Model**
A Logistic Regression model from the sklearn.linear_model library is used for classification. The model is trained on 80% of the data and evaluated on the remaining 20%.

**Results**
After training, the model achieved the following accuracy scores:

> Training Data Accuracy: 83.42%
> Test Data Accuracy: 76.19%

_How to Use This Notebook_

* Clone the repository: If this notebook is part of a Git repository, clone it to your local machine.
* Open in Google Colab: Upload and open the .ipynb file in Google Colab.
* Run cells sequentially: Execute each code cell in order, starting from the top.
* Data: Ensure the sonar data.csv file is accessible in the Colab environment (e.g., uploaded to /content/ or mounted from Google Drive).
* Predictive System: The notebook includes a simple predictive system to test new input data points.
