# VoiceMate

## Overview
VoiceMate is a simple conversational AI bot that allows users to have a voice chat with a GPT-like model. The bot listens to user input, processes it, and generates a response. It is designed to be easy to set up and extend, making it a great starting point for building more advanced conversational AI projects.

## Project Description

### What is VoiceMate?
VoiceMate is an interactive voice bot that simulates a conversational partner using natural language processing. It is built to understand user input and respond appropriately, making it useful for applications such as virtual assistants, customer service bots, or personal chat companions.

### How Can One Use VoiceMate?
VoiceMate can be used to simulate a conversation with a GPT-like model. It can be integrated into various platforms where voice interaction is needed. Users can simply speak or type their input, and the bot will generate responses in real-time. The project can be customized to include more advanced NLP techniques or integrated with external APIs to enhance its conversational capabilities.

## Project Structure
voicemate/
├── .env
├── main.py
├── prompt.py
├── requirements.txt
├── .gitignore
└── README.md
- `.env`: This file contains environment variables such as API keys.
- `main.py`: This is the main script that runs the bot.
- `prompt.py`: This script handles the logic for generating responses.
- `requirements.txt`: This file lists the Python dependencies for the project.
- `.gitignore`: This file specifies which files and directories to ignore in the repository.
- `README.md`: This file provides instructions on how to set up and run the project.



## Setup

1. Clone the repository to your local machine.
    ```bash
    git clone https://github.com/Animeshkr9044/voicemate.git
    cd voicemate
    ```

2. Create a virtual environment and activate it.
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3. Install the required dependencies.
    ```bash
    pip install -r requirements.txt
    ```

4. Create a `.env` file and add your API key or other environment variables.
    ```bash
    echo "API_KEY=your_api_key_here" > .env
    ```

## Usage

1. Run the main script.
    ```bash
    python main.py
    ```

2. Start a conversation with VoiceMate by typing your input and pressing Enter. Type `exit` or `quit` to end the conversation.

## Example

```plaintext
$ python main.py
Starting voice bot...
You: Hello
Bot: Received: Hello
You: How are you?
Bot: Received: How are you?
You: exit
Ending conversation.
