GeminiChainlit-Agent

GeminiChainlit-Agent is an intelligent conversational AI agent that integrates Google Gemini with Chainlit to create a responsive, session-aware chatbot experience.



🚀 Features

🔑 Loads environment variables securely

✅ Checks for required GEMINI_API_KEY

🧠 Connects to Gemini API via OpenAI-compatible interface

🔂 Stores and manages user sessions

💬 Handles incoming messages and returns streamed responses

🧵 Maintains chat history and context during the session

🥉 Flow Overview

Load environment variables

Validate API Key

Start chat with @cl.on_chat_start

Create Gemini external client

Initialize and configure model

Store session data (history, config, agent)

Send welcome message

Handle user input with @cl.on_message

Stream AI response and update chat history

📁 Project Structure

GeminiChainlit-Agent/
├── agents/
│   └── run.py
├── .env
├── main.py
├── requirements.txt
└── README.md

⚙️ Setup Instructions

Clone the repository

git clone https://github.com/yourusername/GeminiChainlit-Agent.git
cd GeminiChainlit-Agent

Install dependencies

pip install -r requirements.txt

Create .env file and add your Gemini API key

GEMINI_API_KEY=your_gemini_api_key_here

Run the app

chainlit run main.py

📚 Reference

Google Gemini API (OpenAI Compatible)

Chainlit Documentation

🧠 Credits

Built using:

Chainlit

Google Gemini
