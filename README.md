# 🔮 PsycheSync // Deep Mind & Vibe Engine
> **Drop the receipts. Decode the human.**  
> Real-time neural psycholinguistics decoding OCEAN profiles, subconscious patterns, and social communication styles directly from unstructured text.

[![Python](https://img.shields.io/badge/Python-3.11+-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com/)
[![Groq LPU](https://img.shields.io/badge/Groq-LPU_Accelerated-f55036?style=for-the-badge)](https://groq.com/)
[![HuggingFace](https://img.shields.io/badge/HuggingFace-Transformers-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)](https://huggingface.co/)
[![License: MIT](https://img.shields.io/badge/License-MIT-purple?style=for-the-badge)](https://opensource.org/licenses/MIT)

---

## ⚡ The Rundown

People leave digital breadcrumbs across everything they write: Discord logs, late-night tweets, cover letters, and messy commit messages. 

**PsycheSync** acts as an autonomous psychological decoder. Instead of relying purely on superficial sentiment tools, PsycheSync channels raw syntax into a hierarchical 3-stage neural pipeline: extracting lexical stats, running latent emotion transformers, and prompting an ultra-low-latency Llama-3.3-70B model to map behavioral profiles with receipts.

---

## 🧬 Diagnostic Output Matrix

| Module | Signal Vector | Extracted Psychological Artifacts |
| :--- | :--- | :--- |
| **🌊 OCEAN Vector** | Big Five Trait Scoring | Scale 1–10 quantitative calibration + contextual quote citations |
| **🗣️ Social Frequency** | Interaction Style | Primary/Secondary drivers (Analytical, Catalyst, Stabilizer, Driver) |
| **🧠 Latent Cognition** | Decision Dynamics | Logic flow, instinctive problem-solving biases, and cognitive strain |
| **🎯 Trait Trajectory** | Strengths & Vulnerabilities | Operational blind spots, collaborative leverage, and strategic career paths |
| **🔬 Raw Sub-Signals** | Linguistic Markers | VADER polarity, transformer emotion distribution, and KeyBERT semantic hubs |

---

## 🛰️ 3-Stage Cascading Intelligence Pipeline

```text
 ┌──────────────────────────────────────────────────────────────┐
 │                      RAW INCOMING TEXT                       │
 └──────────────────────────────┬───────────────────────────────┘
                                │
                                ▼
 ┌──────────────────────────────────────────────────────────────┐
 │ STAGE 01: Classical Surface & Morphological Extraction       │
 │  ├── Rule-based Valence Breakdown (VADER)                    │
 │  ├── Contextual Lexical Polarity (Twitter-RoBERTa)           │
 │  ├── Semantic Kernel & Keyword Anchors (KeyBERT)             │
 │  └── Dependency Graphing & Syntactic Attributes (spaCy)      │
 └──────────────────────────────┬───────────────────────────────┘
                                │
                                ▼
 ┌──────────────────────────────────────────────────────────────┐
 │ STAGE 02: Latent Affect & Semantic Dense Projections         │
 │  ├── 7-Class Emotion Tensor (DistilRoBERTa Emotion Engine)   │
 │  └── 384-Dim Vector Embeddings (all-MiniLM-L6-v2)            │
 └──────────────────────────────┬───────────────────────────────┘
                                │
                                ▼
 ┌──────────────────────────────────────────────────────────────┐
 │ STAGE 03: Inferential Deduction (Groq Hardware Engine)       │
 │  └── Meta-Llama 3.3 70B (Versatile) Synthesis                │
 └──────────────────────────────┬───────────────────────────────┘
                                │
                                ▼
 ┌──────────────────────────────────────────────────────────────┐
 │  Dynamic Telemetry Response Object + Glassmorphism Interface │
 └──────────────────────────────────────────────────────────────┘


🧰 Neural Stack & Frameworks
   Execution Runtime: Python 3.11, FastAPI, Uvicorn ASGI Server

   Lexical & Syntactic Analytics: spaCy (en_core_web_sm), NLTK VADER, KeyBERT

   Deep Transformer Embeddings: Hugging Face transformers, sentence-transformers

   Affect & Emotion Architecture: j-hartmann/emotion-english-distilroberta-base

   Sentiment Modeling: cardiffnlp/twitter-roberta-base-sentiment-latest

  LPU Compute Engine: Groq SDK (llama-3.3-70b-versatile)

  Client Surface: Vanilla ECMAScript, CSS3 Cyber-Glass Interface


🕹️ Quickstart & Local Deployment
1. Initialize Workspace

# Clone the repository
git clone [https://github.com/Khushirajora/PsycheSync.git](https://github.com/Khushirajora/PsycheSync.git)
cd PsycheSync

# Set up virtual environment
python -m venv venv
.\venv\Scripts\Activate.ps1

2. Install Dependencies & Pretrained Weights
  pip install -r requirements.txt
python -m spacy download en_core_web_sm

3. Configure Hardware Secret
  Create a .env configuration file inside backend/:
  GROQ_API_KEY=gsk_your_groq_api_key_here
  
4. Ignite the Backend Core
cd backend
uvicorn main:app --host 127.0.0.1 --port 8000 --reload
Swagger API documentation goes live at: http://127.0.0.1:8000/docs

5. Launch the Client UI
Open a separate terminal window and run:
 cd frontend
python -m http.server 3000
Navigate to http://localhost:3000 to start scanning text.


📡 Gateway Protocol: /analyze
Inbound Query
POST /analyze HTTP/1.1
Host: 127.0.0.1:8000
Content-Type: application/json

{
  "text": "Honestly, debugging distributed consensus algorithms all night wasn't even exhausting—it was genuinely fun. We hit a split-brain edge case, but rewriting our quorum validation logic solved the synchronization lock."
}

Decoded Signal Schema
{
  "ocean": {
    "openness": { "score": 9, "label": "High", "evidence": "Enthusiastic engagement with abstract, complex distributed logic." },
    "conscientiousness": { "score": 8, "label": "High", "evidence": "Methodical decomposition of edge-case concurrency issues." },
    "extraversion": { "score": 3, "label": "Low", "evidence": "Introspective problem-solving orientation." },
    "agreeableness": { "score": 6, "label": "Average", "evidence": "Collaborative 'we' framing without defensive ego." },
    "neuroticism": { "score": 2, "label": "Low", "evidence": "High stress tolerance during system failure scenarios." }
  },
  "communication_style": {
    "primary_style": "analytical",
    "secondary_style": "driver",
    "tone": "objective",
    "description": "Systematic communication that relies on empirical evidence and structured logic."
  },
  "behavioral_insights": {
    "thinking_style": "First-principles engineering logic",
    "decision_making": "Empirical and telemetry-driven",
    "stress_signals": "Hyperfocus on system architecture under pressure"
  },
  "strengths": ["Deep systems thinking", "High autonomy", "Root-cause isolation"],
  "blind_spots": ["May prioritize architectural purity over rapid shipment"],
  "career_fit": ["Distributed Systems Architect", "Security Engineer", "Quantitative Developer"],
  "summary": "High-cognitive autonomy archetype with robust emotional resilience and an analytical communication style.",
  "meta": {
    "word_count": 32,
    "inference_engine": "Groq-LPU-Llama-3.3-70b"
  }
}


