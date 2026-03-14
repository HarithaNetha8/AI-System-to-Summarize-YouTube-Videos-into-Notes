
# 🎥 AI System to Summarize YouTube Videos into Notes (Google Colab)

## 📌project Overview

This project is an **AI-powered YouTube video summarization system** built using **Python and Large Language Models**.
It runs completely on **Google Colab**, making it easy to use without any local setup.

The system extracts subtitles from YouTube videos, splits long transcripts into chunks, and uses **Google’s Flan-T5 model** to generate clean, structured notes.

---

## 🚀 Features

* 📎 Works directly in **Google Colab**
* 🔗 Accepts YouTube video URLs
* 🎧 Automatically extracts subtitles
* ✂️ Handles long videos using chunking
* 🧠 Generates AI-powered summaries
* ⚡ Supports GPU acceleration (CUDA)

---

## 🛠️ Technologies Used

* **Python**
* **Google Colab**
* **youtube-transcript-api**
* **Hugging Face Transformers**
* **Flan-T5-Base**
* **PyTorch**

---

## ▶️ How to Run on Google Colab

### Step 1: Open Google Colab

Go to 👉 [https://colab.research.google.com](https://colab.research.google.com)
Create a **New Notebook**

---

### Step 2: Install Required Libraries

Run this cell:

```python
!pip install -U youtube-transcript-api transformers accelerate sentencepiece
```

---

### Step 3: Enable GPU (Recommended)

* Click **Runtime → Change runtime type**
* Set **Hardware accelerator** to **GPU**
* Click **Save**

---

### Step 4: Run the Code

Copy and paste the project code into Colab cells and run all cells.

When prompted, paste a YouTube video URL:

```
Paste YouTube URL: https://www.youtube.com/watch?v=XXXXXXXXXXX
```

---

## 🧠 Model Details

* **Model:** `google/flan-t5-base`
* Encoder–Decoder architecture
* Optimized for summarization tasks
* Uses Beam Search for better output quality

---

## 📌 Output

The system generates **bullet-point AI notes** summarizing the entire video, displayed directly in the Colab output cell.

---

## 🎯 Use Cases

* Students summarizing lecture videos
* Self-learners saving study time
* Engineers reviewing technical talks
* Researchers processing long video content

---

## 🔮 Future Improvements

* Export notes as PDF
* Multi-language summarization
* Timestamp-based highlights
* Streamlit web interface

