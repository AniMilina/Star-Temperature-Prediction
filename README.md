# Star-Temperature-Prediction  

We received a task from the Sky in the Palm observatory: to figure out how to use a neural network to determine the temperature on the surface of discovered stars

Typically, scientists use the following methods to calculate temperature:

Wien's displacement law
Stefan-Boltzmann law
Spectral analysis
Each of them has pros and cons. The observatory wants to implement machine learning technologies to predict the temperature of stars, hoping that this method will be the most accurate and convenient

The observatory database contains characteristics of 240 stars already studied

Characteristics:

Relative luminosity L/Lo - the luminosity of a star relative to the Sun
Relative radius R/Ro - the radius of the star relative to the radius of the Sun
Absolute magnitude Mv is a physical quantity characterizing the brightness of a star.
Star color (white, red, blue, yellow, yellow-orange, etc.) - the color of a star, which is determined based on spectral analysis
Star type
Our task is to develop a neural network model that will help predict the absolute temperature on the surface of a star, the RMSE metric of which should not exceed 4500

Work plan:
Functions
Constants
Loading Data
3.1 Data preprocessing and analysis
3.2 Visualization of features and statistics
Building a Basic Neural Network
4.1 Dividing data into training and testing
4.2 Test on Catboost
4.3 Hyperparameter selection using Optuna
Neural network training
5.1 Dividing data into features (X) and target variable (Y)
5.2 Data preprocessing
5.3 Definition of neural network architecture
5.4 Initializing the model and optimizer
5.5 Visualization of results
conclusions
