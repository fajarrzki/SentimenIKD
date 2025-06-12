Sentiment Analysis of IKD App Reviews on Google Play Store (Lexicon-Based)
This repository contains a sentiment analysis project focused on user reviews of the Identitas Kependudukan Digital (IKD) application on the Google Play Store. The analysis is conducted using a lexicon-based approach to determine the overall sentiment of users toward the application.

📁 Repository Structure
Scraping.ipynb
Scrapes the latest 2,000 user reviews from the IKD app on Google Play Store using google-play-scraper.

TextPreprocessing.ipynb
Cleans and preprocesses the raw review text, including case folding, punctuation removal, stopword removal, and tokenization.

Lexicon Implement.ipynb
Applies a lexicon-based sentiment analysis method using an Indonesian sentiment lexicon to classify the reviews as positive, negative, or neutral.

🛠️ Tools & Libraries Used
Python

Pandas

Numpy

Sastrawi

Google Play Scraper

Lexicon-based sentiment analysis (using an Indonesian sentiment lexicon)

📊 Output
The final output includes:

Sentiment classification of each review

Summary statistics of sentiment distribution

Sample visualizations (e.g., pie charts or bar plots if added)

📌 Notes
The data used in this project is publicly available user reviews collected from the Google Play Store.

The sentiment analysis is lexicon-based and may not reflect nuanced or sarcastic user expressions.

📄 License
This project is for educational and research purposes only.
