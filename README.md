# Social-Media-and-Music-Analysis
## Overview
This project includes two analyses: Social Media Usage Analysis and Music Popularity Prediction. Each analysis focuses on different datasets and objectives.

## Files
- `Data-Analysis.ipynb`: Jupyter notebook containing the code and analysis for the Social Media Usage Analysis and music popularity prediction.
- `syp-16-data.csv`: Dataset used for the Social Media Usage Analysis.
- `music.csv`: Dataset used for the Music Popularity Prediction.

## Social Media Usage Analysis

### Overview
The Social Media Usage Analysis examines the usage of various social media platforms across different age groups.

### Dataset
The dataset (`syp-16-data.csv`) used in this analysis contains information about respondents' ages and their usage of different social media platforms.

### Analysis
1. Data Loading and Preprocessing:
   - Loaded the dataset using Pandas.
   - Preprocessed the data to handle any missing values or inconsistencies.

2. Exploratory Data Analysis (EDA):
   - Grouped the data by age and calculated the total number of respondents for each social media platform.
   - Plotted bar charts to visualize the distribution of respondents across different social media platforms by age group.

3. Decision Tree Classification:
   - Used a Decision Tree Classifier to predict the age group of respondents based on their social media usage.
   - Trained the model using the entire dataset and visualized the decision tree.

### Dependencies
- Python 3.x
- pandas
- numpy
- matplotlib

## Music Popularity Prediction

### Overview
The Music Popularity Prediction analysis aims to predict whether a song will make it to the Top 10 of Billboard’s Hot 100 Chart.

### Dataset
The dataset used in this analysis contains information about songs from the Top 10 of Billboard’s Hot 100 Chart from 1990-2010, along with other songs that did not make the list.

### Analysis
1. Data Preprocessing:
   - Removed unnecessary columns.
   - Split the dataset into features and target variable.

2. Model Building:
   - Utilized three classification models: K-Nearest Neighbors (KNN), Decision Tree, and Support Vector Machine (SVM).
   - Constructed pipelines for each model including data scaling and model fitting.
   - Used grid search to find the best hyperparameters for each model.

3. Model Evaluation:
   - Evaluated each model's performance using metrics such as accuracy, precision, recall, and F1 score.
   - Compared the performance of different models and scaling techniques.

### Dependencies
- Python 3.x
- pandas
- scikit-learn
- matplotlib

### Usage
1. Clone the repository.
2. Install the required dependencies using pip:
3. Run the Jupyter notebook or Python script to reproduce the analysis.

### Results
- The analysis provides insights into the distribution of social media usage among different age groups.
- The decision tree classifier can predict the age group of respondents based on their social media usage patterns.
- The SVM model with MinMaxScaler achieved the highest accuracy of 84.4% and an F1 score of 0.337 for predicting music popularity.

### Conclusion
Both analyses offer valuable insights into their respective domains. Further exploration and refinement of models could lead to more accurate predictions and deeper understanding of the underlying trends.
