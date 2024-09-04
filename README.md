# End to End Machine Learning project

## Overview

This project is an end-to-end machine learning application designed to predict student exam performance based on various demographic and educational factors. It includes data ingestion, preprocessing, model training, and a web interface for predictions.

## Main Objectives

1. **Data Ingestion**: 
   - Collect and split data into training and testing sets.
   - Store processed data for further analysis.

2. **Data Transformation**:
   - Preprocess data using pipelines for categorical and numerical features.
   - Handle missing values and scale features appropriately.

3. **Model Training**:
   - Train multiple machine learning models.
   - Evaluate and select the best model based on performance metrics.

4. **Prediction**:
   - Provide a user-friendly web interface for predicting student performance.
   - Allow users to input data and receive predictions on math scores.

5. **Deployment**:
   - Set up a Flask application for easy deployment and user interaction.
   - Use AWS Elastic Beanstalk for scalable deployment if needed.

## Project Structure

- **.ebextensions**: Configuration for AWS Elastic Beanstalk.
- **logs**: Directory for storing log files.
- **mlproject.egg-info**: Metadata for the project package.
- **notebook**: Contains Jupyter notebooks for exploratory data analysis and model training.
  - **1. EDA STUDENT PERFORMANCE.ipynb**: Notebook for exploratory data analysis.
  - **2. MODEL TRAINING.ipynb**: Notebook for model training.
- **src**: Source code directory.
  - **components**: Modules for data ingestion, transformation, and model training.
  - **pipeline**: Scripts for prediction and training pipelines.
  - **exception.py**: Custom exception handling.
  - **logger.py**: Logging configuration.
  - **utils.py**: Utility functions.
- **templates**: HTML templates for the Flask web application.
- **venv**: Virtual environment for managing dependencies.

## Key Files

- **app.py**: Flask application script.
- **application.py**: Main entry point for the application.
- **requirements.txt**: Lists Python dependencies needed for the project.
- **setup.py**: Script for packaging and installation.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/ganavihemachandra/End-to-End-Machine-Learning-Project.git

2. Navigate to the project directory:
   cd End-to-End-Machine-Learning-Project

3. Create a virtual environment:
   python -m venv venv

4. Activate the virtual environment:

   On Windows:
   venv\Scripts\activate
   
   On macOS/Linux
   source venv/bin/activate

5. Install the dependencies
   pip install -r requirements.txt

## Usage
1. Run the Flask application:
   python application.py

2. Open your web browser and go to http://localhost:5001 to access the application.
