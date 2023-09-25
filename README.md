

The Miranda Priestly chatbot is an AI-powered fashion recommender system built using Streamlit. It utilizes GLM (added mpt7b model as well) to provide recommendations, information, and engage in fashion-related conversations. The chatbot is designed to assist users with various fashion tasks and topics. 

# ShowGPT

The Miranda Priestly chatbot is an extended part of the fashion recommender system using the ResNet50 model. The recommender system analyzes the visual features of fashion products and provides similar recommendations based on the input image. The ResNet50 model is used for feature extraction, and the Nearest Neighbors algorithm is employed to identify visually similar products.

The code for the fashion recommender system can be found in the ShowGPT GitHub repository (https://github.com/ashes002/ShowGPT). It includes functionalities such as feature extraction, recommendation generation, image display, and product information. The Miranda Priestly chatbot utilizes the fashion recommender system as a component to enhance its fashion-related capabilities.

# Functionalities

- Chat Interface: Users can interact with the chatbot through a text input field where they can enter their queries, fashion-related topics, or tasks.
  
- Fashion Topics: Users can choose from a range of fashion topics, including summer fashion, winter trends, vintage style, street style, workout gear, accessories, sustainable fashion, latest fashion tech, fashion influencers, personal styling tips, and dress codes. These topics help narrow down the conversation and provide more relevant responses.

- Tasks: Users can select a specific task related to fashion, such as coding, summarization, emotion detection, friendship, education, humor, storytelling, translation, writing, fact-checking, advice, forecast, analysis, brainstorming, negotiation, and motivation. Each task corresponds to a specific functionality of the chatbot, enabling it to provide tailored responses.

- AI Model Integration: The chatbot integrates AI models for natural language processing and generation. It utilizes a tokenizer and a pre-trained model to generate responses based on the user input, chosen topic, and task.

- Text-to-Speech Conversion: For most tasks, the chatbot provides responses in text format. However, for tasks like coding, the chatbot formats the response as code. Additionally, for other tasks, the chatbot can convert the response to speech using the gTTS library, allowing users to listen to the generated recommendations or information.

- Chat History: The chatbot keeps track of the conversation history, displaying both user inputs and the chatbot's responses. The chat history allows users to review previous interactions.

Clear Chat: Users have the option to clear the chat history to start a new conversation.
