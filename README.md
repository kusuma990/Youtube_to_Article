# Youtube_to_Article
# 🎥 YouTube to Insightful Article & PDF Generator

## 🚀 Overview

This project is a **GenAI-powered application** that converts any YouTube video into a **well-structured article and downloadable PDF**.

It extracts audio from the video, converts speech to text, processes the content, and generates meaningful insights in the form of an article.

---

## ✨ Features

* 🎬 Extract audio from YouTube videos
* 🎙️ Convert speech to text (Speech Recognition)
* 🧠 Generate insightful article from transcript
* 📄 Export content as downloadable PDF
* 🌐 Simple and interactive UI using Streamlit

---

## 🧠 How It Works

```
YouTube URL
   ↓
Audio Extraction (yt-dlp)
   ↓
Audio Conversion (FFmpeg)
   ↓
Speech-to-Text (SpeechRecognition)
   ↓
Text Processing (NLP)
   ↓
Article Generation
   ↓
PDF Export
```

---

## 🛠️ Tech Stack

* Python
* Streamlit
* yt-dlp
* SpeechRecognition
* pydub
* FPDF
* FFmpeg

---

## 📁 Project Structure

```
youtube_to_article/
│
├── app.py
├── requirements.txt
│
└── utils/
    ├── downloader.py
    ├── transcriber.py
    ├── generator.py
    ├── pdf_generator.py
```

---

## ⚙️ Installation

### 1. Clone the repository

```
git clone https://github.com/kusuma990/Youtube_to_Article.git
cd youtube-to-article
```

---

### 2. Install dependencies

```
pip install -r requirements.txt
```

---

### 3. Install FFmpeg (Important)

Download FFmpeg and add it to your system PATH.

Check installation:

```
ffmpeg -version
```

---

## ▶️ Run the Application

```
streamlit run app.py
```

Open in browser:

```
http://localhost:8501
```

---

## 🧪 Usage

1. Enter a YouTube video URL
2. Click **Generate Article**
3. View generated article
4. Download PDF

---

## ⚠️ Notes

* First run may take time (audio processing)
* Requires internet connection
* FFmpeg must be installed correctly
* Works for any public YouTube video

---

## 🚀 Future Improvements

* AI-powered summarization (LLM integration)
* Multi-language support
* Faster transcription (Whisper)
* Video metadata extraction
* Deployment on cloud (Hugging Face / AWS)

---

## 🎯 Use Cases

* Content summarization
* Study notes generation
* Blog/article creation
* Knowledge extraction from videos

---

## 🤝 Contributing

Contributions are welcome!
Feel free to fork this repo and submit a pull request.

---

## 📜 License

This project is open-source and available under the MIT License.

---

## 👩‍💻 Author

**Kusuma Kumari Bodduluri**

- 🔗 LinkedIn: www.linkedin.com/in/kusuma-kumari-bodduluri
- 💻 GitHub: https://github.com/kusuma990/Youtube_to_Article
---

## ⭐ Support

If you like this project, please ⭐ the repository!

---
