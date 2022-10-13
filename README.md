# Abdul Khalifa's Portfolio
----
# [Project 1: Finance](https://github.com/akhalifaa/Finance) :moneybag: :dollar:
## Project Overview:
### For this project, I used Flask to develop a web application that simulates a financial stock portfolio/exchange platform that you can buy and sell stocks from. I built up the process of regestering on the platform, buying and selling stocks, viewing your portfolio and viewing your complete history of exchange activity. This project was all about learning and exploring Flask, which is a backend framework running with Python. It was a fantastic learning opportunity to understand what happens underneath the hood of many web applications. Flask's main file distribution comrise of a conroller app.py file, templates folder for HTML files, styles folder for CSS and a database of some sort.

In order to access real time stock valuation data, I utilized IEX's API platform which gives you stock quotes, names etc...

For my database, I used a Sqlite3 to implement CRUD activities, store and manage user data.

In order to run this web application, you must create an account with IEX to obtain a unique token key. Once you obtain that, run export API_KEY= (token key) in the terminal, at the directory where your storing all your files. 

Here are sample images from the web applications.
### The Index Page
![alt text](images/img1.png)

### The Sell Page
![alt text](images/img2.png)

# [Project 2: E-Commerce ChatBot](https://github.com/akhalifaa/EcommerceChatBot) 🤖
## Project Overview:
#### Libraries Used: NLTK, Numpy, Pytorch, Sci-kit Learn, and Matplotlib.
* Created an Ecommerce style Chatbot that interacts with customers inquiring about things like **products, delivery times, and payment methods**
* Built a Json intents file containing various **tags, patterns and responses strings** that I tailored to an Ecommerce environment and used to train and test my model.
* Utilized the NLTK toolkit to pre-process strings from the JSON file.
* Trained my Chatbot model with a feedforward neural network using Pytorch containing linear input, hidden and output layer with ReLU activation in between layers and a softmax activation for classification.
* Observed metrics such as training loss, accuracy score and f1 score of the model after training.

| Layer Name & Type | In_Features | Out_Features |
| :---              |:---:        |          ---:|
| l1 linear (input)         | 52          | 8            |
| l2 linear (hidden) | 8 | 8 | 
| l3 linear (output) | 8       | 6|

*A tabular visualisation of the in and out features along with the neural network structure.*

![](images/Convo.png)

*A sample convo with the Bot, notice how the bot was asked twice about the products they sell in different ways and was responsive!* 

# [Project 3: Loan Repayment Neural Network Classifier](https://github.com/akhalifaa/LoanRepayment) 💰
## Project Overview:
#### Libraries Used: Pandas, Numpy,Tensorflow/Keras, Sci-Kit Learn, Seaborn, Matbplotlib.
* A comprehensive project involving heavy feature engineering to create a NN model that classifies whether an individual will repay a loan or not.
* Analyzed plenty of features such as total credit accounts, job title, loan grade, mortgage accounts and many more in order to prepare the data for training.
* Feature engineering involved looking at categorical features and their correlations to numerical features in order to transform them into trainable data.
* Utilized dummy features, mapping and function applying to certain features in order to transform them into trainable data.
* Created a fully connected Neural Network using Keras that took in 78 features, involved two hidden layers and an output layer that classifies whether a certain individual would repay their loan or not.
* Evaluate model metrics: achieved a good model training and validating loss and classification report/confusion matrix convey 90% accuracy. This can be much improved if we use the full data set and increase training epochs.


![](images/heatmap.png)

*Heat map of all the features in order to initialize the feature engineering process*


# [Project 4: Advertisement Classifier, Did they Click or Not?](https://github.com/akhalifaa/AdvertisementClassifier) 📱
## Project Overview:
#### Libraries Used: Pandas, Numpy, Sci-Kit Learn, Seaborn, Matbplotlib.
 * A mini-machine learning project involving the creation of a logistic regression model that predicts whether a user clicks on an internet advertisement or not.
 * The data set contained information about users such as their daily time spent on the internet, age, area income, country and more...
 * This project involved exploring and cleaning data via various data visualization techniques, creating and training a logistic regression model and evalating its classification metrics. More importantly, as a part of creating the training data set, I implemented my take on feature engineering by adjusting the raw data set to include string and non-numerical data so that we could include more features and have a better trained model. I implemented functions such as splitting timestamps and assigning them to new columns and creating dummy variables for a the "Country" column where there was a selection of around 290 different countries.
 * Achieved a testing accuracy of 97%.

![](images/pairplot.png)

*A pairplot of all our columns with a Hue of whether the Ad was clicked on or not*

![](images/Confusion%20Matrix.png)

*Confusion Matrix Portraying the Testing Results*

