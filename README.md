# GROUP 1 - Final Project

## Sentiment Analysis on Arts, Crafts and Sewing Dataset from the Amazon Review data - Using Spark
Sentiment analysis studies the subjective information in an expression, that is, the opinions, appraisals, emotions, or attitudes towards a topic, person or entity. Expressions can be classified as positive, negative, or neutral. For example: “I really like the new design of your website!” → Positive.
Here we are doing a sentimental analysis on Amazon reviews meta deta(Arts, Crafts and Sewing Dataset).
In order to perform Sentimental Anlysis here we are going to discuss what are the necessary steps required:

Tool used: Google Coolab
Creating a spark environment in Google Colab and installing pyspark.

# How to run the project

# 1. Run EDA.ipynb. 
There are instructions to set up the spark environment so that you can run Spark using Google Colab's Jupyter Notebook. 

# 2. Run EDA.ipynb. 
It includes all the data preprocessing part of the project. Before performing machine learning models, preprocessing is a necessary step. 

# 3. Run Ml and NLP Sentiment Analysis and Cross Validation
You can perform sentiment analysis on the text and it includes all the machine learning codes. It includes codes to run TF-IDF model, Logistic Regression.

It also include codes to Validate the model and to improve accuracy of the model. 

------------------------------------------------------------------------------------------------------------------------------

1.) Doing an Exploratory Data Analysis where we have performed several tasks like:
      - Extracting data into colab, reading the data and understanding the basic information like columns, datatypes, finding         null values
      Three steps we used in EDA are:
     
      a.) Graphical Representation of column overall rating
      
      b.) Getting the most common words 
     
      c.) Categorizing the length of review



2.) Data Processing : For us to perform sentiment analysis we have to concentrate on the Reviewtext column where all the positive and negative feedbacks are given. In order to process this we have to first uderstand whether data has null values or not, puctuation and removing special characters. Tasks involved
      
      a.) Removing punctations.
      
      b.) Lowercasing words
      
      c.) Removing stopwords

3.) Machine Learning
In this part, we created  X and y matrices and apply some algorihms to do NLP tasks.
In order to do that,we created TF-IDF matrix.
Then trained a basic Logistic Regression Model for Prediction
Last step was to create pipeline.


4.) Validation
Validation is the part you run some sort of testing code to test your validity of your machine learning model.
In the step the trained model and pipeline was tested on data that the model we created in the machine level step.


5.) Testing
At the final part,we used our model to output some results. We performed the sentimental analysis.We tried traning and testing the reviews at the end
