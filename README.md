# Groq_Streamlit_Demo-App
Build a Streamlit AI chatbot using Groq, the fastest LLM inference API. We will review the code for building the app to include a menu option to select the model type and a slider to choose the tokens.
# Groq Chat Streamlit App:

## Features

**Model Selection**: Users can select between `mixtral-8x7b-32768`, `llama2-70b-4096`, `Gemma-7b-it`, `llama2-70b-4096`, `llama3-70b-8192`, and `lama3-8b-8192` models to tailor the conversation according to each model's capabilities.
- **Chat History**: The app maintains a session-based chat history, allowing for a continuous conversation flow during the app session.
- **Dynamic Response Generation**: Utilizes a generator function to stream responses from the Groq API, providing a seamless chat experience.
- **Error Handling**: Implements try-except blocks to handle potential errors gracefully during API calls.

## Requirements

- Streamlight
- Groq Python SDK
- Python 3.7+

## Setup and Installation

- **Install Dependencies**:

  ```bash
  pip install streamlet grow
  ```

- **Set Up Groq API Key**:

  Could you make sure you have an API key from Groq? This key should be stored securely using Streamlet's secrets management:

  ``` tool
  # .streamlit/secrets.tool
  GROQ_API_KEY="your_api_key_here"
  ```

- **Run the App**:
  Navigate to the app's directory and run:

```CMD
Streamlight run streamlit_app.py

## Usage

Upon launching the app, you are greeted with a title and a model selection dropdown.

After choosing a preferred model, you can interact with the chat interface by entering prompts.

The app displays the user's questions and the AI's responses, facilitating a back-and-forth conversation.

## Customization

The app can be easily customized to include additional language models (as Groq adds more), alter the user interface, or extend the functionality to incorporate other interactions with the Groq API.

## Contributing

Contributions are welcome to enhance the app, fix bugs, or improve documentation.

Please feel free to fork the repository, make changes, and submit a pull request.
