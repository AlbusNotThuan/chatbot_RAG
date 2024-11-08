# Music Theory AI Assistant

An AI-powered assistant for music theory, piano playing, and music production using LangChain and ChromaDB.

## Features

- Music theory explanations
- Piano practice guidance
- Music production advice
- Conversation persistence
- Document retrieval
- Streaming responses

## Setup

1. Clone repository
2. Create virtual environment:

```
   python -m venv .venv
   .venv\Scripts\activate
```

3. Install dependencies:

```
pip install -r requirements.txt
```

4. Create .env file with OpenAI API key:

```
   OPENAI_API_KEY=your_key_here
```

## Usage

Run `chainlit run app.py` to start the server.

Open browser at http://localhost:8000

## Components

- LangChain for LLM interactions
- ChromaDB for vector storage
- Chainlit for UI
- OpenAI GPT-4 for responses
