## Date created
Project uploaded on 26/07/2019

# Insights from WeRateDogs: Wrangle and Analyze Twitter Data

### Gathering Data

First, I gathered the data from three different sources and in three different formats.
The first piece was a Twitter archive given. I downloaded twitter-archive-enhanced.csv from the link and uploaded it to the Jupyter Notebook workspace.
The second piece of data was a collection of image predictions. I downloaded image_predictions using the Requests library and URL given.
The third piece of data was Twitter additional data extracted through an API. Using the tweet IDs in the WeRateDogs Twitter archive, I queried the Twitter API for each tweet's JSON data using Python's Tweepy library and stored each tweet's entire set of JSON data in a file called tweet_json.txt file. 

### Assessing Data

Then, I assessed the data: inspecting the data (visually or programmatically) and documenting issues I encountered.
First, I did a visual assessment. Each piece of gathered data was displayed in the Jupyter Notebook and then in an external application (Excel).
Secondly, I did a programmatic assessment using pandas' functions and/or methods.
I documented 8 quality issues and 2 tidiness issues.

### Cleaning Data

The next step was to clean all issues identified in the assess phase using Python and pandas.
Finally, to complete the wrangling process I created a tidy and clean master dataset with all pieces of
gathered data. This dataset will be used in the following analysis process.

### Extracting Insights from the Clean Dataset

Finally, I used the clean dataset to extract insights from it and answered three questions:
* What is the distribution of ratings?
* Which breed is associated with the highest/lowest number of likes on average?
* What is the average number of retweets for each dog stage?

**Includes all datasets in the folder and the code in the Jupyter Notebook**

## Software requirements
You should have Python3, pandas, matplotlib and Jupyter Notebooks.

## Credits
Thanks to the Udacity team for this great project which is part of the Data Analyst Nanodegree Program!

