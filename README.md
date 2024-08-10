# LLOYD Assistant

A multimodal agent that uses livekit, deepgram and openai to chat with users in real-time.

## Installation

```bash
git clone https://github.com/simandebvu/multimodal
cd multimodal
pip install -r requirements.txt
```

## Usage

Describe how to use your project. For example:

```bash
python agent.py
```

## Features

- Multimodal agent that uses livekit, deepgram and openai to chat with users in real-time
- Uses the `livekit-agents` library to create a multimodal agent
- Uses the `livekit-plugins-deepgram` and `livekit-plugins-openai` libraries to use deepgram and openai respectively
- Uses the `dotenv` library to manage environment variables
- Uses the `requests` library to send requests to the livekit server
- Uses the `websockets` library to connect to the livekit server
- Uses the `asyncio` library to handle asynchronous tasks
- Uses the `json` library to handle json data

## Dependencies

This project requires:
- Python 3.8+
- OpenAI API
- Deepgram API
- dotenv

## Configuration

1. Create a `.env` file in the root directory.
2. Add your API keys and organization ID:

```
OPENAI_API_KEY=your_openai_api_key_here
OPENAI_ORGANIZATION_ID=your_organization_id_here
DEEPGRAM_API_KEY=your_deepgram_api_key_here
```
