# Real Estate Price Prediction Web Application

This repository contains the source code and documentation for a real estate price prediction web application. The project is an end-to-end implementation, leveraging data science and machine learning techniques, and deployed using NGINX.

## Project Overview

This web application predicts real estate prices based on user input such as square footage, number of bedrooms, and location. The application consists of three main components
1. Machine Learning Model Developed using Python and Scikit-learn.
2. Backend Server Built with Python Flask to serve HTTP requests.
3. Frontend A responsive user interface designed using HTML, CSS, and JavaScript.

## Features
- Data cleaning and preprocessing, including outlier detection and feature optimization.
- Machine learning model built using Linear Regression, Lasso, and Decision Trees.
- Hyperparameter tuning with GridSearchCV and accuracy evaluation with K-Fold Cross Validation.
- Exported trained model as a pickle file for integration.
- RESTful API endpoints for predictions and location data retrieval.
- Deployed on an NGINX server for handling HTTP requests.

## Technologies and Tools
- Programming Languages Python, HTML, CSS, JavaScript
- Libraries Numpy, Pandas, Matplotlib, Scikit-learn
- Frameworks Flask
- Server NGINX
- Development Tools Jupyter Notebook, Visual Studio Code, PyCharm

## Project Workflow
1. Data Preprocessing
   - Loaded and cleaned the dataset using Numpy and Pandas.
   - Removed outliers using business logic and applied feature engineering techniques.
   - Performed dimensionality reduction and encoded categorical variables using One-Hot Encoding.
2. Model Building
   - Split the data into training and testing sets.
   - Trained models using Linear Regression, Lasso, and Decision Trees.
   - Optimized models using GridSearchCV and validated using K-Fold Cross Validation.
   - Exported the final model and relevant metadata for deployment.
3. Backend Development
   - Created a Flask application to handle HTTP requests.
   - Developed API endpoints for predictions (POST) and location data retrieval (GET).
   - Tested APIs using Postman.
4. Frontend Development
   - Designed a user-friendly interface for inputting property details and viewing predictions.
   - Integrated the frontend with the Flask backend.
5. Deployment
   - Configured and deployed the application using NGINX.
   - Hosted the application at `localhost` for production.

## Setup Instructions
1. Clone the repository
   ```bash
   git clone httpsgithub.comyourusernamereal-estate-price-prediction.git
   cd real-estate-price-prediction
   ```
2. Install dependencies
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Flask server locally
   ```bash
   python app.py
   ```
   Access the local server at `http127.0.0.15000`.
4. Configure and start NGINX for deployment
   - Update the NGINX configuration file to serve the application.
   - Restart the NGINX server and access the application at `httplocalhost`.


## Acknowledgements
- Dataset sourced from [Kaggle]().

