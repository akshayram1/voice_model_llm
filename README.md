# Voice Assistant Application

## Prerequisites
- Python 3.9+
- OpenAI API Key
- Groq API Key

## Setup
1. Clone the repository
2. Create a virtual environment:
   ```
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. Install dependencies:
   ```
   pip install -r requirements.txt
   ```

4. Create a `.env` file with your API keys:
   ```
   OPENAI_API_KEY=your_openai_key
   GROQ_API_KEY=your_groq_key
   ```

5. Run the application:
   ```
   uvicorn main:app --reload
   ```

## Features
- Real-time voice activity detection
- Audio transcription using Groq Whisper
- AI-powered chat responses
- Text-to-speech responses

## Technology Stack
- FastAPI
- WebRTC VAD
- OpenAI TTS
- Groq API
- WebSocket communication# voice_model_llm


## in the app.py streamlit file is there for gui and for web gui i have not created anything only main.py have backend code 

## app.py is working fine 

## config file : -> config = {"OPENAI_API_KEY":"","GROQ_API_KEY":""}


##  Document Link (only for QED42 Org.)

https://docs.google.com/document/d/1vyL0u_7tCTWM4ewC6eszpozkMmUulmyQZLPL3pSxGbA/edit?usp=sharing