# Reply or React

**Reply or React** is an AI-powered assistant that analyzes personal chat messages and helps users decide whether they should reply, react, or leave a message unanswered.

The application uses a Large Language Model (LLM) to understand the message and provide a short, structured recommendation.

## Features

- **Reply** — identifies messages that require a response and briefly suggests what should be addressed.
- **React** — identifies messages where a simple reaction is sufficient.
- **No Reply Needed** — identifies messages that do not require further action.
- **Explanation** — provides a short reason for each recommendation.
- **Single LLM Call** — analyzes each message using only one API request.

## Technologies

- **Python** — application logic
- **Gradio** — web interface
- **Groq API** — access to the language model
- **GPT-OSS 20B** — language model used for message analysis

## How It Works

1. Enter your Groq API key.
2. Paste a message from a personal conversation.
3. Click the Analyze button.
4. Receive a recommendation and a brief explanation.

The application displays only the structured analysis without unnecessary introductions or additional commentary.

## Installation

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/reply-or-react.git
cd reply-or-react
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the application:

```bash
python app.py
```

Open the local Gradio URL in your browser.

## Project Structure

```text
reply-or-react/
├── app.py
├── requirements.txt
└── README.md
```

## Privacy

The application does not require users to connect their messaging accounts. Messages are entered manually and sent to the LLM provider for analysis. Users should avoid submitting sensitive personal information.

API keys are entered through a password-protected input field and are not hardcoded in the application.

## Project Purpose

This project was developed as an educational assignment to demonstrate the integration of a Large Language Model into a web application using a single API call.
