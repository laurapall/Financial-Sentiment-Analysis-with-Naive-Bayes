# Financial-Sentiment-Analysis-with-Naive-Bayes
Sentiment analysis project analyzing text data (financial reviews) to classify sentiments (positive, negative, neutral).



Sentiment Analysis with Naive Bayes
This repository contains code for performing sentiment analysis using the Naive Bayes algorithm on a dataset. The code covers data preprocessing, model training, and evaluation.

Table of Contents
•	Introduction
•	Dependencies
•	Usage
•	Dataset
•	Data Preprocessing
•	Model Training
•	Model Evaluation
•	Results
•	Contributing
•	License
![image](https://github.com/laurapall/Financial-Sentiment-Analysis-with-Naive-Bayes/assets/48211193/c2a187c5-6aab-4272-a532-fa4bc1a4a9fb)


Table of Contents
Introduction
Dependencies
Usage
Dataset
Data Preprocessing
Model Training
Model Evaluation
Results
Contributing
License
Introduction
Sentiment analysis is the process of determining the sentiment or emotional tone behind a piece of text. This project focuses on sentiment analysis using the Multinomial Naive Bayes algorithm. The dataset used for this analysis contains labeled sentiment data.

Dependencies
Make sure you have the following libraries installed to run this code:

numpy
pandas
matplotlib
seaborn
scikit-learn
nltk
plotly (used for data visualization)
You can install these libraries using pip:

bash
Copy code
pip install numpy pandas matplotlib seaborn scikit-learn nltk plotly
Usage
Clone this repository:
bash
Copy code
git clone https://github.com/your-username/sentiment-analysis.git
cd sentiment-analysis
Download the dataset and place it in the project directory as data_kaggle2.csv.

Run the code using a Python environment (e.g., Jupyter Notebook or a code editor).

Dataset
The dataset used in this project is data_kaggle2.csv. It contains text data and corresponding sentiment labels (positive, negative, or neutral).

Data Preprocessing
The dataset is loaded using pandas.
Sentiment labels are mapped to numerical values.
Data is cleaned, including the removal of stopwords and punctuation.
Model Training
The text data is converted to vectors using the CountVectorizer.
Multinomial Naive Bayes classifier is trained on the vectorized data.
Model Evaluation
The model is evaluated using accuracy score on a test set.
Results
The results of the sentiment analysis are presented as:

Percentage breakdown of sentiment labels in the dataset.
Visualizations of sentiment label distribution.
Model accuracy score on the test data.
Contributing
If you'd like to contribute to this project, feel free to open an issue or submit a pull request.

License
This project is licensed under the MIT License - see the LICENSE file for details.
