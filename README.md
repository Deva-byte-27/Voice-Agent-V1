🎙️ AI Voice Agent V1 — Real-Time Bible Verse Detection
A real-time voice-based system that listens to spoken audio, transcribes it using OpenAI Whisper, and detects/identifies Bible verse references mentioned in the speech using NLP.
✨ Features
🎤 Real-time audio capture and speech-to-text using OpenAI Whisper
📖 Detects and extracts Bible verse references (book, chapter, verse) from transcribed text
🧠 NLP-based reference parsing and validation
⚡ Lightweight, runs locally with Python virtual environment
🛠️ Tech Stack
Python
OpenAI Whisper (Speech-to-Text)
NLP (text processing & reference extraction)
Jupyter Notebook
📂 Project Structure
Code
Training_agent/
├── Version_01.ipynb       # Main notebook with the pipeline
├── .env.example            # Example environment variables
├── .venv/                   # Virtual environment (not pushed to GitHub)
└── README.md
🚀 Getting Started
1. Clone the repository
Bash
git clone https://github.com/Deva-byte-27/Voice-Agent-V1.git
cd Voice-Agent-V1
3. Set up virtual environment
Bash
python -m venv .venv
.venv\Scripts\activate    # Windows

5. Install dependencies
Bash
pip install -r requirements.txt
7. Configure environment variables
Copy .env.example to .env and fill in any required keys.
8. Run the notebook
Open Version_01.ipynb in Jupyter/VS Code and run the cells.
📌 How It Works
Audio input is captured from the microphone
Whisper transcribes the audio into text in real time
The transcribed text is scanned for Bible verse references (e.g., "John 3:16")
Matched references are validated and displayed/returned
🔮 Future Improvements
Add a simple UI for live transcription display
Support multiple Bible translations
Improve detection accuracy for partial/ambiguous references
👤 Author
Sanjay Deva M.G
B.Tech AI & Data Science Student
