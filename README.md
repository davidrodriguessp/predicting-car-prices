## Machine Learning Modeling: Predicting Car Pricess with KNN Regression.
*Author: David Rodrigues. davidrodriguessp@hotmail.com. Aug 11, 2021.*

The objective of this project is to build a model to predict car prices based on their features. We used  the *Automobile Dataset* available at the the [UCI Machine Learning repository](https://archive.ics.uci.edu/ml/datasets/automobile). 

This dataset includes a list of cars and features as engine size, hoursepower and width. You can directly download the data clicking on this [link](https://archive.ics.uci.edu/ml/machine-learning-databases/autos/imports-85.data).

To build the model we used KNN Regression, the numeric columns of the dataset as features and the price as the target variable. The final model included four features: `horsepower`, `engine_size`, `curb_weight`, `width`and a k value of 2. The model reached a RMSE value of 2,170 and a R2 score of 90%.

You will find two files in this repository:
- Predicting Car Prices with KNN Regression.ipynb (the Jupyter Notebook with the full analysis)
- imports-85.data (datafile)

