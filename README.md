# US-Elections-Analysis-
# Data Overview
Trump Reviews: 1156 entries, 7 columns (user, text, sentiment polarity, expression label).

Biden Reviews: 2788 entries, 7 columns (user, text, sentiment polarity, expression label).

Steps Performed
# Data Loading:

Trump Reviews and Biden Reviews datasets were loaded from CSV files.

# Sentiment Analysis:

TextBlob was used to determine the sentiment polarity (ranging from -1 to +1) of each tweet.

Example: Trump tweet at index 10 had a polarity of 0.0 (neutral); Biden tweet at index 500 had a polarity of 0.598 (positive).

# Labeling Sentiments:

Tweets were classified as "positive", "negative", or "neutral" based on their sentiment polarity.

Example: Trump tweet with polarity 0.15 labeled as "positive"; with polarity 0.00 labeled as "neutral".

Cleaning and Balancing Data:

Neutral tweets were dropped to balance the datasets.

Random sampling was used to create balanced subsets for further analysis.

# Sentiment Distribution:

Trump Reviews: 273 negative, 434 positive.

Biden Reviews: 581 negative.

# Summary
Sentiment analysis was applied to categorize tweets about Trump and Biden into positive, negative, and neutral sentiments.

Data cleaning and balancing ensured fair comparisons between the two sets.

The sentiment distribution gives insights into public opinion on both figures.
