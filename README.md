# Askwise – AI Knowledge Base Chatbot

Askwise is an AI-powered SaaS chatbot platform that lets businesses upload documents and build their own smart assistants trained on internal content.

## 🌐 Live Demo
[https://askwise.io](https://askwise.io)

## ✨ Features
- Upload PDFs, DOCX, TXT – auto-training
- Chat interface with OpenAI/GPT
- Pinecone vector store
- Token-based usage analytics
- SaaS: per-user KB, rate limits, billing
- Stripe subscriptions
- Mobile-optimized UI

## ⚙️ Tech Stack
- React, Node.js, Express, MongoDB
- OpenAI API, Pinecone, Firebase
- Vercel (frontend), Render (backend)

## 📂 Structure
- `frontend/`: Chat interface + dashboard
- `backend/`: API + embeddings + vector DB logic
- `vector_db/`: Pinecone wrappers/config

## 🚀 Getting Started
```bash
git clone https://github.com/syntaxcraft/askwise-ai-chatbot.git
cd askwise-ai-chatbot
# Add OpenAI + Pinecone API keys
docker-compose up --build
📄 License
Commercial – © SyntaxCraft
