# 🎥 YouTube Video Analyzer

An AI-powered tool that analyzes YouTube videos by downloading audio, transcribing speech, summarizing content, translating to Arabic, and enabling QA through chatbot interaction.

## ✨ Features

- ✅ Download audio from any YouTube video
- ✅ Transcribe audio using Whisper (Fast/Accurate)
- ✅ Summarize the transcript into bullet points
- ✅ Translate summary to Arabic (Fusha)
- ✅ Ask questions about the video using RAG (Retrieval-Augmented Generation)
- ✅ Clean and responsive Gradio UI

## 🛠 Requirements

Install the required packages using:

```bash
pip install -r requirements.txt
```

Also make sure `ffmpeg` is installed on your system.

For Ubuntu/Debian:

```bash
sudo apt update
sudo apt install ffmpeg
```

## 🚀 How to Run

1. Clone or download the repository.
2. Make sure you have Python 3.8+.
3. Run the app using:

```bash
python app.py
```

Then open your browser to the Gradio link shown in the terminal.

## 📂 File Structure

- `app.py` – Main Python app with Gradio interface
- `requirements.txt` – All required Python packages
- `setup.sh` – (Optional) Shell script for automatic setup

## 📌 Notes

- This app uses OpenAI (gpt-3.5-turbo) and Whisper via `faster-whisper`
- Make sure you have an OpenAI API key in your environment as `OPENAI_API_KEY`
- Best used in environments with access to ffmpeg and Python virtual environments

## 📺 Demo Videos
[Click here to view demo videos on Google Drive](https://drive.google.com/drive/folders/1Mev4RdZewnkRV5ufqk2hPk42hvtxt3O1?usp=drive_link)

---

Made with ❤️ using Python, LangChain, OpenAI, Gradio, and Hugging Face.