# sentiment_analysis
<p>In this project I will investigate the basics of Natural Language Processing (NLP) and aim to predict whether a sample of tweets are either positive or negative. This will consist of combining machine learning principles with text. I will use mathematics and statistics to get the text in a format that algorithms can understand.
<p><b>Understanding the problem statement and business case</b>
<p><li>Natural language processors (NLP) works by converting words (text) into numbers
<li>These numbers are used to train an AI/ML models to make predictions
<li>Predictions could be sentiment inferred from social media posts and product reviews
<li>AI/ML-based sentiment analysis is crucial for organisations to automatically predict whether their customers are happy or not
<li>The process could be done automatically without having humans manually review thousands of tweets and customer reviews
<p>In this case study, we will analyse Twitter tweets to predict people’s sentiment
<p>For instance:
<p>TWEET: “Good morning everyone! Such a beautiful day!!” -> SENTIMENT ANALYSIS (NLP MODEL) -> SENTIMENT: POSITIVE (Label 0)
<br>TWEET: “The food was awful and the waiters rude.” -> SENTIMENT ANALYSIS (NLP MODEL) -> SENTIMENT: NEGATIVE (Label 1)
<p>The objective of this task is to detect hate speech in tweets. For the sake of simplicity, we say a tweet contains hate speech if it has a derogatory or negative sentiment associated with it.
  <p><b>Content</b><p>
Full tweet texts are provided with their labels for training data.<br>
Mentioned users will be redacted.<br>
<p>1,600,000 tweets extracted using the twitter api . The tweets have been annotated (0 = negative, 4 = positive) and they can be used to detect sentiment .
Data can be obtained from this kaggle dataset: https://www.kaggle.com/kazanova/sentiment140
