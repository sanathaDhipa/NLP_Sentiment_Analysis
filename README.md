<!-- ABOUT THE PROJECT -->
## About The Project

This project focuses on analyzing the sentiment of Twitter posts related to Prabowo Subianto during the Indonesia Public Election held on May 28-29, 2019. The dataset used for this analysis is sourced from [Indonesia Public Election Twitter Sentiment repository](https://github.com/audhiaprilliant/Indonesia-Public-Election-Twitter-Sentiment-Analysis/blob/master/Datasets/Sentiment%20Data%20Prabowo%20Subianto.csv).

Two machine learning models were developed which is a Support Vector Machine (SVM) model and a Naive Bayes model. The project begins with data preprocessing, which includes cleaning the tweets, tokenizing the text, and applying stemming to reduce words to their root forms. The preprocessing step also involves removing stopwords and non-alphabetic characters to ensure that only relevant words are retained for analysis.

To address class imbalances within the dataset, oversampling techniques were applied using the RandomOverSampler method, resulting in a balanced dataset that improves model performance. The features were extracted using TF-IDF (Term Frequency-Inverse Document Frequency) vectorization, enabling the models to capture the importance of words in the context of the entire dataset.



### Built With

* [![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)](https://www.python.org/)
* [![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org/)
* [![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)](https://matplotlib.org/)
* [![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)](https://numpy.org/)
* [![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)](https://scikit-learn.org/stable/)
