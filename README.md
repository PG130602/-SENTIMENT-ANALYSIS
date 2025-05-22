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

![Image](https://github.com/user-attachments/assets/13727329-132f-4f8a-afd1-e8811bb6a9cd)
![Image](https://github.com/user-attachments/assets/6d257127-90aa-4902-8f10-0368997e64b0)
![Image](https://github.com/user-attachments/assets/e0932367-63ba-4f04-bdea-f20b6518ec82)
![Image](https://github.com/user-attachments/assets/60e8d11a-d677-4e50-b44f-935712c5c5fd)
![Image](https://github.com/user-attachments/assets/50c815ee-f6f0-433f-8336-38bdce28ff03)
![Image](https://github.com/user-attachments/assets/ba713397-da6e-4960-8b15-445f250b21c3)
![Image](https://github.com/user-attachments/assets/e62a8923-63a7-4aa3-a5bc-13b4ece720a6)
![Image](https://github.com/user-attachments/assets/76a67291-a410-40e1-8fee-4dbef283272f)
![Image](https://github.com/user-attachments/assets/e276f626-5050-4ec4-930c-f898ebc11899)
![Image](https://github.com/user-attachments/assets/49791d03-289c-4ed2-b968-f8f5c6407954)
![Image](https://github.com/user-attachments/assets/55a3540b-7902-40f7-a468-23006d728874)
![Image](https://github.com/user-attachments/assets/54cf0cf4-2ea6-4a4e-aacf-4c7b2f5716c3)
![Image](https://github.com/user-attachments/assets/6a92ffec-74ce-4002-b0dd-823de247e201)
![Image](https://github.com/user-attachments/assets/6d9bc2de-14d9-43e8-be70-e87e252668d1)
