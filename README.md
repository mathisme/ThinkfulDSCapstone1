# Experimental Design Capstone: Do free ad-enabled apps get lower ratings than paid apps?
This is my capstone project on experimental design for Thinkful’s Data Science Flex program. For this capstone we were to complete a buisness research project.
Steps involved
* Write a research proposal
* Run a hypothesis test, analyze and write up results
* Create a power point presentation

## Included in this repository
* The research proposal, https://github.com/mathisme/ThinkfulDSCapstone1/blob/main/Thinkful%20Research%20Proposal.pdf
* Jupyter notebook containing the results, https://github.com/mathisme/ThinkfulDSCapstone1/blob/main/Results.ipynb
* PowerPoint presentation, https://github.com/mathisme/ThinkfulDSCapstone1/blob/main/ThinkfulDSCap1.pptx

## Background
As someone who uses apps and gets annoyed by all the advertisements popping up in free apps, I was curious to see if free ad-enabled apps get lower ratings on average than paid apps without ads.
To examine thiis, I chose the Google Play Store Apps dataset found on Kaggle.  The dataset can be found here: https://www.kaggle.com/gauthamp10/google-playstore-apps
Although this is not for any buisness purpose, developers can see from my research that having ads does not significantly effect user ratings.  

## Steps
* An exploratory data analysis was performed on the data
* As a t-test was intended the ratings column needed to be transformed to make it more normal
* A/A testing was used to test for bias
* A one sided t-test was performed and results analyzed
* To derive a confidence interval on the non-transformed 'ratings' column, bootstrapping was utilized

## Tools Used
* Numpy
* Pandas
* Scipy
* Matplotlib

## To do in the future
Find data on user reviews and see if ads effect review sentiment
