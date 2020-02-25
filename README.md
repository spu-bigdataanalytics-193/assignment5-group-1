# GROUP 1 - Final Project

## Sentiment Analysis on Arts, Crafts and Sewing Dataset from the Amazon Review data - Using Spark
Sentiment analysis studies the subjective information in an expression, that is, the opinions, appraisals, emotions, or attitudes towards a topic, person or entity. Expressions can be classified as positive, negative, or neutral. For example: “I really like the new design of your website!” → Positive.
Here we are doing a sentimental analysis on Amazon reviews meta deta(Arts, Crafts and Sewing Dataset).
In order to perform Sentimental Anlysis here we are going to discuss what are the necessary steps required:

Tool used: Google Coolab

1.) Creating a spark environment in Google Colab and installing pyspark.

2.) Doing an Exploratory Data Analysis where we have performed several tasks like:
      - Extracting data into colab, reading the data and understanding the basic information like columns, datatypes, finding         null values
      Three steps we used in EDA are:
     
      a.) Graphical Representation of column overall rating
      
      b.) Getting the most common words 
     
      c.) Categorizing the length of review

3.) Data Processing : For us to perform sentiment analysis we have to concentrate on the Reviewtext column where all the positive and negative feedbacks are given. In order to process this we have to first uderstand whether data has null values or not, puctuation and removing special characters. Tasks involved
      
      a.) Removing punctations.
      
      b.) Lowercasing words
      
      c.) Removing stopwords
     
