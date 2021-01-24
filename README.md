# Twitter-NLP-Analysis
This project uses GCP and Pyspark to analyze four universities tweets data. In nowadays world, social media takes an important role in nowadays’ social life. Twitter is the one of the most influential social medias all over the world.  Many universities use Twitter to interact with their stakeholders and to promote school brand. By analyzing university tweets data, we could gain more insights on university tweets' users and their concerns. 

Original data has 300M records (2TB+). This project has selected University of Chicago, Northeastern University, University of Nebraska-Lincoln, and Brown University as subset data to compare twitterers’ difference and tweet content difference. Lastly, based on the analysis, we can offer recommendations for universities to improve their twitter account management.


## The Finalversion file includes questions following: 

1. Identify tweets related to UChicago, Brown University, Northeast University, and university of Nebraska.
2. Complete thorough EDA to identify which variables you can use to profile the Twitterers
3. Identify the most prolific / influential Twitterers
    By message volume
    By message retweet
4. How much are they tweeting about the Universities vs. other topics?
5. Where are these Twitterers located?
    For UChicago
    For other universities
6. Do you see any relationship between university locations and Twitterers’ locations?
    Visualize the relationships
7. What distinguishes University of Chicago Twitterers vs Twitterers who tweet about other universities
    Visualize the trends
8. What are the timelines of these tweets? Do you see significant peaks and valleys?
9. Do you see data collection gaps?
10. How unique are the messages for each of these universities?
    Are they mostly unique? Or mostly people are just copy-pasting the same text?

## The LDA file includes LDA topic modeling in pyspark
## The MinhashLSH File uses MinhashLSH to evaluate university tweets' uniqueness VS near-duplicates. 

