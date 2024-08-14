**House Price Prediction Web Application**

#Author: Aditya Nema

#Date: 14-08-2024

This project is a machine learning-based web application built with Flask that predicts house prices based on various input features like the number of bedrooms, bathrooms, floors, and the year of construction. The prediction model is pre-trained using a dataset and implemented with a linear regression algorithm.

Project Structure

index.html: This is the frontend of the application where users can input details such as the number of bedrooms, bathrooms, floors, and the year of build to predict the price of the house.

app.py: The main Flask application file. It handles the routing of the web application, takes user input from the form, processes it, and displays the predicted house price.

house.py: This script is responsible for training the machine learning model. It loads the dataset, performs data preprocessing, trains a linear regression model, and saves the trained model as a pickle file (model.pkl).

model.pkl: The serialized machine learning model used for making predictions in the web application.


How It Works
User Input: The user inputs the number of bedrooms, bathrooms, floors, and the year the house was built into the web form on the frontend (index.html).
Prediction: Upon submission, the inputs are sent to the Flask server (app.py), where they are processed and passed to the pre-trained machine learning model (model.pkl).
Output: The model predicts the house price, and the result is displayed back on the webpage.

Model Training
The model was trained using a dataset containing various features related to house pricing.
A linear regression model was used due to its simplicity and effectiveness in predicting continuous values like house prices.
The model was trained on 75% of the data, while the remaining 25% was used for testing to evaluate the model's performance.

Contact
For any queries, please feel free to contact Aditya Nema at adinema27@gmail.com.



