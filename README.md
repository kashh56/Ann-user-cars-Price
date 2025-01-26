Used Car Price Prediction
=========================

**Used Car Price Prediction** is a machine learning project where we used an Artificial Neural Network (ANN) to predict the price of used cars based on various features such as make, model, year of manufacture, mileage, and others. The project involves hyperparameter tuning using **Keras Tuner** to optimize the model and achieve better prediction accuracy. While the model is trained and optimized, it is not yet deployed.

Table of Contents
-----------------

*   [About](#about)
*   [Dataset](#dataset)
*   [Model](#model)
*   [Hyperparameter Tuning](#hyperparameter-tuning)
*   [Contributing](#contributing)
*   [License](#license)

About
-----

The goal of this project is to predict the price of used cars based on their attributes. The model uses various features such as:

*   Make
*   Model
*   Year of Manufacture
*   Mileage
*   Engine Size
*   Fuel Type
*   Transmission Type


These features are used to predict a continuous target variable, which is the price of the car. We used an Artificial Neural Network (ANN) for the regression task, trained on a dataset of used car listings.

Dataset
-------

The dataset used for this project contains information on used cars, such as the car’s make, model, year, mileage, fuel type, transmission type, . The target variable is the car price (continuous).

Some of the features include:

*   **Make**: The manufacturer of the car (e.g., Toyota, Ford, etc.)
*   **Model**: Specific model of the car (e.g., Camry, Mustang, etc.)
*   **Year**: Year the car was manufactured
*   **Mileage**: Distance the car has traveled in kilometers
*   **Engine Size**: Size of the engine in liters
*   **Fuel Type**: Type of fuel the car uses (e.g., Petrol, Diesel, Electric)
*   **Transmission**: Type of transmission (e.g., Automatic, Manual)

The target variable is the **Price**, which is a continuous value.

Model
-----

For this project, we used an **Artificial Neural Network (ANN)** to predict car prices. The model consists of the following components:

*   An **input layer** to accept various features of the car
*   One or more **hidden layers** with ReLU (Rectified Linear Unit) activation functions
*   An **output layer** with a single neuron that predicts the price (regression task)

The ANN model was built using **Keras** with TensorFlow backend. It uses Mean Squared Error (MSE) as the loss function and Adam as the optimizer.

Hyperparameter Tuning
---------------------

Hyperparameter tuning was performed using **Keras Tuner**, a library for automated hyperparameter optimization. The tuning process involved searching for the optimal combination of hyperparameters, such as:

*   Number of hidden layers
*   Number of neurons in each hidden layer


Contributing
------------

If you would like to contribute to this project, feel free to fork the repository, make changes, and submit a pull request. Please follow these guidelines:

*   Follow the existing coding style
*   Write unit tests for new features or changes
*   Update the documentation accordingly

License
-------

This project is licensed under the MIT License -
