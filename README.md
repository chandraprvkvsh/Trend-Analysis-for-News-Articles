# Historical-News-Analysis
# Brief Introduction

Objective of this project is to utilize the news articles dataset containing the entire corpus of articles published over a decade and highlight the important episodes shaping the last decade and how they evolved over time. 
This project involved data cleaning, Vectorizing the dataset, Creating the required report.

NLTK, Scikit-Learn,mglearn libraries were used.
CountVectorizer, Latent Dirichlet allocation algorithms were used.

# Details of the project

Domain – News
Focus – Important episodes in over a decade [2003-2017]
 
Business challenge
 
News articles dataset includes the entire corpus of articles published by the ABC website in the given time range. With a volume of 200 articles per day and a good focus on international news, we can be certain that every event of significance has been captured here.

Requirement

You as an NLP expert, delve into the keywords and highlight the important episodes shaping the last decade and how they evolved over time. 

1.      Load the dataset and create a dataframe.
2.      Check the hygiene of data and sanitize it.
3.      Create DTM using following parameters:
a.      CountVectorizer(max_df=0.95, min_df=2,max_features=1000,ngram_range = (1,2),stop_words='english')
4.      Fit  LDA model with 5 components.
5.      Create a report

Where LDA is the model created.
Vect is the vector created using CountVectorizer.

Key issues
1)    publish_date: Date of publishing for the article in yyyyMMdd format
2)    headline_text: Text of the headline in ASCII English, lowercase

Considerations
News articles have been saved as elements of the CSV file.

Data volume
1103663

Business benefits
This exercise will embolden the historical record of noteworthy events between 2003 and 2017.  