# [Project 5: Canada Housing Market, A Regression Analysis](https://github.com/akhalifaa/CanadaHousing) 🏠
## Project Overview:
#### Libraries Used: Pandas, Numpy.
* An exploratory analysis of the Canadian Housing Market, observed features such as number of households, household income, value and more. This project portrays the process of executing a machine learning project that involves data exploration, cleaning, feature engineering, creating and training a model and evaluating results.
* Utilized multiple data visualisation techniques to portray insights and explain how the different columns in the data frame correlate.
* Split up the data for training and testing, fit the data on 3 different regression models: Linear, Ridge and SVR and observed the root mean squared error of each model result.

![](images/histo.png)

*A method of holistically checking out the correlation between different columns in our data*

![](images/Residual.png)

*A Plot of the Residuals of the Linear Regression Model Results*


# [Project 6: Concrete Crack Detection](https://github.com/akhalifaa/Concrete-Crack-Detection) 🏗️
## Project Overview:
#### Libraries Used: Pandas, Numpy, Seaborn, matplotlib, Tensorflow/keras, cv2.
* Downloaded a large [data set](https://www.kaggle.com/datasets/arunrk7/surface-crack-detection) of cracked and non-cracked concrete images from Kaggle and trained a model to detect cracks on a test set of similar concrete specimens.
* Created a four layer convoluted neural network model with ReLU activation and maxpooling in between layers and a sigmoid activation for clsssification. I implemented the model with a (3,3) kernel size and a (2,2) pooling size.
* Observed some metrics for the model after training it and looked at the accuracy, training loss and the cofusion matrix after testing the model on the testing set. The model accuracy came to be 98.61%.

![](images/00001.jpg)

*Cracked Concrete Specimen that the model classifies as 1 or Cracked*

![](images/download.png)

*Confusion Matrix Representing the Accuracy of the model on the test data*

# [Cool Task 1: DNAandSoccerTournament]() ⚽ 
## Task Overview:
This repository contains two separate cool tasks I did with Python that have interesting applications:
1) Tournament.py is a script that simulates the famous soccer FIFA World Cup to come up the percent chance of a participating country to win based on past World Cup stats and winning streaks that give each country a rating. Along with it are the [2018m](https://github.com/akhalifaa/DNAandSoccerTournament/blob/main/2018m.csv) and [2019w](https://github.com/akhalifaa/DNAandSoccerTournament/blob/main/2019w.csv) that have the men's and women's soccer World Cup team ratings respectively.

2) DNA.py is a script that reads [DNA sequences](https://github.com/akhalifaa/DNAandSoccerTournament/tree/main/sequences) and searches a [DNA database](https://github.com/akhalifaa/DNAandSoccerTournament/tree/main/databases) to match that sequence to an individual. This concept has applications in crime detection and is actually used to investigate crimes.

# [Cool Task 2: Shopify Data Science Challenge 2022](https://github.com/akhalifaa/ShopifyDSChallenge2022) 🛒
## Task Overview:
* My work, thought process and solutions to Shopify's 2022 Data Science Technical challenge. 

**Question 1**: Given some sample data, write a program to answer the following: click here to access the required data set

On Shopify, we have exactly 100 sneaker shops, and each of these shops sells only one model of shoe. We want to do some analysis of the average order value (AOV). When we look at orders data over a 30 day window, we naively calculate an AOV of $3145.13. Given that we know these shops are selling sneakers, a relatively affordable item, something seems wrong with our analysis. 

Think about what could be going wrong with our calculation. Think about a better way to evaluate this data. 
What metric would you report for this dataset?
What is its value?

**Question 2**: For this question you’ll need to use SQL. Follow this link to access the data set required for the challenge. Please use queries to answer the following questions. Paste your queries along with your final numerical answers below.

How many orders were shipped by Speedy Express in total?

What is the last name of the employee with the most orders?

What product was ordered the most by customers in Germany?

# [Cool Task 3: MysterySolverSQL](https://github.com/akhalifaa/MysterySolverSQL) 🕵️
## Task Overview:
* The problem given was that a theft occured on a certain date and street name that were provided to me. Given was a database file with 10 tables of varying columns related to the different aspects of the crime.
* For example, some of the tables given were: suspect interviews, flights out of the city, ATM transactions, security footage and more...
* The goal was to strategically navigate all the tables and join them in order to figure out the thief, accomplice and city of escape.
* The way I tackled this task was through a series of queries as seen in my log.sql file, all queries are titled with a common and are run one query at a time. Query by query I was able to determine the relevant columns to look at and narrow down the data to obtain the solution. Every q.text file has the result of my subsequent queries.

# [Cool Task 4: Tweet Sentiment Analysis](https://github.com/akhalifaa/CanadaHousingTweets) 😄 😞
## Task Overview:
* A simple task/project that portrays a sentiment analysis technique I used to classify Tweets regarding the Housing market in Canada.
* Created a vectorizer based on the Tweets in order to map out all the words to corresponding unique vectors of real numbers.
* Created a predictive Multinomial Naive Bayes Classifier model to classify the Tweets as positive or negative.
