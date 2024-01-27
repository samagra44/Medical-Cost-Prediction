# Medical Cost Prediction Web App

## Overview
The Medical Cost Prediction Web App is an innovative project designed to predict medical costs using machine learning techniques. The goal is to assist individuals and healthcare providers in estimating medical expenses based on various factors. The predictive model, employing the Random Forest Regressor algorithm, showcases remarkable accuracy, achieving a commendable 97.63%.

## Project Details

### Dataset
The dataset used for this project comprises 1338 records and 7 columns, encompassing critical features such as age, sex, BMI, number of children, smoker status, region, and the target variable – medical charges. Extensive data analysis was conducted to comprehend the dataset's characteristics thoroughly.

### Exploratory Data Analysis (EDA)
Prior to model training, exploratory data analysis techniques were applied to gain insights into the distribution and relationships between different variables. Visualizations and statistical analyses were employed to uncover patterns and trends within the data.

### Data Preprocessing
A meticulous data preprocessing pipeline was implemented to enhance the model's robustness. Techniques such as label encoding were applied to convert categorical variables into a numerical format. Special attention was given to handling missing values and outliers, ensuring data integrity.

### Machine Learning Model
The heart of the project lies in the machine learning model powered by the Random Forest Regressor algorithm. This algorithm was chosen for its ability to capture complex relationships within the dataset. The model's impressive accuracy of 97.63% attests to its effectiveness in predicting medical costs.

## Web App Details

### Framework and Interface
The web app is developed using the Django framework, providing a robust and user-friendly interface. Users can seamlessly input relevant information, including age, sex, BMI, number of children, smoker status, and region. The interface facilitates easy interaction with the machine learning model.

### Usage
Users simply input their relevant details into the web app, and the model, running seamlessly in the background, provides accurate predictions of medical costs. The user-friendly design enhances accessibility, making the tool valuable for both individuals and healthcare professionals.

## How to Run the Web App

1. **Dependencies Installation**: Install the required dependencies listed in the `requirements.txt` file.
2. **Django Server**: Run the Django development server using the command: `python manage.py runserver`.
3. **Accessing the Web App**: Open your browser and navigate to `http://localhost:8000` to interact with the web app.

Issues and pull requests are welcomed for any encountered problems or potential improvements. The Medical Cost Prediction Web App stands as a powerful tool, offering predictive insights to navigate the complex landscape of healthcare costs.

# Output
![Screenshot 2024-01-27 223951](https://github.com/samagra44/Medical-Cost-Prediction/assets/77968722/f34d0d33-b097-4b20-af33-c3e21839f555)
