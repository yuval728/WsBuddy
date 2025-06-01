# WsBuddy

WsBuddy is a project I built to experiment with WhatsApp automation and AI-powered chat agents. The goal is to create a smart WhatsApp agent that can chat, remember conversations, process images and voice, and even generate content. It uses a combination of AI models, a vector database for memory, and a simple chat interface to provide a seamless user experience. I developed this project using the Neural Maze blogs and videos as a guide, which you can find [here](https://github.com/neural-maze/).

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
     uv venv
     ```
   - Activate it:
     ```
     venv\Scripts\activate
     ```
   - Install dependencies:
     ```
    uv sync
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

- [Yuval Mehta](https://github.com/Yuval728)

---

Feel free to fork, use, or contribute!