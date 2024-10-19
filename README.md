# Developing-a-Human-like-Conversational-Chatbot
Developing a Human-like Conversational Chatbot

# Final Project Group 10: Developing a Human-like Conversational Chatbot - USD

# Dataset.
This project is a part of the AAI-520 course in the Applied Artificial Intelligence Program at the University of San Diego (USD). Project Status: [Completed]

# Installation
To use this project, first clone the repo on your device using the below command: git clone [https://github.com/maleal2/Fitness_Tracker_wearable_device_project_Group_1](https://github.com/maleal2/Developing-a-Human-like-Conversational-Chatbot)

# Project Introduction
This project presents the design of a chatbot capable of generating personalized responses based on user prompts. The dataset, Cornell Movie Dialogs Corpus, sourced from Kaggle, includes 220,579 conversational exchanges from 167 movies and 10,292 characters. The dataset was preprocessed in Google Colab, where conversations were tokenized, cleaned, and prepared for model training.
Initially, a Sequence-to-Sequence model using LSTM was implemented. Tokenization, dictionary creation, and sentence padding were applied, with perplexity used to evaluate the model. Although the results were promising, limitations led to the exploration of GPT-2.
GPT-2, a pre-trained generative model, was fine-tuned on the Cornell dataset across three phases. The model's performance improved using hyperparameters like temperature, top_k, and repetition penalty. A web interface was built using Gradio, enabling real-time interaction with the chatbot while maintaining conversation history. The paper concludes with recommendations for fine-tuning and observations on GPT-2's effectiveness.


# Contributors
Maria Leal.

# Methods Used
Long Short Term Memory with Sequal layers.
GPT-2.
Gradio.
Python, Pytorch.

# Project Description
Data source: [https://www.kaggle.com/datasets/arashnic/fitbit ](https://www.kaggle.com/datasets/rajathmc/cornell-moviedialog-corpus)

Name of the variables:

movie_lines.txt
movie_conversations.txt

Number of variables: 2

Size of the dataset: 220,579 
