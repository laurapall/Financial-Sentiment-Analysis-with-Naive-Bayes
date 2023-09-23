# Sentiment Analysis using Python

This project is a simple sentiment analysis task performed using Python. 
It includes loading a dataset, preprocessing the text data, training a Multinomial Naive Bayes classifier, and evaluating the model's performance.

## Requirements

Make sure you have the following libraries installed to run this code:

- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `nltk`
- `scikit-learn`


## Dataset
The dataset used in this project is stored in a CSV file called data_kaggle2.csv. The dataset contains text data and corresponding sentiment labels.
- Data source: https://www.kaggle.com/datasets/sbhatti/financial-sentiment-analysis?select=data.csv 

## Exploratory Data Analysis
The code begins with importing necessary libraries and loading the dataset. It performs some basic exploratory data analysis, including checking for null entries and displaying summary statistics.

## Data Preprocessing
Text data preprocessing is a crucial step in sentiment analysis. The code preprocesses the text data by:

- Mapping sentiment labels to numerical values (1 for positive, -1 for negative, 0 for neutral).
- Calculating the percentage distribution of sentiment labels in the dataset.

## Data Visualization
The code uses matplotlib and seaborn to create data visualizations, including:

- A pie chart showing the distribution of sentiment labels.
- A bar chart displaying the count of each sentiment label.

## Model Building
The sentiment analysis model is built using a Multinomial Naive Bayes classifier. The code performs the following steps:

- Splits the dataset into training and testing sets.
- Converts text data into numerical features using Count Vectorization.
- Trains the Multinomial Naive Bayes classifier on the training data.
- Makes predictions on the test data.

## Model Evaluation
The code calculates the accuracy score of the sentiment analysis model to evaluate its performance.

## Running the Code
To run this code, make sure you have the required libraries installed and the dataset file (data_kaggle2.csv) in the same directory as the script. Then, execute the script.

## Conclusion
This project demonstrates a basic sentiment analysis task using a Multinomial Naive Bayes classifier. The accuracy score obtained provides an initial assessment of the model's performance. Further improvements, such as fine-tuning the model or using more advanced techniques, can be explored to enhance sentiment analysis results.

Feel free to customize and expand upon this project as needed.

## Contact
If you have any questions, suggestions, or issues related to this project, feel free to contact us at [flaurapall@gmail.com].

## Author
* [Pall Laura](https://github.com/laurapall)






