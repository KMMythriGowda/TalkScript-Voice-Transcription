# 🎙 TalkScript – AI-Powered Voice Transcription System

TalkScript is an AI-powered web application that converts WhatsApp .ogg voice notes into editable text using speech recognition.
It supports multilingual transcription and provides downloadable transcripts.
It is designed to help students, professionals, and researchers quickly transcribe voice messages into readable text.

---

## 🚀 Features

- Upload WhatsApp voice notes (.ogg)
- Supports multiple languages (English & Hindi)
- AI-powered speech recognition
- Downloadable transcript file
- Simple web interface using Gradio

---

## 🛠 Technologies Used

- Python
- SpeechRecognition
- Pydub
- Gradio
- Google Speech Recognition API


---
## 📦 Installation

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/TalkScript-Voice-Transcription.git
cd TalkScript-Voice-Transcription

## 🏗 System Architecture

1. User uploads .ogg voice file  
2. Audio converted to .wav using Pydub  
3. SpeechRecognition processes audio  
4. Google API returns transcribed text  
5. Transcript saved as .txt file  
6. User downloads transcript

---
⭐ If you found this project useful, consider giving it a star.

---

TalkScript-Voice-Transcription/
│
├── app.py
├── requirements.txt
├── README.md
└── assets/
      ├── screenshot.png
      └── demo.mp4




