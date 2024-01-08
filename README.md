# OpenAI Assistant API Project

This project integrates the OpenAI Assistant API with Streamlit to create an interactive web application.

## Setup Instructions

### 1. Create Secret Configuration
- Create a `.streamlit` folder in the root directory of your project.
- Inside this folder, create a file named `secrets.toml`.
- Add your OpenAI API key and Assistant ID to this file:
  ```toml
  openai_apikey = "your_openai_api_key"
  assistant_id = "your_assistant_id"

### 2. Install Dependencies
- Install the OpenAI Python package:
- pip3 install --upgrade openai

- Install Streamlit:
- pip3 install streamlit

### 3. Run the Application
- Start the Streamlit web application:
- streamlit run app.py

### Getting the Assistant ID
- You can obtain the Assistant ID from the OpenAI Playground.
- Create an agent in the OpenAI Playground by uploading files (PDF, TXT, etc.) and defining starting prompts.
- The Assistant ID is used to uniquely identify your custom model.
