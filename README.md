# ChatBot Using NLP

## Overview

This project implements a **Chatbot** using **Natural Language Processing (NLP)** to interact with users and provide intelligent responses. It utilizes pre-trained **GPT-2** for general conversation and integrates a custom knowledge base (in the form of intents) for specific responses, such as telling jokes. The chatbot is built with **Streamlit** for a user-friendly web interface.

### Features:
- **Chatbot Responses**: Uses **GPT-2** for dynamic conversations and **predefined intents** for specific responses (like jokes).
- **Joke Randomization**: Provides a random joke each time the user asks for one.
- **Conversation History**: Maintains a history of user queries and bot responses.
- **Streamlit Interface**: Easy-to-use web-based interface to chat with the bot.

## Technologies Used

- **Python 3.x**
- **Streamlit**: Web framework to build the UI
- **Hugging Face Transformers (GPT-2)**: For NLP-based responses
- **JSON**: To store predefined intents and responses
- **Datetime**: To display timestamps for each conversation entry

## Prerequisites

Make sure you have the following installed on your machine:
- Python 3.x
- Pip

## Installation
1.Install the necessary dependencies:
```bash
pip install -r requirements.txt
