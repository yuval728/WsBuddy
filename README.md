# WsBuddy

WsBuddy is a personal project I built to experiment with WhatsApp automation and AI-powered chat agents. The goal is to create a smart WhatsApp agent that can chat, remember conversations, process images and voice, and even generate content.

## Features

- Send and receive WhatsApp messages automatically
- Integrate AI models for smart, context-aware replies
- Store and recall chat history using a vector database (Qdrant)
- Voice-to-text and text-to-voice support
- Image recognition and generation
- Simple deployment to the cloud

## Getting Started

1. **Clone the repository:**
   ```
   git clone https://github.com/Yuval728/WsBuddy.git
   cd WsBuddy
   ```

2. **Set up your environment:**
   - Create a virtual environment:
     ```
     python -m venv venv
     ```
   - Activate it:
     ```
     venv\Scripts\activate
     ```
   - Install dependencies:
     ```
     pip install -r requirements.txt
     ```

3. **Configure environment variables:**
   - Copy `.env.example` to `.env` and fill in your API keys and settings.

4. **Run the app:**
   ```
   python main.py
   ```

## Tech Stack

- **Python** for the backend logic
- **Qdrant** for long-term memory and vector search
- **Groq/OpenAI/Whisper** for AI chat, vision, and voice
- **Chainlit** for the chat interface
- **Google Cloud Run** for deployment


## License

MIT License

## Author

- [Your Name](https://github.com/Yuval728)

---

Feel free to fork, use, or contribute!