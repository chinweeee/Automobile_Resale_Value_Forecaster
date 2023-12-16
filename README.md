# Automobile_Resale_Value_Forecaster

**Introduction**

The "Automobile Resale Value Forecaster" is a machine learning project focused on predicting the resale value of automobiles using a regression model and a simple neural network. This project utilizes a simple neural network built with TensorFlow, providing insights into the resale value based on various vehicle attributes. Here I used the HorsePower of these Used Care to determine its resale value. The expected Label is a continuous value hence the reason Regression Model is used. 
The Cars where categorized as this:
- Cheap Cars: < 8.5
- Expensive Cars: >= 8.5

Note that this is a clean data. Therefore, no data cleaning was done.

**Features**

- Neural network implementation using TensorFlow for regression analysis.
- Comprehensive data preprocessing and exploration.
- Keras was used for Input Normalization
- Model training, evaluation, and prediction on automobile resale values.
- Visualization of data and prediction results for better understanding.

**Requirements**

To run this project, you will need:
- Python 3.x
- TensorFlow 2.x
- Pandas
- NumPy
- Seaborn (for data visualization)
- Scikit-Learn (for additional modeling and metrics)


**Additionally, this project can be run on Google Collab**

**Dataset**

The project uses a dataset (train.csv) containing various features of used cars. This includes attributes like years', 'km', 'rating', 'condition', 'economy', 'top speed', 'hp', 'torque', 'current price' and other relevant features that could impact the resale value.

