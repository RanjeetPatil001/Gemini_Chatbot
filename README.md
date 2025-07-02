# Gemini_Chatbot

Chat with Google Gemini-Pro!

This project integrates a chatbot built using Streamlit and Google's Gemini-Pro model, allowing users to interact with an AI assistant directly from a web interface.

The code enables conversational AI features with a simple and user-friendly interface.

Features
Streamlit Integration: Provides a clean and interactive UI.

Google Gemini-Pro Integration: Uses Google’s Gemini-Pro model for generating AI responses.

Chat History: Displays past interactions for context.

Prerequisites

Python 3.7+

Streamlit: To install Streamlit, run:

pip install streamlit

Google Gemini AI SDK: Install the required SDK with:

pip install google-generativeai

How to Use

Clone the repository or copy the code into your local project.

Set up your API key:
api_key = "YOUR_API_KEY"

Run the app locally:
streamlit run <your-app_name>.py

Open the Streamlit app in your browser.

Code Overview

Initialization: The Google Gemini-Pro API is configured with your API key.

Streamlit UI: Chat history is displayed, and users can input their queries.

AI Interaction: User input is sent to Google Gemini-Pro, and responses are displayed in the chat interface.
