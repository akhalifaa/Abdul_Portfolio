# Abdul_Portfolio
The repository in charge of my website portfolio.

# [Project 1: E-Commerce ChatBot](https://github.com/akhalifaa/EcommerceChatBot) 🤖
## Project Overview:
* Created an Ecommerce style Chatbot that interacts with customers inquiring about things like **products, delivery times, and payment methods**
* Built a Json intents file containing various **tags, patterns and responses strings** that I tailored to an Ecommerce environment and used to train and test my model.
* Trained my Chatbot model with a feed forward neural network containing linear input, hidden and output layer with ReLU activation in between layers and a softmax activation for classification.
* Observed metrics such as training loss, accuracy score and f1 score of the model after training.

| Layer Name & Type | In_Features | Out_Features |
| :---              |:---:        |          ---:|
| l1 linear (input)         | 52          | 8            |
| l2 linear (hidden) | 8 | 8 | 
| l3 linear (output) | 8       | 6|

*A tabular visualisation of the in and out features along with the neural network structure.*

![](images/Convo.png)

*A sample convo with the Bot, notice how the bot was asked twice about the products they sell in different ways and was responsive!* 

# [Project 2: Canada Housing Market, An Exploratory Analysis](https://github.com/akhalifaa/CanadaHousing)
## Project Overview:
* An exploratory analysis of the Canadian Housing Market, observed features such as number of households, household income, value and more.
* Utilized multiple data visualisation techniques to portray insights and explain how the different columns in the data frame correlate.
* Split up the data for training and testing, fit the data on 3 different regression models: Linear, Ridge and SVR and observed the root mean squared error of each model result.

# [Project 3: Concrete Crack Detection](https://github.com/akhalifaa/Concrete-Crack-Detection)
## Project Overview:
* Downloaded a large [data set](https://www.kaggle.com/datasets/arunrk7/surface-crack-detection) of cracked and non-cracked concrete images from Kaggle and trained a model to detect cracks on a test set of similar concrete specimens.
* Created a four layer convoluted neural network model with ReLU activation and maxpooling in between layers and a sigmoid activation for clsssification. I implemented the model with a (3,3) kernel size and a (2,2) pooling size.
* Observed some metrics for the model after training it and looked at the accuracy, training loss and the cofusion matrix after testing the model on the testing set. The model accuracy came to be 98.61%.

![](images/00001.jpg)

*Cracked Concrete Specimen that the model classifies as 1 or Cracked*

![](images/download.png)

*Confusion Matrix Representing the Accuracy of the model on the test data*


