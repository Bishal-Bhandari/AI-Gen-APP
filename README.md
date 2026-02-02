# 🎥 Video to Blog Generator

This project converts a **YouTube video link** into a **well-structured blog post** automatically.

It works by extracting the video transcript and using AI to transform it into a readable blog article.

Built with **Django**, **AssemblyAI**, **PostgreSQL**, and **OpenAI**.

---

## 🚀 Features

- Submit a YouTube video link
- Fetch video transcript using **AssemblyAI**
- Generate blog content using **OpenAI**
- Store transcripts and blogs in **PostgreSQL**
- Backend built with **Django**

---

## 🛠️ Tech Stack

- **Backend:** Django (Python)
- **Transcription:** AssemblyAI
- **AI Blog Generation:** OpenAI
- **Database:** PostgreSQL (Managed DB via Qovery)

---

## 🔄 How It Works

1. User submits a YouTube video link  
2. AssemblyAI extracts the transcript  
3. Transcript is stored in PostgreSQL  
4. OpenAI generates a blog post from the transcript  
5. Blog post is returned as output  

---

## ⚙️ Installation

### Create & Activate Virtual Environment

```bash
python -m venv venv
source venv/bin/activate   # Windows: venv\Scripts\activate
```
### Install Dependencies
```bash
pip install -r requirements.txt
```
### Apply Migrations
```bash
python manage.py makemigrations
python manage.py migrate
```
### Run the Server
```bash
python manage.py runserver
