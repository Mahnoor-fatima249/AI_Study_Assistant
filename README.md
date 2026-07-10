# 🎓 AI Study Assistant

An intelligent AI-powered learning assistant designed to help students study smarter by providing personalized explanations, AI-generated quizzes, voice interaction, and learning support through Generative AI.

## 🚀 Overview

**AI Study Assistant** is a smart educational platform that uses Artificial Intelligence to support students in their learning journey.

The application helps students understand difficult concepts, generate practice questions, get instant explanations, and interact with an AI tutor. It combines AI models, backend APIs, and modern application development to create a personalized learning experience.

---

## ✨ Features

### 🧠 AI Learning Assistant

* Ask questions and get AI-powered explanations
* Simplifies complex topics into easy concepts
* Provides step-by-step learning guidance
* Acts as a personal AI tutor

### 📝 AI Test & Quiz Generator

* Generates quizzes automatically
* Creates practice questions from topics
* Helps students prepare for exams
* Provides answer explanations

### 🎤 Voice Interaction

* Speech-to-text support
* Voice-based learning assistance
* Text-to-speech responses for better accessibility

### 📚 Personalized Learning

* Topic-based learning support
* Interactive study experience
* Helps students revise effectively

---

# 🏗️ System Architecture

```
              Student
                 |
                 ↓
          AI Study Assistant
                 |
        --------------------
        |                  |
        ↓                  ↓
   Frontend UI        Backend API
                           |
                           ↓
                    AI Model Integration
                           |
                           ↓
                  Response Generation
```

---

# 🛠️ Tech Stack

## Frontend

* Flutter
* Dart

## Backend

* FastAPI
* Python
* REST API

## AI Technologies

* Generative AI
* Large Language Models (LLMs)
* Prompt Engineering
* AI-based Question Generation

## Database

* SQLite

## Libraries & Tools

* Speech Recognition
* Text-to-Speech (TTS)
* Git & GitHub
* VS Code

---

# 📂 Project Structure

```
AI_Study_Assistant/
│
├── backend/
│   ├── app/
│   │   ├── main.py
│   │   ├── routes/
│   │   ├── services/
│   │   ├── models/
│   │   └── utils/
│   │
│   ├── requirements.txt
│   └── .env
│
├── frontend/
│   ├── lib/
│   │   ├── screens/
│   │   ├── widgets/
│   │   ├── services/
│   │   └── main.dart
│   │
│   └── pubspec.yaml
│
├── README.md
└── .gitignore
```

---

# ⚙️ Installation & Setup

## Clone Repository

```bash
git clone https://github.com/your-username/AI_Study_Assistant.git

cd AI_Study_Assistant
```

---

# Backend Setup

Go to backend folder:

```bash
cd backend
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Create `.env` file:

```env
AI_API_KEY=your_api_key
DATABASE_URL=your_database_url
```

Run FastAPI server:

```bash
uvicorn app.main:app --reload
```

Backend will run:

```
http://127.0.0.1:8000
```

---

# Frontend Setup

Go to frontend folder:

```bash
cd frontend
```

Install Flutter dependencies:

```bash
flutter pub get
```

Run application:

```bash
flutter run
```

---

# 🎯 Use Cases

* Students preparing for exams
* AI-based tutoring
* Self-learning platform
* Quick concept explanations
* Practice test preparation
* Interactive education system

---

# 🔮 Future Improvements

* Student progress tracking
* AI-based study plans
* RAG-based knowledge system
* PDF notes analysis
* Multi-language learning support
* Cloud deployment
* AI learning memory system

---

# 👩‍💻 Developer

**Mahnoor Fatima**
AI & Backend Developer

**Lokesh Kumar**
Frontend Developer

Focused on:

* Generative AI Applications
* AI Agents
* Backend Development
* Intelligent Learning Systems

---

# 📜 License

This project is developed for educational purposes and AI experimentation.
