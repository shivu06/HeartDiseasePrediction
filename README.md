# **Heart Disease Prediction using Machine Learning Approach**

Heart Disease (including Coronary Heart Disease, Hypertension, and Stroke) remains the No. 1 cause of death in the US.The Heart Disease and Stroke Statistics—2019 Update from the American Heart Association indicates that:

*   116.4 million, or 46% of US adults are estimated to have hypertension. These are findings related to the new 2019 Hypertension Clinical Practice Guidelines.
*   On average, someone dies of CVD every 38 seconds. About 2,303 deaths from CVD each day, based on 2020 data.
*   On average, someone dies of a stroke every 3.70 minutes. About 389.4 deaths from stroke each day, based on 2021 & 2022 data.

In this machine learning project, we have collected the dataset from UCI (https://archive.ics.uci.edu/ml/datasets/statlog+(heart)) and we will be using Machine Learning to make predictions on whether a person is suffering from Heart Disease or not.

**Problem Statement**

*   Complete analysis of Heart Disease UCI dataset.
*   To predict whether a person has a heart disease or not based on the various biological and physical parameters.

**Machine Learning Algorithms**

*   Random Forest Classifier
*   K-Nearest Neighbors Classifier
*   Decision Tree Classifier
*   Naive Bayes Classifier

**File Descriptions:**
* `dataset.csv` : the dataset file.
* `Heart_Disease_Prediction.ipynb` : contains the code of data exploration, preparation and modeling.
* `models.pkl` : the classification model.
* `heart_disease_app.py` : Flask API that bind between the classification model and the web page.
* **templates:**  `Heart_Disease_Classifier.html` : a web page that contains a form for heart disease testing.
