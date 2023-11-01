# AI-driven-and-exploration
AI-Driven Exploration and Prediction of Company Registration Trends with Registrar of Companies (RoC)
Company Registration Trends Prediction with Random Forest Regression

This repository contains code for exploring and predicting company registration trends with the Registrar of Companies using a Random Forest regression model.

 Table of Contents
- [Prerequisites](#prerequisites)
- [Getting Started](#getting-started)
  - [Installation](#installation)
- [Usage](#usage)
- [Data](#data)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Machine Learning Model](#machine-learning-model)
- [Model Evaluation](#model-evaluation)
- [Prediction for Future Years](#prediction-for-future-years)
- [Contributing](#contributing)
- [License](#license)

 Prerequisites

Before running the code, ensure you have the following prerequisites:

                            - Python 3.x
                            - Required libraries: pandas, numpy, scikit-learn, and matplotlib. You can install them using the provided `requirements.txt` file.

Getting Started

Installation

1.	Clone this repository to your local machine.
2.	
   git clone https://github.com/Kaniiii19/AI-driven-and-exploration.git
   cd company-registration-trends
   

2. Create a virtual environment (optional but recommended).
   python -m venv venv
   source venv/bin/activate # On Windows: venv\Scripts\activate
   

3. Install the required libraries using pip.
   pip install -r requirements.txt
  
 Usage

Follow these steps to run the code:

1. Place your company registration data CSV file in the project directory, or update the file path in the code accordingly.

2. Open a terminal and navigate to the project directory.

3. Run the code.

The code will load the data, perform data preprocessing and feature engineering, conduct exploratory data analysis, train a Random Forest regression model, evaluate its performance, and predict company registrations for future years.

 Data

The code expects a CSV file containing company registration data. Make sure the CSV file includes columns like 'DATE_OF_REGISTRATION,' 'year,' 'INDUSTRIAL_CLASS,' and any other relevant features.

Exploratory Data Analysis

The code conducts exploratory data analysis to visualize company registration trends by year.

 Machine Learning Model

A Random Forest regression model is used to predict company registration trends based on the 'year' feature.

Model Evaluation

The code calculates the Mean Squared Error (MSE) as the evaluation metric for the model's performance.

 Prediction for Future Years

The model predicts the number of registrations for future years (2023, 2024, 2025) and displays the results.

 Contributing

Feel free to contribute to this project by opening issues or pull requests. Your contributions are welcome and appreciated.

 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

