# Tamul-Ai
# 🎙️ Conversational Podcast AI Backend

A real-time **Conversational AI Backend** built with **FastAPI, WebSockets, and Google Cloud STT/TTS**, designed to power interactive podcast-style conversations.  
This project enables **streaming Speech-to-Text and Text-to-Speech** with low latency, context-aware AI dialogue, and scalable backend performance.

---

## 🚀 Features

- **Real-time Speech-to-Text (STT)** using Google Cloud Chirp HD  
- **Streaming Text-to-Speech (TTS)** with audio delivery via `/assets` endpoint  
- **Multi-agent LLM dialogue system** with advanced prompt engineering  
- **Context-aware memory** integration using Redis  
- **Asynchronous architecture** powered by `asyncio` and `janus queues`  
- **Parallelized TTS execution** via ThreadPoolExecutor for low-latency response handling  
- **FastAPI + WebSockets** for high-performance real-time communication  

---

## 🛠️ Tech Stack

- **Backend Framework:** FastAPI, WebSockets  
- **Programming Language:** Python  
- **Cloud Services:** Google Cloud Speech-to-Text & Text-to-Speech (Chirp HD)  
- **AI/LLM:** Prompt-engineered multi-agent system  
- **Database/Cache:** Redis (for memory and context storage)  
- **Concurrency:** asyncio, janus queues, ThreadPoolExecutor  

---
