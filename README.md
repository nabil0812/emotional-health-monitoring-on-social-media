![image](https://github.com/nabil0812/emotional-health-monitoring-on-social-media/assets/105557940/3f5fcb00-65ff-4516-9809-ce7219e8b716)# emotional-health-monitoring-on-social-media


![Screenshot 2024-01-14 161854](https://github.com/nabil0812/emotional-health-monitoring-on-social-media/assets/105557940/b91ccde0-8661-47ec-b2f7-7421378b6a58)



## INTRODUCTION :


Social media platforms like Twitter, Instagram, and Facebook play significant roles in our daily lives, and their popularity has surged, particularly during the pandemic. Research indicates an increased likelihood of individuals sharing their emotions and thoughts on Twitter since the onset of the Covid-19 crisis. While positive emotions may not always correlate with higher life satisfaction, negative emotions are often seen as more authentic expressions of one's true feelings.

Depression, a prevalent mental disorder that extends beyond mere sadness, manifests through various signs. These signs include a diminished interest in daily activities, notable changes in weight, disruptions in sleep patterns (either insomnia or excessive sleeping), fatigue, difficulty concentrating, feelings of worthlessness or excessive guilt, and in severe cases, recurrent thoughts of death or suicide. Fortunately, depression is a condition amenable to treatment. A combination of therapy and antidepressant medication is commonly employed to address this mental health issue.




## AIMS & OBJECTIVES :


* Extracting extensive datasets from social media channels like Twitter holds the potential to yield valuable insights into human behavior and emotions.
* Twitter stands out as a prevalent platform for individuals to express their emotions and opinions, offering a rich source for gaining deeper insights into mental health, everyday decision-making, and perceptions related to quality of life.
* Depression, a widespread mental disorder that can lead to severe consequences such as suicide, affects over 300 million people globally each year.
* The objective of this project is to employ supervised machine learning techniques to identify tweets that exhibit characteristics indicative of depression.




## METHODOLOGY USED :


### DATASETS :

We require two datasets: one comprising tweets exhibiting depressive characteristics obtained through the X API, and the other consisting of arbitrary messages. The data mining process involved extracting over 10,000 tweets using the X API and the Tweepy library. The source data collected from X is available here, while arbitrary messages were obtained from Kaggle datarepository. The cleaned data-repository is utilized for training machine learning algorithms.


### WORKFLOW :

* Data Collection: Acquired a well-balanced dataset from both the Twitter API and the Kaggle dataset.
* Data Preprocessing: Executed thorough data cleaning, exploration, processing, annotation, and analysis employing NLP libraries.
* EDA and Feature Selection: Utilized techniques like Count Vectorizer, TF-IDF, and spaCy word embedding model for exploratory data analysis and feature selection.
* Model Selection: Opted for a diverse set of models, including Logistic Regression, Support Vector Machine (SVM), K-Nearest Neighbors (k-NN), Decision Tree Classifier, Random Forest Classifier, Neural Network, LSTM, and Naïve Bayes.
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

* Clean the dataset

```bash
python clean.py <file_name> 
```
* Train the best model
```bash
python train.py <file_name> <model_name>
```
* Predict 
```bash
python predict.py <tweet.txt> SVM
```
* Run the Flask Application

- Start flask web server: `python app.py`
- The server will start on the address http://127.0.0.1:5000 [if port 5000 is not occupied]

  


## References :

* https://www.apa.org/topics/depression
* https://www.kaggle.com/ywang311/twitter-sentiment/data
* https://towardsdatascience.com/text-classification-with-nlp-tf-idf-vs-word2vec-vs-bert-41ff868d1794
  





