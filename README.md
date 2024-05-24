# SalarySmart: Predict Your Earnings!

## Overview

SalarySmart is a machine learning web application developed using Python and Streamlit. It leverages real-world survey data to predict yearly salaries based on factors such as country, education level, and years of professional coding experience. The project consists of two main parts: data analysis and model building, followed by creating a user-friendly web application to make predictions accessible to users.

## Features

- **Data Analysis and Cleaning**: Processing and preparing real-world data for modeling.
- **Machine Learning Model**: Building, training, and optimizing various regression models to predict salaries.
- **Web Application**: Using Streamlit to create an interactive web interface for salary predictions.
- **User Input Handling**: Allow users to input their details and receive predicted salary information.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/SalarySmart.git
    cd SalarySmart
    ```

2. Create and activate a virtual environment:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

4. Run the Streamlit application:
    ```bash
    streamlit run app.py
    ```

## Usage

1. Open your web browser and navigate to `http://localhost:8501`.
2. Enter your country, education level, and years of professional coding experience.
3. Click on the "Predict Salary" button to view the predicted yearly salary.

## Dataset
The data used in this project comes from the Stack Overflow Developer Survey 2020. This survey provides comprehensive insights into the global developer community, covering various aspects such as employment, education, coding experience, and compensation.

## Data Preparation

The data used in this project comes from the Stack Overflow Developer Survey. The steps involved in data preparation include:

- Selecting relevant columns (Country, Education Level, Years of Professional Coding, Employment Status, and Salary).
- Cleaning and preprocessing the data (handling missing values, encoding categorical variables, etc.).
- Filtering the data to include only full-time employed individuals with valid salary information.

## Model Building

Multiple regression models were built and evaluated, including:

- Linear Regression
- Decision Tree Regression
- Random Forest Regression

The models were trained and optimized to minimize the error in salary predictions. The best-performing model was selected for deployment in the web application.

## Web Application

The web application was built using Streamlit, providing an interactive and user-friendly interface for making salary predictions. The model and necessary preprocessing steps were saved using Pickle, allowing the application to load and use the trained model efficiently.

## Future Improvements

- Integrating additional features such as job title, industry, and company size to improve prediction accuracy.
- Enhancing the user interface with more visualizations and interactive elements.
- Deploying the application on a cloud platform for broader accessibility.
