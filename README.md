<div align="center">

<img src="header.svg" width="100%" alt="Nakshatra Garg — LLM Inference, GenAI & Voice AI"/>

<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=38BDF8&center=true&vCenter=true&width=720&lines=Serving+~2.5M+voice-bot+calls%2Fday+on+self-hosted+LLMs+%F0%9F%9A%80;vLLM+%E2%80%A2+NVIDIA+H200+%E2%80%A2+50ms+TTFT+%E2%9A%A1;Hybrid+RAG+%E2%80%A2+LoRA+Fine-tuning+%E2%80%A2+Guardrails+%F0%9F%9B%A1%EF%B8%8F;Real-time+ASR+%2F+TTS+%2F+Voice+Bots+%F0%9F%8E%99%EF%B8%8F" alt="Typing SVG" /></a>

<p>
  <a href="https://www.linkedin.com/in/nakshatra-garg"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="mailto:gargnakshatra11@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
  <img src="https://komarev.com/ghpvc/?username=nakshatra-garg&style=for-the-badge&color=0ea5e9&label=PROFILE+VIEWS"/>
</p>

</div>

---

## 👋 About Me

<img align="right" alt="LLM + Voice AI" src="hero.svg" width="36%" />

I'm a **Data Scientist / AI Engineer at [Rezo.AI](https://rezo.ai)** with **3+ years** of building production **LLM** and **Voice AI** systems for enterprise clients.

I love the hard part of AI — taking models out of notebooks and making them **fast, cheap, safe and reliable at scale**.

- 🔭 Currently owning a **self-hosted open-weight LLM** on **vLLM + NVIDIA H200s**, serving **~2.5M calls/day**
- 🌱 Working on **in-house ASR & TTS** data and training pipelines
- 🎓 M.Tech CSE (AI & ML minor), **VIT Vellore** · B.Tech IT, **COER Roorkee**
- 📍 Noida, India
- 💬 Ask me about **LLM inference, RAG, guardrails, voice bots**
- ⚡ Fun fact: I made "time-to-first-*sentence*" our north-star latency metric — because voice users don't hear tokens

<br clear="right"/>

---

## 🏆 Impact at a Glance

<div align="center">

| 📞 Calls / Day | 💰 Inference Cost | ⚡ TTFT | 🗣️ p95 TTFS | 🚀 Audio Encode | 🎯 LangID Accuracy |
|:---:|:---:|:---:|:---:|:---:|:---:|
| **~2.5M** | **↓ ~40%** | **50 ms** | **0.3 s** | **35× faster** | **98%** |

| 🔍 RAG precision@3 | 👥 Concurrent Callers (LangID) | 🛡️ Guardrail Layers |
|:---:|:---:|:---:|
| **~80%** | **500+ @ <300 ms p95** | **5, in real time** |

</div>

---

## 🛠️ What I've Built

<details open>
<summary><b>🧠 Self-Hosted LLM Platform — replaced a third-party LLM API</b></summary>
<br>

- Open-weight LLM on **vLLM + NVIDIA H200**, serving **~2.5M voice-bot calls/day**
- **Smart LLM router on HAProxy** · **~40% lower inference cost** · zero external data exposure
- **50 ms TTFT · 0.3 s p95 / 0.6 s p99 TTFS · 1.5–2 s p95 full response**, tracked live in **Prometheus**
</details>

<details open>
<summary><b>🛡️ Multi-Layer Guardrails & Post-Processing</b></summary>
<br>

- PII redaction · thinking-token leak suppression · repetition control
- Harmful-content filtering · system-prompt adherence — **all inside the real-time latency budget**
</details>

<details open>
<summary><b>🌐 GPU Voice Language-ID Service</b></summary>
<br>

- **vLLM + open multimodal model** in production · **98% accuracy**
- **35× faster audio encoding** via **CUDA graph capture** · **500+ concurrent callers at sub-300 ms p95**
- Multi-GPU rollout **A100 → NVIDIA Blackwell**
</details>

<details>
<summary><b>🔍 Hybrid-Retrieval RAG for Chatbots & Voice Bots</b></summary>
<br>

- **BM25 + dense vectors (Qdrant) + reranking** across multiple enterprise clients
- **~80% precision@3**, fewer hallucinations, better flow completion
- Embedding service with **two-tier caching (Redis + Qdrant)** on **BGE-M3**
</details>

