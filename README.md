# udacity-data-wrangling-project
Perform data wrangling process for the twitter account @WeRateDogs. Gather, assess and clean the data. Provide two insights on the data.

What is Data Wrangling?
Data Wrangling is the process of gathering, assessing, cleaning and storing data. These steps are intended to make the raw_data functionally fit for data analysis to find hidden insights. These insights
in the data help us make data-oriented decisions. Let us go through these data wrangling steps one by one and find insights in the data.

Data Gathering:
  Raw data is gathered in this step. Data gathering can be done through various
  methods. These methods include:
  1. Downloading data directly via any source
  2. Downloading data programmatically using python packages. For this project I
  used requests library
  3. Accessing data of websites using Application Programming Interfaces(APIs).
  For this project, using tweepy library I accessed @WeRateDogs twitter
  archive2. 
  
Data Assessing:
  Assessing data can be done in two ways: Visually and Programmatically
  1. Visual Assessment:
  Visual assessment is usually done to acquaint oneself with the data.
  We see the data in its entirety and understand the data.
  Understanding each column in the data is very important for further
  assessment.
  2. Programmatic Assessment:
  Using programmatic tools such as pandas,descriptive statistics,
  matplotlib to assess the data. This type of using code to assess the
  raw data is known as programmatic assessment. Using programmatic
  assessment we could try to find the following observations.
    1. If there is any missing data in the data set
    2. Data type of each variable in the data set
    3. Checking for duplicates
    4. Checking for invalid entries
    5. Checking for data consistency, etc
    
Data Cleaning:
  In this step, the observations made in the data assessing step are transformed into
  action items. These action items are then implemented via code to clean the
  raw_data. Data cleaning involves converting observations made in the data
  assessment into pseudocode(define), then coding(code) to clean the code, and then
  testing to check if the particular observation is resolved. At the end of this step, after
  all the observations have been resolved using define>>code>>clean, the resulting
  data is an enriched data functionally fit for further data analysis.

Data Storing:
  This step involves saving the cleaned data as a file, or to a database.
 
I took @WeRateDogs twitter account archive and tried to find some insights. Initially I had
like approximately 2500 tweets which contained only basic information of the tweet_id,
dog_name, dog_stage, rating_numerator, rating_denominator. I followed the above data
wrangling process and came up with a high quality and neat data. The resultant dataset
contained 1946 tweets with additional data such as retweet_count, favorite_count, and
predicted dog_
