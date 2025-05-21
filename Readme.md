# 🚀 GroMo LeadGen AI Agent

Welcome to the **GroMo LeadGen AI Agent**, a multilingual, AI-powered platform designed to revolutionize lead generation, qualification, and conversion for GroMo Partners. Built for the **FinArva AI Hackathon 2025**, this solution leverages cutting-edge AI, scalable cloud infrastructure, and voice automation—tailored for Bharat’s next billion users.

---

## 📌 Problem Statement Addressed

> GroMo Partners face difficulty in identifying and converting high-quality leads, especially across India’s diverse and multilingual markets. Our solution enhances productivity, earnings, and engagement with a full-stack AI pipeline.

---

## 🧠 Key Features

- **Multilingual Lead Generation** from LinkedIn, JustDial & other platforms
- **AI-Powered Lead Scoring & Ranking** using LangChain + OpenAI/Gemini
- **Localized Pitch Script Generator** using Sarvam AI (Hindi, Tamil, Kannada, etc.)
- **Interactive AI Sales Coach** for GroMo Partner upskilling
- **Post-Sale Voice Automation Assistant** powered by Sarvam AI
- **Real-Time Data Sync** via Firebase and partner dashboard
- **Bharat-First UI**: Lightweight, fast, mobile-ready, and offline-friendly

---

## 🏗️ Tech Stack

| Layer            | Technology                                     |
|------------------|------------------------------------------------|
| Frontend         | Next.js, TailwindCSS, Redux                    |
| Backend          | FastAPI (async Python)                         |
| Auth & DB        | Firebase Auth + Firestore + PostgreSQL         |
| AI Integration   | LangChain, OpenAI, Gemini, Sarvam AI           |
| Voice AI         | Sarvam AI for Hindi/vernacular voice UX        |
| Scraping Engine  | Apify, PhantomBuster, Puppeteer                |
| Cloud Infra      | GCP (Cloud Run, Kubernetes), GitHub Actions    |
| Realtime Comm    | Firebase Realtime DB + Cloud Functions         |

---

## 🧩 Architecture Highlights

- **Scrapers** pull lead data every hour from multiple sources
- **LangChain pipelines** analyze text, extract insights, rank leads
- **LLMs (OpenAI/Gemini)** generate pitch copy, simulate buyer responses
- **Sarvam AI** transcribes and replies to voice calls in native languages
- **FastAPI** routes leads to GroMo Partners based on dynamic scoring
- **Firebase** pushes leads and training feedback in real-time to partners

---

## 🎙️ AI Use Cases

| Feature                     | Model Used      | Purpose                                     |
|-----------------------------|-----------------|---------------------------------------------|
| Lead Scoring & Ranking      | OpenAI / Gemini | Classify & prioritize best potential leads  |
| Voice Sales Automation      | Sarvam AI       | Handle post-sale engagement in vernaculars  |
| Regional Pitch Generator    | Sarvam AI       | Language-specific pitch script generation   |
| AI Sales Coach & Tutor      | LangChain       | Simulate real-world conversations           |
| Lead Enrichment             | LangChain       | Extract intent, tags, geo, financial cues   |

---