<details>
<summary><b>🧬 LLM Fine-Tuning & Evaluation</b></summary>
<br>

- **LoRA** fine-tuning of **Qwen3.5-4B** and **Gemma-4B**
- Evaluation via **LLM-as-a-judge + human review**
</details>

<details>
<summary><b>🧾 OCR for Banking KYC & 📊 Speech Analytics</b></summary>
<br>

- Aadhaar / PAN extraction for a **leading Indian bank**, powering production KYC
- **+15% OCR accuracy** through detection → OCR pipeline tuning and drift-aware retraining
- Call analytics: conversational flow, silences, interruptions, response latency
</details>

---

## 🧰 Tech Stack

**🤖 LLM Serving & GenAI**

![vLLM](https://img.shields.io/badge/vLLM-30A2FF?style=for-the-badge&logo=lightning&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![LoRA/QLoRA](https://img.shields.io/badge/LoRA%20%2F%20QLoRA-FF6F00?style=for-the-badge&logo=huggingface&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white)
![CUDA](https://img.shields.io/badge/CUDA-76B900?style=for-the-badge&logo=nvidia&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)

**🔍 Retrieval & Vector Search**

![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=for-the-badge&logo=qdrant&logoColor=white)
![pgvector](https://img.shields.io/badge/pgvector-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=for-the-badge&logo=meta&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6446?style=for-the-badge&logoColor=white)
![BGE-M3](https://img.shields.io/badge/BGE--M3%20Embeddings-6E40C9?style=for-the-badge&logoColor=white)

**🎙️ Speech & Voice AI**

![Whisper](https://img.shields.io/badge/Whisper-412991?style=for-the-badge&logo=openai&logoColor=white)
![SpeechBrain](https://img.shields.io/badge/SpeechBrain-FF9900?style=for-the-badge&logo=python&logoColor=white)
![Azure Speech](https://img.shields.io/badge/Azure%20Speech-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)

**⚙️ APIs, LLMOps & Infra**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![WebSocket](https://img.shields.io/badge/WebSocket-010101?style=for-the-badge&logo=socketdotio&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![HAProxy](https://img.shields.io/badge/HAProxy-106DA9?style=for-the-badge&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

**☁️ Cloud & GPUs**

![Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white)
![Bedrock](https://img.shields.io/badge/AWS%20Bedrock-FF9900?style=for-the-badge&logo=amazonwebservices&logoColor=white)
![NVIDIA](https://img.shields.io/badge/H200%20%7C%20Blackwell%20%7C%20A100-76B900?style=for-the-badge&logo=nvidia&logoColor=white)

**👁️ OCR & Vision**

![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![YOLO](https://img.shields.io/badge/YOLO-00FFFF?style=for-the-badge&logoColor=black)
![Tesseract](https://img.shields.io/badge/Tesseract-3C8DBC?style=for-the-badge&logoColor=white)

---

## 🗺️ Journey

```text
2022 ── 🎓 B.Tech IT · College of Engineering Roorkee
2023 ── 🧪 Data Science Intern @ Rezo.AI · OCR + Speech Analytics
2024 ── 🎓 M.Tech CSE (AI & ML) · VIT Vellore
2024 ── 🚀 Data Scientist / AI Associate @ Rezo.AI
          └─ RAG · Language ID · Guardrails
2025+ ─ 🧠 Self-hosted LLM at ~2.5M calls/day on H200s
          └─ Now: in-house ASR & TTS models
```

---

## 📊 GitHub Stats

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=nakshatra-garg&count_private=true&include_all_commits=true&show_icons=true&theme=tokyonight&hide_border=true" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=nakshatra-garg&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" />

<img width="90%" src="https://github-readme-activity-graph.vercel.app/graph?username=nakshatra-garg&theme=tokyo-night&hide_border=true&area=true" />

</div>

---

<div align="center">

### 🤝 Let's build fast, safe, production-grade AI together

**Open to conversations on LLM inference, RAG, and Voice AI.**

<a href="https://www.linkedin.com/in/nakshatra-garg"><img src="https://img.shields.io/badge/Connect%20on%20LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="mailto:gargnakshatra11@gmail.com"><img src="https://img.shields.io/badge/Say%20Hello-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>

<img src="footer.svg" width="100%"/>

</div>
