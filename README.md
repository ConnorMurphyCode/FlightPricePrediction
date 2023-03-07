# FlightPricePrediction
Flight Price Prediction
This repository contains code for predicting flight prices using Multiple Linear Regression, Machine Learning, and statistics practice. The model was trained on over one hundred thousand data points and achieved a 92% accuracy on real-world data.

## Features

The model includes a wide range of options, such as:

•Choice of six different airlines

•Choice of six different source and destination cities

•Separate departure and arrival times

•Number of stops

•Seat type

•Duration of the flight

•Days until the flight

•How to Use

To use the code, open the "Flight Price Prediction.ipynb" notebook. The notebook provides an overview of the code, but its interactive features are not active. To access the live dashboard/Jupyter Notebook, use the following link:

https://colab.research.google.com/drive/1a-gR2KlnoSaflgzr8n9AbgavRDUK7nnp?usp=sharing


## Results

The model's accuracy can be evaluated by comparing predictions against the other 1/4th of the data after training the model on 3/4ths of the data. Additionally, several graphical comparisons between the different variables in the dataset are included.


#### Seat Distribution in the Data Set
This first graph displays the distribution of Economy and Business Class in the dataset. The second shows the price distribution of flights in Economy and Business Class in the dataset.
![Distribution of Economy vs Business Class](https://i.imgur.com/5jms2h2.png "Distribution of Economy vs Business Class")


#### Airline Occurences and their Price Distribution
These graphs display the number of occurences that each airline has in the dataset as well as the price distribution. Notibly, you'll notice that no specific airline dominates at any specific price point.
![Distribution airlines and costs](https://i.imgur.com/tANJc4G.png "Distribution of Airlines and costs")


#### Price vs Days Until Flight (all Airlines)
These graphs shows the relationship between the price of flights and the number of days remaining until the flight, across all airlines in the dataset used for the Flight Price Prediction model.
![Price vs Days Until Flight](https://i.imgur.com/1tQJrfs.png "Price vs Days Until Flights")


#### Example of Model Prediction with All Options Selected
This image shows an example of the Flight Price Prediction model in action, with all available options selected. The model has generated a predicted price based on these inputs, using Multiple Linear Regression and machine learning techniques. This example illustrates the model's flexibility and accuracy in predicting flight prices across a wide range of variables.

![Example of user predicting a price](https://i.imgur.com/u7yc8oj.png "Example of user predicting a price")
