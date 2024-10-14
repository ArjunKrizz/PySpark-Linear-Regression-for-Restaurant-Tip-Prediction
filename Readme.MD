# PySpark Linear Regression Model for Predicting Tips

This project implements a linear regression model using PySpark's `ml` library to predict the tip amount (`tip`) based on multiple features from the popular 'tips' dataset. The dataset contains information related to restaurant bills, including `total_bill`, `tip`, `sex`, `smoker`, `day`, `time`, and `size`. The project aims to predict the tip amount based on these features using PySpark's machine learning pipeline.

By using PySpark, this project enables large-scale data processing and distributed computing, making it ideal for handling big data problems. The implementation includes data preprocessing (handling categorical features), feature selection, and applying the linear regression model for prediction.

## Project Structure

- **Data:** `tips.csv` - A dataset containing restaurant bill information.
- **Script:** The main PySpark script that loads the data, processes it, and applies a linear regression model.
- **Results:** The model output and evaluation metrics like RMSE, R-squared, etc.

## Prerequisites

To run this project, you will need the following dependencies:

- **PySpark**: Apache Spark's Python API.
- **Python 3.12**: Ensure you have Python 3 installed on your system.

You can install PySpark using the following command:

```bash
pip install pyspark
