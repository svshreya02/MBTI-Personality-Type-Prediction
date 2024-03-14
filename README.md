# MBTI Personality Type Prediction
This project focuses on predicting the Myers-Briggs Personality Type Indicator (MBTI) using various machine learning techniques. MBTI is a type indicator that categorizes individuals into one of 16 personality types based on their preferences in four dimensions: Introversion/Extraversion, Sensing/Intuition, Thinking/Feeling, and Judging/Perceiving.

# Dataset
The dataset used in this project is sourced from [[source](https://www.kaggle.com/datasets/datasnaek/mbti-type)], containing posts from individuals along with their MBTI type. The data preprocessing steps include cleaning, normalization, and splitting into training and testing sets.

# Requirements
- Python 3.x
- Pandas
- Numpy
- Matplotlib
- Seaborn
- Scikit-learn
- Keras
- XGBoost
- WordCloud
  
To install all the necessary packages, run:
```python
pip install pandas numpy matplotlib seaborn scikit-learn keras xgboost wordcloud
```

# Implementation
- Data Exploration and Visualization: Understanding the distribution of MBTI types and the common words used by each type.
- Preprocessing: Cleaning the text data and preparing it for model training.
- Feature Engineering: Extracting features from the text data that are useful for the prediction of MBTI types.
- Model Training: Implementing different models, including Artificial Neural Networks (ANN) and AdaBoost, to predict the MBTI type based on text data.
- Evaluation: Comparing the performance of different models using accuracy metrics and determining the best-performing model.
  
# Usage
To run this project, execute the Jupyter Notebook cells in sequence. The notebook includes comments and markdown explanations to guide you through the process.

# Contributing
Feel free to fork this project, make improvements, and submit a pull request. We're open to any contributions that improve the project.

# License
This project is licensed under the MIT License - see the LICENSE.md file for details.
