# BrightPath-Speech
BrightPath Speech
🎤 BrightPath Speech (TalkMetrics)
An AI-powered speech therapy assistant designed to help Speech-Language Pathologists (SLPs), clinicians, and students track pronunciation progress through interactive speech analysis, scoring, and visualization.

🚀 Features
🎙️ Voice Recording – Record and analyze speech samples in real time.
🤖 AI Pronunciation Analysis – Transformer-based models evaluate clarity and accuracy.
💾 SQLite Database Integration – Store student data, session history, and therapy goals.
📊 Progress Visualization – Built-in analytics dashboard using Plotly and Dash.
🧠 Data Security – Designed with FERPA-compliant principles for safe educational use.
🧩 Tech Stack
Category	Technologies
Backend	Python (Flask, SQLAlchemy)
AI / ML	PyTorch, Transformers, Torchaudio
Visualization	Dash, Plotly
Database	SQLite
Audio Processing	PyAudio, SoundFile, SciPy
⚙️ Installation
Clone the repository

git clone https://github.com/saimasano123/BrightPath_Speech.git
cd BrightPath_Speech
Create and activate a virtual environment

python -m venv .venv
.venv\Scripts\activate   # On Windows
source .venv/bin/activate  # On macOS/Linux
Install dependencies

pip install -r requirements.txt
Initialize the database

python init_db.py
Run the app

python app.py
Then open your browser and visit:
👉 http://127.0.0.1:5000/

📂 Project Structure
BrightPath_Speech/
│
├── app.py                   # Flask entry point
├── models.py                # ORM models
├── audio_recorder.py        # Handles recording logic
├── voice_analyzer.py        # AI-based pronunciation analysis
├── visualization.py         # Dash/Plotly visualization
├── database/                # SQLite database + schema
├── demo_recordings/         # Example recordings
└── requirements.txt         # Python dependencies
🌟 Future Enhancements
📱 Add web-based dashboard for remote tracking
🗣️ Support for multilingual speech recognition
📈 Advanced analytics with student progress reports
☁️ Cloud-based database integration
