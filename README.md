# 🎙️ Leo - Voice Assistant  

Leo is a simple **Python-based voice assistant** (like Alexa or Google Assistant) that can:  
- 🔊 Listen to your voice commands  
- 🗣️ Reply using text-to-speech (gTTS + pygame)  
- 🌐 Open websites (Google, YouTube, Facebook, LinkedIn)  
- 🎵 Play songs from a local music library  
- 📰 Read the latest news (via NewsAPI)  
- 🤖 Answer general questions (offline dictionary-based AI)  

---

## 📂 Project Structure  

├── main.py # Core voice assistant logic
├── musicLibrary.py # Dictionary of songs with YouTube links
├── client.py # Offline AI logic (rule-based responses)
├── requirements.txt # Required Python dependencies


---

## ⚡ Installation  

1. Clone this repository:  
   ```bash
   git clone https://github.com/<your-username>/Leo-Voice-Assistant.git
   cd Leo-Voice-Assistant
2. Installing Dependencies:
   pip install -r requirements.txt
3. Add your NewsAPI key in main.py:
   newsapi = "<Your Key Here>"
