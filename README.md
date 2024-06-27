## Chatbots are essential for businesses, efficiently managing customer queries using Artificial Intelligence, Machine Learning, and Data Science. 
## They utilize Recurrent Neural Networks with JSON datasets for training in Python. The choice between specific domain or open domain depends on the chatbot's purpose, enhancing its intelligence and accuracy with each interaction. 

## As these chatbots interact more with users, their intelligence and accuracy improve, thanks to their ability to learn from past interactions.

### In this case, it is a simple ChatBot that is easy to build and understand its operation. It will consist of the following files:

## Train_chatbot.py
In this file, we will build and train the deep learning model that can classify and identify what the user is asking to the bot.

## Gui_Chatbot.py
This file is where we will build a graphical user interface to chat with our trained chatbot.

## Intents.json
The intents file has all the data that we will use to train the model. It contains a collection of tags with their corresponding patterns and responses.

## Chatbot_model.h5
This is a hierarchical data format file in which we have stored the weights and the architecture of our trained model.

## Classes.pkl
The pickle file can be used to store all the tag names to classify when we are predicting the message.

## Words.pkl
The words.pkl pickle file contains all the unique words that are the vocabulary of our model.

Execute first "python3 train_chatbot.py" for training the model and "python3 gui_chatbot.py" for init the chatbot.

