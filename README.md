# AI-voice-assistent
🗣️ AI Voice Assistant — Python-based Smart LLM Bot
A powerful AI Voice Assistant built using Python that listens to your voice, understands your intent using a Large Language Model (LLM), and speaks back the response using TTS (Text-to-Speech).
Supports real-time interruption, streaming responses, and integrates with APIs like OpenAI, DeepSeek, ElevenLabs, or pyttsx3.

Features
🎙️ Real-time Speech Recognition (speech_recognition)

🧠 Natural Language Understanding using LLM (OpenAI or DeepSeek)

🗣️ Voice Output with ElevenLabs or pyttsx3

🔁 Continuous conversation loop

⏱️ Interruptible input (auto-detects when user starts talking again)
Tech Stack
Python (Flask/CLI)

OpenAI or DeepSeek LLM

ElevenLabs or pyttsx3 (TTS)

speech_recognition for voice input

Optional: GUI with Tkinter or Streamlit

How to Run
bash
Copy
Edit
pip install -r requirements.txt
python assistant.py

Environment Setup (example)
env
Copy
Edit
OPENAI_API_KEY=your-key
ELEVENLABS_API_KEY=your-key










