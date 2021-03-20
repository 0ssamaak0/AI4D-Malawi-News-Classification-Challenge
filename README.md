# AI4D-Malawi-News-Classification-Challenge
## This is a Contribution to Zindi Competition: AI4D Malawi News Classification Challenge

### The goal of the comptetition is to classify news articles into 19 classes.

# Steps
### After the typical steps of importing the libraries and reading the trainging data set, we checked of the articles was euqally divided according to the label. but it wasn't
- so we decided the whole program must consider percentages, not absolute numbers
### To remove the useless common words: Pronous, prepositions and etc we started to check the occurance percentages of the words
- visually: using Wordcloud for each label
- analytically by finding the words that occurs the most in the whole text of all articles.
###
Removing the uneeded words from the Dataframe, we have a relativly unique text contents
### Then we made a dictionary that contains the most occured words in each Label and their frequency of occurance.
### we will multiply the percentage of occurance of the word in each testing data by the the percentage of occurance of the same word in a certain label in order to find a weighted score.
### for example: the word lorem has a percentage of occurance of 0.3% in a test sample. and it has a percentage of occurance of 0.25% in Label A,
### Label A gets a score of 0.3 . 0.25 = 0.075*

This Submission scored 0.4032 with rank 123 of 150 [https://zindi.africa/users/0ssamaak0/competitions/certificate]
