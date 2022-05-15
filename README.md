# Abdul_Portfolio
The repository in charge of my website portfolio.

# [Project 1: E-Commerce ChatBot](https://github.com/akhalifaa/EcommerceChatBot)
## Project Overview:
* Created an Ecommerce style Chatbot that interacts with customers inquiring about things like **products, delivery times, and payment methods**
* Built a Json intents file containing various **tags, patterns and responses strings** that I tailored to an Ecommerce environment and used to train and test my model.
* Trained my Chatbot model with a feed forward neural network containing linear input, hidden and output layer with ReLU activation in between layers and a softmax activation for classification.

| Layer Name & Type | In_Features | Out_Features |
| :---              |:---:        |          ---:|
| l1 linear (input)         | 52          | 8            |
| l2 linear (hidden) | 8 | 8 | 
| l3 linear (output) | 8       | 6|

* Observed metrics such as training loss, accuracy score and f1 score of the model after training.
