# heart-disease-risk-prediction
Supervised Machine Learning algorithms are applied namely Decision Tree, Support Vector Machine, KNN

Details explanation of concepts used in this repository can be found in [medium](https://naveen-varma.medium.com/heart-disease-risk-prediction-using-supervised-machine-learning-baaece3649a)

> Python and Jupyter Notebook are used to implement this project

## Steps

1. Several Data mining techniques like feature selection, Exploratory Data Analysis, SMOTE-data balancing are performed on the dataset in [preprocessing_data file](preprocessing_data.ipynb)
2. After processing the data we train the prediction model using three different classifiers namely SVM, Decision Tree, KNN and these models are saved in models folder this training is done in the [training_models file](training_models.ipynb)
3. We test the performances of the three models in [model_selection file](model_selection.ipynb) and select the best performing model.
4. Finally the selected model is implemented in heart disease prediction in [heart_disease_prediction file](heart_disease_prediction.ipynb)

## Running the code:
- Install anaconda (it comes with jupyter)
- Install the code files and dataset in your system
- run the jupyter notebook
- open the preprocessing_data file and run it
- Then run training_model file
- then run model_selection file
- Finally, selected model can be tested in heart_disease_prediction file
