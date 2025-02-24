# Building Chatbots
Chatbots automate a majority of the customer service process,  single-handedly reducing the customer service workload. They utilize a variety of techniques backed by artificial intelligence, machine learning and data science.

Chatbots analyze customer inputs and reply with an appropriate mapped response. To train the chatbot, you can use recurrent neural networks with the intents JSON dataset, while the implementation can be handled using Python. Whether you want your chatbot to be domain-specific or open-domain depends on its purpose. As these chatbots process more interactions, their intelligence and accuracy also increase.
This is a learning project in python. Due to large files in library, github could not be uploaded it

Technology Used:
1. Python3
2. Thinker
3. Keras
4. NLTK (NLP)

Project File Structure:
After the project is complete, you will be left with all these files. Lets quickly go through each of them. It will give you an idea of how the project will be implemented.

1. Train_chatbot.py — In this file, we will build and train the deep learning model that can classify and identify what the user is asking to the bot.
2. Gui_Chatbot.py — This file is where we will build a graphical user interface to chat with our trained chatbot.
3. Intents.json — The intents file has all the data that we will use to train the model. It contains a collection of tags with their corresponding patterns and responses.
4. Chatbot_model.h5 — This is a hierarchical data format file in which we have stored the weights and the architecture of our trained model.
5. Classes.pkl — The pickle file can be used to store all the tag names to classify when we are predicting the message.
6. Words.pkl — The words.pkl pickle file contains all the unique words that are the vocabulary of our model.

Running the Chatbot
we have two separate files, one is the train_chatbot.py, which we will use first to train the model.
python train_chatbot.py

Referance:
1. https://dzone.com/articles/python-chatbot-project-build-your-first-python-pro
