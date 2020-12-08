

#                                                   Twitter Data Analysis: Netflix growth in a COVID-19 world

Netflix is one of the biggest and most valuables streaming companies of all times, and everyday tens of thousands of people are been tweeting, liking, and retweeting about Netflix trending shows. The streaming service is hard to avoid on Twitter, getting validation from their strategy encourages the platform to expand their Twitter interaction with their audience by sharing memes about their own shows and creating polls and questionaries about their services. As we know, COVID-19 has had a big impact in everyone's life, even in big companies like Netflix. So, is Netflix having a positive outcome from it's subscribers during a pandemic? How are viewers feeling about Netflix content lately?. To answer our question our team has collected data from Twitter, from which we used R Studio to research among data, create a hypothesis, and produce models that will lead us to a better understanding of this topic. 

# Motivation and Objective

##  Motivation
We look forward to analyze data and running models in order to understand why are these shows so popular and conclude if they are worth it to be the best top shows regarding the spectators opinions. Also, we want to discover the relationship between these shows and movies and the audience feelings during COVID times. The impact of these shows during a pandemic and during the Holidays could make the audience feel overwhelmed, making them miss their families and feel sad or lonley. In the other hand, it might make them feel happier, bringing them joyful and warm thoughts.

## Objective
Our objective for this project is to analyze tweets related to Netflix in order to analyze the trends of the most popular streaming platform. Due to COVID-19, Netflix subscribers have been rising up quicker than ever before as people look to the platform as a major source of entertainment. We would like analyze their audience sentiment, see what people are saying on twitter about Netflix and the latest top 10 rated shows and movies offered by the platform. Some questions we will ask are: How has the brand image of Netflix changed over the years?  What shows and movies are receiving the most recognition? Is their audience showing a positive, negative, or neutral reaction to these shows and movies?

# Data Research

## Collecting Data
The first step was to get access to Twitter API and then get our keys in order to create a code that could constantly pull out data from Twitter within the past 7 days from the code beign ran. Afterwards, we were able to clean the data. Since is a trending topic, the tweets have too many @ and # that maybe won't be helpful on our analysis, therefore we needed to filter our data in order to find just the tweets that would be helpful for our analysis. Finally, we will extract the show ‘s names to analyze the sentiment of each show and the overall polarity on the different opinions. We searched for keyphrases like #SelenaNetflix, #Selena, #BigMouth, #BigMouthNetflix, #VirginRiver, #PeppermintNetflix, #TheCrown, #TheCrownNetflix, #TheQueensGambit, #TheQueensGambitNetflix, #Marauders, #AlienWorld, #TheChristmasChronicles, and #TheGrinch. We also looked focused to look at more general tweets to make sure we gathered tweets about the shows beign watched from the platform we are interested in, like #Netflix, #NetflixShows #NetflixOriginals, #NetflixandChill, #QuarantineandChill and analyze if the tweets obtained are positively or negatively related to Netflix.

# Top 10 Netflix Shows and Movies in USA
*Saturday, Dec 5th, 2020:* 

1. Selena
2. Big Mouth
3. Virgin River 
4. Peppermint
5. Marauders 
6. Queens Gambit 
7. The Christmas Chronicles
8. Alien Worlds 
9. The Crown 
10. The Grinch

# Our Research
We started by pulling data from the latest 7 days of Twitter activity. Looking for tweets that mentioned netflix and the top 10 shows on the platform. Following up. we saved the data in CSV files, we needed a backup in case we had a problem.

## Statistical and Predictive Analysis 
For uncovering patterns and trends, make predictions and test our hypothesis, the following statistical and predictive models were used in our analysis:

* Logistic Regresion
* Logistic Model
* CTree
* CART
* Naive Bayes
* Time Series
* ARIMA

# Text Sentiment
- Text and sentiment analysis using Voson package
