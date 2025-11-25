# Projects

Below are selected analytical and AI-focused projects that demonstrate technical depth, clarity of thinking, and the ability to translate data into insight.

---

🚀 Startup VC Funding Dashboard

Interactive data product analyzing 100k+ global VC funding rounds using Python & Streamlit.

🔍 Problem

Understanding where venture capital is flowing — geographically, by industry, and over time — requires transforming raw funding records into a clear, interactive data product.

🎯 Approach

Cleaned and explored 100k+ funding transactions

Created high-signal visuals for trends, geographies, and industry patterns

Built a dark-mode Streamlit dashboard with filters for:
Year range • Industry • Country • Color theme

Computed metrics such as:
Total VC raised, total rounds, top industries, top countries

📈 Key Insights

The U.S. consistently dominates global VC flow

Software + biotech receive the highest capital concentration

Funding activity surges significantly post-2010

Several mega-round outliers heavily skew total dollars

🖥️ Deliverables

startup_eda.ipynb — full EDA with commentary

app.py — Streamlit dashboard

startup_data/ — cleaned dataset

README.md — full project documentation

🧠 What I Learned

Designing dashboards that reveal real business insights

Managing large datasets and eliminating bias from outliers

Balancing aesthetics with core usability principles in Streamlit

Structuring data products that show both technical and strategic thinking

<img src="/assets/img/Screenshot 2025-11-25 151714.png" alt="VC Investment Trends Dashboard Screenshot" width="100%" style="border-radius: 8px;">

2. 🧠 Travel LLM Recommender

A modular AI system comparing Prompt Engineering, Fine-Tuning (T5), and RAG for travel recommendations.

🔍 Problem

Travel recommendations rely heavily on human reviews and inconsistent descriptions. The goal was to build an AI system that understands user intent and returns high-quality, personalized travel suggestions.

🎯 Approach

Phase 1 — Prompt Engineering

Designed structured prompts for destination ranking

Optimized temperature, tone, and instruction clarity

Built reproducible templates for consistent comparisons

Phase 2 — Fine-Tuning a T5 Model

Cleaned and reformatted 500-entry JSONL dataset

Fine-tuned a T5 model using Hugging Face Trainer + PyTorch

Controlled overfitting by reducing input/output redundancy

Saved final model under /output/final-model/

Phase 3 — Retrieval-Augmented Generation (RAG) (in progress)

Chunked multi-thousand-row travel datasets

Created FAISS index using MiniLM sentence embeddings

Preparing inference pipeline for hybrid retrieval + generation

📈 Key Insights

Prompt engineering delivers fast results but lacks depth

Fine-tuning improves specificity but depends on dataset quality

RAG is promising for grounding recommendations in real data

Travel datasets contain heavy redundancy → must dedupe

🖥️ Deliverables

finetune/prepare_data.py — dataset cleaning

finetune/train.py — T5 fine-tuning script

rag/build_index.py — FAISS vector indexing

rag/query_rag.py — RAG inference logic

README.md — detailed project outline

🧠 What I Learned

How to train transformer models on domain-specific data

How vector search and embeddings power retrieval systems

How to debug large indexing jobs with FAISS

How to compare LLM strategies in a fair, controlled pipeline

3. 🎵 Spotify Data Visualization Project

Exploring global audio trends using seasonal dashboards and genre-based feature analysis.

🔍 Problem

Spotify tracks dozens of audio features per song (danceability, valence, tempo, acousticness, etc.). Understanding trends across seasons and genres requires structured analysis and intuitive visualization.

🎯 Approach

Cleaned Spotify dataset and performed EDA in Python

Built two interactive dashboards:
1. Seasonal Trends — valence, energy, danceability, acousticness
2. Genre Evolution — tempo, speechiness, instrumentalness, liveness

Designed visuals to mirror a professional BI dashboard layout

Extracted patterns across Hip-Hop, Pop, and R&B over multiple years

📈 Key Insights

Hip-hop consistently exhibits highest speechiness + tempo

Pop tracks show strong seasonal shifts in energy and danceability

R&B trends show rising instrumentalness over time

Seasonality strongly correlates with listener mood features (valence)

🖥️ Deliverables

spotify_eda.ipynb — complete EDA with insights

Seasonal trends dashboard

Genre evolution dashboard

Cleaned dataset

🧠 What I Learned

How to design dashboards that communicate music analytics

How to structure multi-visual layouts for non-scroll oversights

How to translate feature engineering into user-friendly charts
