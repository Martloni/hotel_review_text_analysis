## Hotel Review Sentiment analysis

Hotels play crucial role in travelling and the text reviews provided by clients is a reflection of their of their experience with the hotel. 

#### **Data Source**
The [data](https://www.kaggle.com/andrewmvd/trip-advisor-hotel-reviews) used for this analsysis was obtained from kaggle. The dataset consist of 20,491 reviews

#### **Project Goal**
The goal of this project was to build a classifier that predicts customer reviews as either positive or negative. 
Here is the breakdown of the project: 
* Exploratory Data Analysis
* Data Cleaning and preprocessing
	* Removing URL
	* Lower casing
	* Dealing with contractions
	* Remove punctuations
	* Tokenization
	* Removal of stopwords
* Train/Test Split
* Vectorization of text data using Count Vectorizer
* TF-IDF vectorization of text
* Lemmatization 
* N-Grams
* Model fit and prediction by comparing six different classifiers
* Parameter optimization with RandomSearchCV



#### Conclusion
Based on the confusion matrix, LinearSVC provided the highest number of true positive and true negative label. The accuracy of the model on both the validation and test data was approximately 93 percent. 
