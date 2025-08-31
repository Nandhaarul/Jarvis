# Jarvis Voice Assistant

A personalized, real-time voice assistant built in Python using the ElevenLabs conversational AI API. This project demonstrates conversational AI, speech synthesis, and secure API integration.

## Features

- Real-time conversational AI with speech synthesis
- Personalized greetings and prompts
- Secure API key management using environment variables
- Modular callback functions for agent/user interaction
- Easily extensible for new features (e.g., scheduling, reminders)

## Tech Stack

- Python
- ElevenLabs API
- [python-dotenv](https://pypi.org/project/python-dotenv/)
- Pydantic (via ElevenLabs)
- Standard Python libraries

## Setup Instructions

1. **Clone the repository**
   
2. **Create and activate a virtual environment (optional but recommended)**

3. **Install dependencies**
 
4. **Set up your `.env` file**
   - Create a file named `.env` in the project root.
   - Add your ElevenLabs API key:
     ```
     ELEVENLABS_API_KEY=your_actual_api_key_here
     ```

5. **Update configuration in `voice_assistant.py`**
   - Replace `"Agent id here"` with your actual ElevenLabs agent ID.
   - Ensure `API_KEY = os.getenv("ELEVENLABS_API_KEY")` is set.

6. **Run the assistant**
   ```sh
   python voice_assistant.py
   ```
