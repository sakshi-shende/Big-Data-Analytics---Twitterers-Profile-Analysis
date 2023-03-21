# Twitterers Profile Analysis

## Objective
Twitter is one of the most popular social media platforms that enable real-time communication among ~100M users worldwide and ~500M tweets sent daily. Twitter has become an important source of real-time news and information related to education, news, sports, health, etc.

The project aims to identify whether Twitter is a credible source of information for important trends and topics in education by answering the following questions:

* Who are the most influential Twitterers?
* What type of Twitter users contribute to the platform's education-related discussion?
* Are there any spikes in activity and shifts in geographical distribution to Twitterers?
* Are the tweets original content or just copies of existing tweets and retweets?

## Data Source Overview
We have ~100 M tweets (~500GB) collected on the topics of education, schools, universities, learning, knowledge sharing, etc. These tweets are spread across 50K JSON files in deeply nested format. The tweets are available from April 2022 to February 2023.
The full layout can be seen here: https://dev.twitter.com/overview/api/tweets

## Database & tools
pySpark, Pandas, Matplotlib &  Seaborn (for data visualization), Google Cloud Platform, SimHash and Jaccard Distance (for similarity analysis)
