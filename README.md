# AuraV7

<div align="center">

# 🌟 Aura: The Holistic Student Copilot

[![Hackathon Project](https://img.shields.io/badge/Hackathon-Submission-blue.svg)](#)
[![Tech Stack: React](https://img.shields.io/badge/Frontend-React%20%7C%20Next.js-61DAFB?logo=react&logoColor=black)](#)
[![Tech Stack: Python](https://img.shields.io/badge/Backend-Python%20%7C%20FastAPI-3776AB?logo=python&logoColor=white)](#)
[![AI Powered](https://img.shields.io/badge/AI-OpenAI%20%7C%20Whisper-412991?logo=openai&logoColor=white)](#)

*Building ed-tech that treats students like humans, not machines.*

[**Watch the Demo Video**](link-to-your-youtube-video) • [**View Live Deployment**](link-to-your-vercel-app)
</div>


## 💡 The Inspiration
Current educational technology focuses purely on content delivery. It ignores the realities of modern student life: burnout, accessibility needs, and overwhelming schedules. When students are trying to balance complex courses—like first-order differential equations or industrial electrical systems—the drive for academic success often comes at the cost of mental well-being. 

**Aura** was built to bridge this gap. It is an AI-powered learning hub that adapts to *how* a student learns and *how they are feeling*.

## ✨ Key Features

### 📚 1. Smart Lecture Breakdown
Upload raw lecture audio or video. Aura instantly processes the file and returns structured notes, a brief summary, and a visual concept map. 
* *Tech: Whisper API for Speech-to-Text, LLM for summarization.*

### 🧠 2. Adaptive Spaced Repetition
Aura automatically generates flashcards from your lecture notes. The AI tracks your response times and accuracy, seamlessly adjusting the difficulty of your next study session so you spend time only on what you don't know.

### 🧘‍♀️ 3. Burnout Predictor & Wellness Integration
Aura prompts users with a quick daily check-in. Using sentiment analysis, the app flags distress patterns. If a student is overwhelmed, Aura will automatically suggest rescheduling study blocks, generate a visual dashboard of their progress to reduce anxiety, and provide links to campus mental health resources.

### 👁️ 4. Built-in Inclusivity
A single toggle instantly transforms the entire UI into a spaced, high-contrast, dyslexia-friendly format, alongside real-time text-to-audio reading options.


## 🏗️ Architecture & Tech Stack

Aura is built with a modern, decoupled architecture designed for speed and scalability during the hackathon:

**Frontend Interface**
* **React / Next.js:** For a snappy, responsive single-page application.
* **Tailwind CSS:** For rapid UI styling and implementing the dyslexia-friendly theme toggle.
* **D3.js / Chart.js:** For rendering interactive data visualizations of the student's study habits and wellness trends.

**Backend & AI Engine**
* **FastAPI (Python):** Handles routing, audio file uploads, and API communication.
* **OpenAI Whisper API:** High-accuracy audio transcription.
* **OpenAI GPT-4:** Natural language processing for generating summaries, flashcards, and sentiment analysis on daily check-ins.

## 🚀 Getting Started

Follow these steps to run Aura locally on your machine.

### Prerequisites
* Node.js (v16+)
* Python (3.9+)
* An OpenAI API Key

### Installation

1. **Clone the repository**
   ```bash
   git clone [https://github.com/your-username/aura-student-copilot.git](https://github.com/your-username/aura-student-copilot.git)
   cd aura-student-copilot
