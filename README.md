# 🎤 AI Voice Assistant using Local LLM 

A simple Python-based AI Voice Assistant that:
- Listens to your voice
- Sends your speech to a locally hosted LLM using Ollama
- Speaks back the AI response

---

## 🚀 Features

- Real-time voice input
- Speech-to-text using Google Speech Recognition
- AI responses using Ollama
- Text-to-speech output
- Continuous conversation loop
- Exit command support

---

## 🛠 Technologies Used

- Python
- SpeechRecognition
- pyttsx3
- Requests
- Ollama
- Llama 4

---

## 📦 Installation

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## 🦙 Install Ollama

Download Ollama from:

https://ollama.com

Pull the model:

```bash
ollama pull llama4
```

Start Ollama:

```bash
ollama serve
```

---

## ▶️ Run the Project

```bash
python listen.py
```

---

## 🧠 How It Works

1. User speaks through microphone
2. Speech converted to text
3. Text sent to Ollama LLM
4. AI response generated
5. Response spoken back using TTS

---

## ❌ Exit Commands

Say:

- exit
- stop
- quit

---

## 🔮 Future Improvements

- Wake word detection
- GUI interface
- Streaming responses
- Offline speech recognition
- Multi-language support
- Memory support

---

## 📜 License

MIT License

---

## 👨‍💻 Author

Shubham
