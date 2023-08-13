# SENTIMENT-ANALYSIS-WITH-POWER-BI-NIGERIA-ELECTION-TWEETS-
This undertaking, named "Sentiment Analysis of the 2023 Nigeria Presidential Election Tweets," delved into data analytics to assess public sentiment towards the candidates post-election. By harnessing Twitter data, the project meticulously tracked and evaluated sentiments related to the three main presidential contenders. The resulting report offers a comprehensive insight into post-election public perceptions, contributing valuable analytical perspectives for understanding the dynamics of the electoral process.

## About the Dataset

The dataset utilized in this analysis was sourced from Kaggle, a prominent platform for data science and analytics resources. This dataset served as the foundation for conducting comprehensive sentiment analysis on the 2023 Nigeria Presidential Election Tweets, facilitating an in-depth exploration of public sentiment towards the candidates and their electoral journey [Dataset Link](https://www.kaggle.com/datasets/gpreda/nigerian-presidential-election-2023-tweets).

### Data Columns for Sentiment Analysis of 2023 Nigeria Presidential Election Tweets

The dataset extracted from Kaggle comprises the following key columns, each contributing to a comprehensive analysis of sentiment in relation to the 2023 Nigeria Presidential Election:

1. **ID**: Unique identifier for each tweet.
2. **User Name**: The username associated with the tweet.
3. **User Location**: Location details provided by the user.
4. **User Description**: A brief description provided by the user.
5. **User Created**: The date when the user's account was created.
6. **User Followers**: Number of followers the user has.
7. **User Friends**: Number of friends or accounts the user follows.
8. **User Favorites**: Number of tweets the user has marked as favorites.
9. **User Verified**: Indicates whether the user's account is verified.
10. **Date**: The date and time when the tweet was posted.
11. **Text**: The content of the tweet itself.
12. **Hashtags**: Any hashtags included in the tweet.
13. **Source**: The source from which the tweet was posted (e.g., device or application).
14. **Retweets**: Number of times the tweet has been retweeted.
15. **Is Retweet**: A binary indicator of whether the tweet is a retweet or an original post.

This dataset, stored in CSV format, forms the foundation for conducting a comprehensive sentiment analysis of the Nigeria Presidential Election tweets. By leveraging these data columns, valuable insights into public perceptions and reactions can be extracted, contributing to a deeper understanding of the electoral landscape.

## DATA CLEANING
### The Power Query Transformation Process:

The transformation process commenced within Power Query Editor, a robust tool within Microsoft Power BI. This environment provided an avenue to meticulously refine the dataset and mold it into a coherent structure for sentiment analysis. The following key steps were undertaken:   
**Data Source**
![Data Source](https://github.com/Ainaganiu/SENTIMENT-ANALYSIS-WITH-POWER-BI-NIGERIA-ELECTION-TWEETS-/blob/main/Picture/SOURCE.png)
**Promoting Headers**   
 A key step in the data cleaning process was the utilization of Power Query's built-in functionality to promote headers. By analyzing the first row of data, the Power Query Editor accurately identified column names, ensuring precision in subsequent transformations.
 ![Promoting Headers](https://github.com/Ainaganiu/SENTIMENT-ANALYSIS-WITH-POWER-BI-NIGERIA-ELECTION-TWEETS-/blob/main/Picture/SOURCE.png)
 In the course of dataset refinement, certain columns including "Date," "Content," "Location," and "Platform" were deliberately excluded from the dataset. This curation was undertaken to streamline the focus of the analysis and optimize the dataset for sentiment assessment and subsequent insights extraction.

 **Creating the Sentiment Score**   
 The dataset underwent a meticulous cleansing process through the utilization of the built-in "Clean" function applied to the  "Custom column", rendering the data primed for analysis. Subsequent to this preparation, the Text Analytics function from Azure Cognitive Service was harnessed to generate sentiment scores for each entry within the customized "Text" column. This approach facilitated the quantification of sentiment nuances, culminating in a comprehensive evaluation of the dataset's emotional undercurrents.
 ![Sentiment Score](https://github.com/Ainaganiu/SENTIMENT-ANALYSIS-WITH-POWER-BI-NIGERIA-ELECTION-TWEETS-/blob/main/Picture/score_sentiment.png)


