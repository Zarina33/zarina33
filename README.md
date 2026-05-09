# Hi there! 👋 I'm Zarina

## 🚀 About Me

ML Engineer & AI Researcher from Kyrgyzstan. 3+ years of production experience shipping LLMs, agentic RAG systems, NLP and Computer Vision at **100K+ user scale**. Published researcher in low-resource Turkic NLP.

- 🔭 Creator of **[AiRUN](https://airun.kg)** — world's #1 Kyrgyz LLM, beats **Gemma 3:27B** on PIQA, HellaSwag, BoolQ
- 🏦 Co-built a production **agentic RAG chatbot for Bakai Bank** (12-stage state machine, hybrid retrieval, multilingual RU/KG/EN)
- 🗣 Shipped the **first production Kyrgyz ASR & TTS**, plus a next-gen ASR at **8% WER** (~2× improvement)
- 🎓 Published at **ACL / EMNLP / ICML / ACM TALLIP** — first author on most
- 🌱 Currently going deep on **GPU optimization & inference performance**
- 📫 Reach me: **zarina.uvalievaa@gmail.com**

## 🛠 What I Build

### 🤖 LLMs & Agentic AI
- **AiRUN** — Kyrgyz LLM trained on 59M curated tokens. Beats Gemma 3:27B: PIQA **79.15%**, HellaSwag **67.57%**, BoolQ **90.54%**. 4,000+ active users
- **Agentic RAG chatbot** for Bakai Bank — 12-stage state machine, 11 FastAPI microservices, 5 banking intents with slot filling, real-time tool use (loan calculator, FX scraping, account lookup). Authored the **hybrid retrieval stack** (Qdrant + Elasticsearch BM25 + RRF 0.6/0.4 + BGE CrossEncoder reranking on GPU) and **safety layer** (PII detection, sentiment escalation, LLM-as-judge gating)
- **Conversational sales agent** for Bakai Digital — action-level multi-turn agent with catalog retrieval and generative vacation-planning fallback
- **University admissions assistants** (in dev) — multilingual RAG for program requirements, deadlines, documents
- **Product description generation** end-to-end on H200 — image-to-text pipeline (1–5 images → SEO/sales/short copy), 15s batch inference

### 🗣 Speech & Language for Kyrgyz
- **Next-gen Kyrgyz ASR** — **8% WER** on 150h corpus (~2× over the first-gen system)
- **First production Kyrgyz ASR** at UlutSoft — Whisper, 15.43% WER on 73h, serving 100K+ users
- **First production Kyrgyz TTS** — 96% accuracy on 60h
- **First Kyrgyz–Russian MT system** — 1.4M parallel-sentence corpus across 3 domains, **+1.0 BLEU** via LLM post-editing
- **KyRuBench-20K** — released the first domain-balanced KG–RU MT benchmark (20K pairs, 7 systems evaluated)
- **avatar.airun.kg** — first Kyrgyz digital avatar platform, 2,000+ users, 20s generation, MPS/CUDA-optimized
- **Kyrgyz punctuation restoration** — XLM-RoBERTa, F1 **94.9%** ([paper](https://anonymous.4open.science/r/kyrgyz-punctuation-anon-review-6321/README.md))

### 👁 Computer Vision & OCR
- **Visual Search API** — 200K+ images in Qdrant, CLIP embeddings, **96% Precision@K**, sub-second latency
- **Production ID/Passport OCR** — 5 document types (KG/KZ/RU), regex template logic, served via vLLM in Docker, <3s per document
- **National railway monitoring** — YOLOv8 + EasyOCR + tracking, **99% accuracy** in train number recognition

### ⚙️ Production ML
- **SWIFT transfer classification** — 70 categories, 85% accuracy on 600 daily transactions
- **GPT-4o fine-tuning** for real-time comment classification — 1M+ daily comments, 96% accuracy, sub-second API
- **QA system on Mistral 8B** — trained on 1.2M pages, 74% accuracy

## 📑 Research

**Published**
- *Punctuation Restoration for Kyrgyz using Transformers* — HCI-E Eurasian Conference, 2024 *(first author)*

**Under Review (2026)** — first author on 5 of 8
- ACM TALLIP — *Punctuation Restoration for Kyrgyz* (XLM-RoBERTa, F1 94.9%)
- ACL 2026 Workshop MeLLM — *Kyrgyz Text Normalization: Neural vs Rule-Based*
- ICML/ACL 2026 Workshop Blackbox — *How LLMs Encode Emotions Across Languages*
- EMNLP 2026 — *Spectral Collapse Without Collapse: SVD Dynamics of LoRA Adapters for Low-Resource Turkic Languages*
- ACL 2026 MeLLM — *KyRuBench-20K* (co-author)
- ICML 2026 Workshops TAIGR & Mech Interp — *Layered Oversight for Legally-Binding AI* / *Safety Feature Lifecycle via SAEs* (co-author)

## 🎤 Speaking & Community
- Invited speaker at regional tech conferences across Kyrgyzstan & Central Asia (100+ audiences) on AiRUN, low-resource NLP, and applied ML
- Speaker — ICF Kyrgyzstan × Women's Entrepreneurship Day 2025
- Selected participant — **"100 Лидер Айым"** national leadership program
- Mentored 8+ engineers — **100% placement rate** (including Uber)
- 🥈 ASR Hackathon (team lead) • Startup Nation Top 40 finalist

## 🧰 Tech Stack

**LLMs & Agentic** — Fine-tuning, LoRA/QLoRA, RAG (hybrid retrieval + reranking), Tool Use, Dialog State Machines, LLM-as-Judge, Gemma, Mistral, LLaMA, DeepSeek
**NLP & CV** — HuggingFace Transformers, CLIP, YOLOv8, EasyOCR, Whisper, Multi-modal Embeddings
**ML/DL** — PyTorch, TensorFlow, vLLM, Unsloth, DeepSpeed, ONNX, TensorRT
**Infra** — FastAPI, Docker, PostgreSQL, Redis, Elasticsearch, Qdrant, FAISS, CUDA, MPS

## 🌐 Connect

- 🌍 [airun.kg](https://airun.kg)
- 💼 [LinkedIn](https://www.linkedin.com/in/zarina-uvalieva-a31320238)
- 💻 [GitHub](https://github.com/Zarina33)
- 🤗 HuggingFace
- 📧 zarina.uvalievaa@gmail.com

## 🎯 Current Focus

```python
current_focus = {
    "shipping":    ["AiRUN — #1 Kyrgyz LLM", "Bakai Bank agentic RAG", "Sales agent for Bakai Digital"],
    "researching": ["LoRA dynamics for low-resource Turkic", "Cross-lingual emotion encoding in LLMs",
                    "Layered AI oversight in legal domain"],
    "learning":    ["GPU optimization", "Inference performance tuning"],
    "mission":     "Bringing modern AI to Central Asian languages",
}
```

---

<div align="center">
  <img src="https://komarev.com/ghpvc/?username=zarina33&color=blueviolet&style=flat-square&label=Profile+Views" alt="Profile views" />
</div>

<div align="center">
  💫 <i>Let's connect and build something amazing together!</i> 💫
</div>
