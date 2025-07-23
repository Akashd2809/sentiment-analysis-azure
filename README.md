# Sentiment-analysis-azure

# Sentiment Analysis on Tweets using Azure ML

This project performs sentiment analysis on tweets using TextBlob, visualized via Seaborn and Matplotlib, and trained using Scikit-learn models. It is integrated with Azure Machine Learning for experimentation and tracking.

##  Features
- TextBlob for sentiment polarity
- Classification using Logistic Regression
- Visualization with Seaborn and Matplotlib
- AzureML integration

## Project Structure
sentiment-analysis-azure/

├── data/
           twitter-dataset.csv

├── notebooks/sentiment.ipynb

├── requirements.txt

└── README.md


## How to Run
1. Clone the repo
2. Install dependencies: `pip install -r requirements.txt`
3. Run the Jupyter Notebook: `jupyter notebook notebooks/sentiment.ipynb`

## Output Sample

Classification Report:
           precision    recall  f1-score   support
negative       0.00      0.00      0.00        96
 neutral       0.82      0.90      0.86       990
positive       0.89      0.89      0.89       914
accuracy                           0.85      2000

## Requirements
- Python 3.x
- textblob
- nltk
- scikit-learn
- pandas
- matplotlib
- seaborn
- azureml-core

## References
1. https://textblob.readthedocs.io/en/dev/install.html
2. https://medium.com/@maleeshadesilva21/preprocessing-steps-for-natural-language-processing-nlp-a-beginners-guide-d6d9bf7689c9

## Contact
Akash Deep Singh | Georgian College | Artificial Intelligence
