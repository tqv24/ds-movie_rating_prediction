# Movie Critic Rating Prediction

## Purpose
The purpose of this project is to predict the critic ratings of movies before any critic or audience ratings are posted. This can help movie producers, distributors, and marketers to gauge the potential reception of a movie based on various features such as runtime, genre, and release season.

## Repository Contents
This repository contains the following files and directories:

- `final.ipynb`: The main Jupyter Notebook containing the data analysis, feature engineering, model training, and evaluation.
- `requirements.txt`: A file listing the Python packages required to run the project.
- `movies.pkl`: This is the pickle file for the data that was used in the analysis.
- `README.md`: This file, providing an overview of the project and its contents.

## Project Overview
1. **Data Collection**:
   - Connect to a MLDS PostgreSQL database to retrieve movie data.
   - Load the data into a Pandas DataFrame for analysis.
   - For reproductory of the result, use the pickle file data.

2. **Data Preprocessing and Feature Engineering**:

   - Handle missing values and convert data types as necessary.
   - Create new features such as `kid_friendly`, `runtime_category`, `seasonal_release`, and `director_popularity`.

   - Generate dummy variables for categorical features such as `genre`.
   - Add new features like `director_popularity`.

3. **Model Training and Evaluation**:
   - Train multiple linear regression models with different sets of features.
   - Evaluate the models using metrics such as R², MAE, and RMSE.
   - Identify the best performing model and significant features.

4. **Model Improvement**:
   - Suggest potential improvements such as feature engineering, advanced modeling techniques, and data preprocessing.

## How to Run the Project
1. **Set up the environment**:
   - Using `pip`:
     ```bash
     pip install -r requirements.txt
     ```

2. **Run the Jupyter Notebook**:
   - Open [final.ipynb](http://_vscodecontentref_/0) in Jupyter Notebook or JupyterLab and run the cells to execute the analysis and model training.
