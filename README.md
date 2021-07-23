# Sentiment analysis

Natural Language Processing is an art of extracting information from text. 
Using this we analyse emotions/sentiments of a given text or essay.We also scrape tweets and find out the emotions. attached to the tweets.

## Cleaning Text Steps:
1. Create a text file read.txt and paste any essay we want to analyse.
2. Convert the letter to lowercase.
3. Remove punctuations like .,!? etc.

### NLP Emotion Algorithm:
1. Check if the word in the final word list is also present in emotion.txt
 - open the emotion file
 - Loop through each line and clear it
 - Extract the word and emotion using split
2. If word is present -> Add the emotion to emotion_list
3. Finally count each emotion in the emotion list using counter from collections and show emotions using Matplotlib

### Twitter data analysis
1. Install GetOldTweets3 package.
2. Create twitter_analysis.ipynb file
3. Write function to get tweets using GetOldTweets
4. Merge code from main.ipynb file to see graph of emotions

### Using NLTK for sentiment analysis.
1. Install nltk package.
2. Use the setting.py file to download all the packages necessary
3. Run main_nltk.py file in which we used SentimentIntensityAnalyzer,word tokenizer and wordNetLemmatizer for sentiment analysis with NLTK.