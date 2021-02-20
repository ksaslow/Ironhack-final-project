# Ironhack-Data-Analytics:
## Final Project
## Kate Saslow

# Who is "Happier"? 
### Sentiment Analysis of Tweets comparing my German and American Networks. 

### Introduction:
I used the Twitter API to gather tweets from my friends and followers. Through interacting with the API, I was able to gather tweets, location, gender, and other helpful information to use in my analysis. I filtered the tweets to only include people from Germany (and Austria and Switzerland) and America (and Canada) in my analysis. 

My hypothesis was that Germans would be more negative overall than Americans, but that the women in my American network would be more negative than the women in my German network. Only the former held true. One dimension of further analysis I would like to conduct is to train my own classification model to pick up on sarcasm and context better, because I have the feeling that the women I follow (overwhelmingly women in tech) are highly sarcastic on twitter.

### Analysis:
* Notebooks:
  * 1_Twitter-API-Wrangling-the-Data.ipynb
  * 2_Cleaning-and-Restructuring-Twitter-Data.ipynb
  * 3_Sentiment-Analysis-on-Twitter-Network.ipynb
  * 4_Visualizing-the-Twitter-Data.ipynb
  * 5_Twitter-Analysis-with-spaCy.ipynb
  * 6_Appendix_Training-NLP-Classification-Model.ipynb

* Data Folder:
  * all tweets wrangled from Twitter API
  * all dataframes cleaned/restructured/used for analysis and visualizations (refer to individual notebooks for which csv file needed at which step)
  * tweets processed for NLP

* WordClouds Folder:
  * all wordclouds generated in "5_Twitter-Analysis-with-spaCy.ipynb"
  * wordclouds of frequent words used in American and German tweets
  * wordclouds of frequent ADJECTIVEs used in American and German tweets

* Graphs Folder:
  * all png files created in "4_Visualizing-the-Twitter-Data.ipynb" to analyze and compare networks.
