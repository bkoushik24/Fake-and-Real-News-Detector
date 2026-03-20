# Fake-and-Real-News-Detector
Developed an AI-powered Fake News Detection system using Streamlit and transformer-based zero-shot classification. Integrated Retrieval-Augmented Generation (RAG) with real-time web search (SerpAPI) to verify claims against live data. Designed an explainable interface with confidence scoring and evidence-based reasoning.
# 🧠 AI Fake News Detector (RAG + Streamlit)

An industry-level AI-powered web application that detects whether a news claim is **Fake or Real** using **Retrieval-Augmented Generation (RAG)** and **transformer models**.

---

## 🚀 Features

- 🔍 Real-time news verification using SerpAPI
- 🧠 AI-based classification (Fake / Real)
- 📊 Confidence score visualization
- 🌐 Evidence retrieval from live sources
- 💡 Explainable AI output
- 🎨 Modern Streamlit UI
- ⚡ Fast and interactive interface

---

## 🏗️ Tech Stack

- **Frontend/UI:** Streamlit
- **Backend:** Python
- **AI Model:** Hugging Face Transformers (Zero-shot classification)
- **API:** SerpAPI (Google Search)
- **Libraries:** requests, torch

---

## 🧠 How It Works

1. User enters a news claim
2. App retrieves real-time related articles using SerpAPI
3. Extracted snippets are used as evidence
4. AI model compares claim + evidence
5. Outputs:
   - Fake / Real classification
   - Confidence score
   - Supporting evidence

---
