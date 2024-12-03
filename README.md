# Emotional Health Monitoring on Social Media


![Screenshot 2024-01-14 161854](https://github.com/nabil0812/emotional-health-monitoring-on-social-media/assets/105557940/b91ccde0-8661-47ec-b2f7-7421378b6a58)



## INTRODUCTION :


The evolution of internet and communication technologies, notably online social networks, has revolutionized electronic interactions and communication patterns. Platforms like Face-book, Twitter, Instagram, and similar ones not only serve as hosts for various forms of con-tent but also enable users to express their emotions and sentiments on various topics and issues. 

On the one hand, this fosters open and unrestricted contributions and responses on social networking sites. On the other hand, it presents an opportunity for healthcare professionals to gain insights into the mental state of individuals based on their reactions to specific topics. 




## AIMS & OBJECTIVES :


* Substantial datasets retrievable from social media platforms like Twitter hold the potential to furnish meaningful understanding of human actions and feelings. X, being one predominant platforms, serves as a common avenue for individuals to express their emotions and viewpoints, offering an opportunity to acquire a more profound comprehension of their psychological wellbeing everyday decision-making, and perceptions of life quality. 
* Depression, a prevalent mental disorder, carries the risk of leading to severe consequences, including suicides.
* This project's objective is to deploy supervised machine learning techniques for the identification of tweets exhibiting depressive traits.



## METHODOLOGY USED :


### Datasets :

We require two datasets: one comprising tweets exhibiting depressive characteristics obtained through the X API, and the other consisting of arbitrary messages. The data mining process involved extracting over 10,000 tweets using the X API and the Tweepy library. The source data collected from X is available here, while arbitrary messages were obtained from Kaggle datarepository. The cleaned data-repository is utilized for training machine learning algorithms.


### Workflow :

* Data Collection: Acquired a well-balanced dataset from both the Twitter API and the Kaggle dataset.
* Data Preprocessing: Executed thorough data cleaning, exploration, processing, annotation, and analysis employing NLP libraries.
* EDA and Feature Selection: Utilized techniques like Count Vectorizer, TF-IDF, and spaCy word embedding model for exploratory data analysis and feature selection.
* Model Selection: Opted for Logistic Regression machine learning algorithm
* Model Training: Applied the Scikit-Learn library for training the selected models.
* Inference: Assessed model performance using metrics like F1-Score, Confusion Matrix, and ROC-AUC to derive meaningful insights.
* Data Product: Formulated a Flask-based web application for efficient deployment and interaction with the trained models.
  

## HOW IT WORKS !

* Clone this repository

```bash
git clone https://github.com/nabil0812/emotional-health-monitoring-on-social-media.git 
```

* Create a virtual environment

```bash
python3 -m venv env
```

* Activating a virtual environment

```bash
source env/bin/activate
```

* Run the Flask Application

- Start flask web server: `python app.py`
- The server will start on the address http://127.0.0.1:5000 [if port 5000 is not occupied]

  


## REFERENCES :

* https://www.apa.org/topics/depression
* https://www.kaggle.com/ywang311/twitter-sentiment/data
* https://towardsdatascience.com/text-classification-with-nlp-tf-idf-vs-word2vec-vs-bert-41ff868d1794
  





