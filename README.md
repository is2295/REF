# Final-Project-Report-
Netflix Stock Price Prediction: Comparative Analysis of CNN, Random Forest, and LSTM Models
Overview
This repository contains the final project report and code implementation for the study on predicting Netflix stock prices using machine learning techniques. The project compares the effectiveness of three different models: Convolutional Neural Networks (CNN), Random Forest Regression, and LSTM, with the aim of determining which model provides the most accurate forecasts based on the complex characteristics of financial time series.

Project Structure
data/: This folder contains the historical Netflix stock price data used for training and testing the models.
notebooks/: Jupyter notebooks detailing the exploratory data analysis (EDA), model development, training, and evaluation processes.
models/: Contains the saved models for CNN, Random Forest, and LSTM, which can be loaded for further predictions.
results/: This folder includes the performance metrics and comparison results of the different models.
scripts/: Python scripts for data preprocessing, model training, and evaluation.
README.md: The current file, providing an overview of the project, its goals, and instructions for reproducing the analysis.
Motivation
Accurate stock price prediction is crucial for investors, portfolio managers, and financial analysts, as it can help in making informed decisions, reducing risks, and maximizing returns. Traditional models like LSTM often struggle with the complexities of financial data, making it important to explore more advanced machine learning techniques. This project investigates whether models like CNN and Random Forest can outperform traditional methods in forecasting the highly volatile stock prices of Netflix.

Objectives
Predict Netflix stock prices using historical data and machine learning techniques.
Compare the performance of traditional models (e.g., LSTM) with deep learning models (e.g., CNN, LSTM) in terms of prediction accuracy.
Provide insights that can help financial practitioners in making better investment decisions.
Methodology
The project involves the following steps:

Data Collection: Historical stock price data for Netflix is gathered from reliable financial data sources.
Data Preprocessing: The data is cleaned, normalized, and split into training and testing sets.
Model Development:
LSTM: A traditional time series forecasting model.
Random Forest Regression: An ensemble learning method that operates by constructing multiple decision trees.
CNN: A deep learning model that is typically used for image data but is applied here for time series forecasting.
Model Evaluation: The models are evaluated based on performance metrics like Mean Squared Error (MSE), Mean Absolute Error (MAE), and R-squared (R²) to compare their accuracy.
Comparison and Analysis: The results are analyzed to determine which model performs best for predicting Netflix stock prices.
Key Findings
The findings of this study contribute to the growing body of knowledge on financial forecasting by:

Demonstrating the strengths and weaknesses of CNN, Random Forest, and LSTM models in the context of stock price prediction.
Providing practical insights into the application of these models for financial practitioners, which can improve decision-making processes related to stock trading and investment strategies.
Getting Started
Prerequisites
To run the code in this repository, you'll need:

Python 3.x
Jupyter Notebook
The following Python libraries:
pandas
numpy
scikit-learn
keras/tensorflow (for CNN)
statsmodels (for LSTM)
matplotlib/seaborn (for data visualization)
Installation
Clone this repository:

bash
Copy code
git clone https://github.com/is2295/REF.git
cd REF
Install the required libraries:

bash
Copy code
pip install -r requirements.txt
Usage
Navigate to the notebooks/ directory and open the Jupyter notebooks to explore the EDA and model development steps.
Run the scripts in the scripts/ directory to preprocess the data, train the models, and evaluate their performance.
Check the results/ folder for the comparison results and performance metrics.
Conclusion
This project provides a comprehensive analysis of different machine learning models for predicting Netflix stock prices. The results indicate the potential of deep learning techniques like CNNs to outperform traditional models like LSTM, especially in handling the complexities of financial time series data.

Author
Ismail Sarigat

Email: ismailsarigat90@gmail.com
GitHub: is2295
License
This project is licensed under the MIT License. See the LICENSE file for details.
