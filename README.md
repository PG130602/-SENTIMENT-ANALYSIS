# SENTIMENT-ANALYSIS

*COMPANY* : CODTECH IT SOLUTIONS

*NAME* : Pavan Vadiraj Gokak

*INTERN ID* : CT08WT194

*DOMAIN* : Data Analytics

*DURATION* : 8 WEEKS

*MENTOR* : Neela Santhosh Kumar 

## ✈️ US Airline Tweet Sentiment Analysis
This project performs sentiment analysis on tweets directed at US airlines using both rule-based and transformer-based methods. It extracts and compares sentiments, emotions, and topics from the data to generate business insights.

## 📂 Dataset
Source: Twitter US Airline Sentiment Dataset
Columns used: text, airline_sentiment, airline, negativereason

## 🛠️ Features & Workflow
1.Data Loading
Uploads and loads the dataset CSV.
Keeps only relevant columns.

2.Text Cleaning
Lowercasing, URL/mention/hashtag removal.
Special character stripping and whitespace normalization.

3.Visualizations
Sentiment distribution.
Sentiment by airline.
Common reasons for negative sentiment.
Word clouds by sentiment.

4.Sentiment Analysis
VADER: Rule-based model for polarity scoring.
RoBERTa: Pretrained transformer from cardiffnlp/twitter-roberta-base-sentiment.

5.Emotion Analysis
NRCLex for emotion tagging (joy, sadness, anger, etc.).
Aggregated emotion distribution plots.

6.Keyword Extraction
Top 30 keywords using CountVectorizer.

7.Topic Modeling
LDA (Latent Dirichlet Allocation) to uncover 5 latent topics in tweets.

8.Model Evaluation
Accuracy and classification report comparing VADER and RoBERTa with actual labels.

## 📦 Dependencies
pip install pandas numpy matplotlib seaborn nltk wordcloud scikit-learn nrclex transformers
nltk.download('vader_lexicon')
nltk.download('punkt_tab')

## 📊 Output Examples
Classification accuracy for both VADER and RoBERTa
Top 5 reasons for negative airline sentiment
Emotion and sentiment visualizations
Dominant topic assignment per tweet

## 🔍 Insights
Allows businesses to track public sentiment trends.
Identifies specific complaint categories and emotion tones.
Offers comparative performance of traditional vs. deep learning sentiment models.

## 👤 Author
This project was created by Pavan Gokak as part of a task for CODTECH IT SOLUTIONS, showcasing the use of NLP and transformer-based models for sentiment analysis on airline-related tweets. It highlights the application of VADER, RoBERTa, and emotion analysis to extract insights from social media data in real-world scenarios.
