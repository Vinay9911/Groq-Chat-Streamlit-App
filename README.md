# Groq Chat Streamlit Application 🚀
![Screenshot 2024-09-23 013021](https://github.com/user-attachments/assets/f815759f-c6ab-4f5e-adbc-ef280c5053d3)


This Streamlit application leverages the Groq API to create an interactive chat interface that enables users to engage with sophisticated language models. Users can select from various models to customize their experience, enhancing the versatility of the chat application. 


## Features 🌟

- **Model Selection**: Choose from the following models to tailor your conversation based on each model’s strengths:
  - mixtral-8x7b-32768
  - llama-3.1-8b-instant
  - Gemma-7b-it
  - llama3-70b-8192

- **Chat History**: The app maintains a session-based chat history, allowing for a seamless conversation throughout the session. 📜
- **Dynamic Response Generation**: A generator function is used to stream responses from the Groq API, ensuring a fluid chat experience. 🔄
- **Error Handling**: Incorporates try-except blocks to manage any potential errors that may arise during API interactions. ⚠️

## Requirements 📋

- Streamlit
- Groq
- Python 3.7+

## Setup and Installation ⚙️

### Install Dependencies:

```bash
pip install streamlit groq
```

### Configure Groq API Key:

Obtain an API key from Groq and securely store it using Streamlit's secrets management:

```toml
# .streamlit/secrets.toml
GROQ_API_KEY="your_api_key_here"
```

### Launch the App:

Navigate to the app’s directory and execute:

```bash
streamlit run Groq-LLMs-Chat.py
```

## Usage 💬

When you start the app, you'll see a title and a dropdown for model selection. After choosing your desired model, you can engage with the chat interface by entering prompts. The app will show both your questions and the AI's responses, allowing for an interactive conversation.

## Customization 🛠️

The app is easily customizable to add new language models (as Groq introduces them), modify the user interface, or extend functionality for additional interactions with the Groq API.

## Contributing 🤝

Contributions to enhance the application, fix bugs, or improve documentation are welcome. Feel free to fork the repository, make your modifications, and submit a pull request.
