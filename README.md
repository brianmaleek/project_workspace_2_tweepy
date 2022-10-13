# We-rate-dogs-Twitter
Data wrangling refers to the process of gathering, assessing and cleaning the raw data available into a more usable format, so as to create interesting and trustworthy analyses and visualizations.
# Project overview
The main purpose of this report is to summarize the effort deployed to wrangle the data of the WeRateDogs Twitter, which is a Twitter account that rates people's dogs with a humorous comment about the dog.
For this project, I have gathered 3 sources of data: 
* The twitter archive file, that I downloaded it manually from Udacity servers. 
* The tweet image predictions, I downloaded it programmatically using the Requests library and the following URL: https://d17h27t6h515a5.cloudfront.net/topher/2017/August/599fd2ad_image-predictions/image-predictions.tsv 
* Twitter API & JSON: I downloaded it from the Udacity servers and read this text file line by line into a pandas DataFrame with tweet ID, retweet count, and favorite count. I loaded the 3 raw data files into separate tables: twitter_archive, image_predictions, tweets_df. 

After gathering the data, the second step is to assess data of the three datasets, visually and programmatically. The main objective of this section is to look for uncleaned data in all the three DataFrames, in particular for quality issues (completeness, validity, accuracy and consistency) and tidiness. The later is where each variable forms a column, each observation forms a row and each type of observational unit forms a table.

The third step is the cleaning task. It doesn’t mean that I have changed the data to make it say something different, I have just cleaned data when inaccurate, removed when irrelevant and replaced when missing.
# Evaluation
My project was reviewed by a Udacity reviewer. All criteria found in the rubric met specifications for me to pass.
