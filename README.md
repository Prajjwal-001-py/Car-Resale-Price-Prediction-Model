# Car-Resale-Price-Prediction-Model

A Multi regression model to predict the car's resale value using some features of the car as input  made using closed form solution.

Tools used:

Google colab as notebook.  
Numpy library for mathematical calculations and array transformations.  
Pandas to access the data.  
Matplotlib and seaborn to visualise the features and their interdependencies.  
Gemini to generate the dataset.

Steps:

Importing libraries  
Reading the dataset  
Visualisation of the features of the dataset  
Formation of 2D numpy arrays for better calculation  
Scaling of the input data using z-score normalisation  
Adding bias columns in the input scaled array to get the intercept  
Applying closed form solution to get the parametric array  
Formation of function for Prediction of Resale Price  
Testing of the Model

Problems:

Understanding the process to do calculations in matrix(array) form of inputs, outputs, and parameters was the tricky part.  
There were some points where eventually bugs appeared like totally different graph results at the time of visualisation,etc.
Also even the Horsepower the car was zero, the model was showing a very good price of the car as it was mathematically obivous. Fixed by adding an additional if else statement in the predictor function.
