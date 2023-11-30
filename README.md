# Python_Data_Analysis_Project

## Read Me

Music Release Year Prediction

## Overview

This Colab notebook is part of a project focused on predicting the release year of songs based on audio features. The dataset used is a subset of the Million Song Dataset (MSD), which spans from 1922 to 2011. The project aims to explore trends in music evolution and leverage machine learning to predict release years.

## Dataset

The dataset consists of audio features, particularly timbre averages and covariances, obtained through segmenting each song into 12 segments. The target variable is the release year of the song.

- *Dataset Source:* [Million Song Dataset (MSD)](http://labrosa.ee.columbia.edu/millionsong/)
- *Data Shape:* (515345, 91)

## Project Components

1. *Exploratory Data Analysis (EDA):*
   - Initial analysis of the Billboard charts from 1950 to 2015 to understand trends in popular music.
   - Exploration of the MSD subset to gain insights into the features and distribution of the data.

2. *Data Preprocessing:*
   - Handling missing values, if any.
   - Feature scaling or normalization to prepare the data for machine learning models.

3. *Machine Learning Models:*
   - Implementation of linear regression for the baseline model.
   - Evaluation and exploration of other models like Random Forest if baseline performance is suboptimal.
   - The notebook MJ_Final implements the neural models, the Linear and Logistic Regressions and the Decision Tree Classifier
   - The notebook machine_learning_model implements the Random Forest Classifier

4. *Evaluation Metrics:*
   - Assessment of model performance using metrics such as Mean Absolute Error (MAE) and accuracy.

## Instructions

1. *Run the Notebooks Sequentially:*
   - Run each cell sequentially to ensure proper execution and understanding of the step-by-step process.

2. *Customization:*
   - Feel free to customize parameters, explore additional visualizations, or try different machine learning models.

3. *Dataset Access:*
   - Ensure access to the MSD dataset, and update the file path or download instructions if needed.

4. *Contribution:*
   - Contributions and suggestions are welcome! Feel free to fork the repository, make changes, and submit pull requests.

## Acknowledgments

- This project utilizes the Million Song Dataset, and we extend our gratitude to the contributors and maintainers of the dataset.
