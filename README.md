# 🎥 YouTube Video Usefulness Analyzer

A powerful and interactive Jupyter Notebook-based tool that analyzes the **usefulness** of YouTube videos based on your **topic of interest**. It evaluates **keyword density**, **semantic similarity**, and **sentiment**, and generates a **usefulness score** with intuitive visualizations.

---

## 🚀 Features

- 📜 **Transcript Extraction** via:
  - YouTube Transcript API
  - Video captions using `yt-dlp`
  - Automatic audio transcription using OpenAI Whisper

- 📊 **Score Components**:
  - **Keyword Density**
  - **Semantic Similarity** (via `sentence-transformers`)
  - **Sentiment Analysis** (via VADER)

- 📈 **Interactive Widgets** for:
  - Inputting URL, keywords, topic
  - Customizing score weights

- 🎨 **Visualizations** using `matplotlib` and `seaborn`

- ✅ Caches models using `@lru_cache` for faster performance

---

## 🧰 Installation

Make sure you have Python 3.7+ installed.

Install all required packages via pip:

```bash
pip install youtube-transcript-api transformers sentence-transformers vaderSentiment pandas matplotlib seaborn yt-dlp openai-whisper torch ipywidgets
