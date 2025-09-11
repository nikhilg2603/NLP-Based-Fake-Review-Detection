# Project Overview

The dataset contained the reviews posted by several amazon users along with its metadata and the item metadata.

Identify fake reviews or anomalies in reviews by looking at the ratings and the review text: For example, if the review text has positive words/sentiment, it can be assumed to receive high rating, take it as an anomaly incase of the contrary. Similar logic applies for negative words/sentiments.

● We used text based analysis (ex. Negative Word frequency, LDA) for this purpose.

● Used a regression model to evaluate whether the presence of fake reviews relates to the price of the item
