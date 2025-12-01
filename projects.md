# Projects

Below are selected analytical and AI-focused projects that demonstrate technical depth, clarity of thinking, and the ability to translate data into insight.

---

## <a name="startup-vc-funding-dashboard"></a> 🚀 Startup VC Funding Dashboard

<img src="/assets/img/Screenshot 2025-11-25 151714.png" alt="VC Investment Trends Dashboard Screenshot" width="100%" style="border-radius: 8px;">

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


## <a name="travel-llm-recommender"></a> 🧠 Travel LLM Recommender


<img src="/assets/img/Screenshot 2025-12-01 002814.png" width="100%" style="border-radius:8px; margin-bottom:20px;">

A smart, modular recommendation system that explores three major techniques for building a travel assistant using Large Language Models:

- 🔹 Prompt Engineering  
- 🔹 Fine-Tuning a T5 Transformer  
- 🔹 Retrieval-Augmented Generation (RAG) *(in progress)*  

**What’s done:**
- Built structured travel recommendation prompts  
- Fine-tuned a T5 model with a curated dataset
- Performed preprocessing + EDA using TripAdvisor and Europe travel sources

**Tech Used:** Python · Hugging Face · LangChain · FAISS · PyTorch


## <a name="spotify-data-visualization-project"></a> 🎵 Spotify Data Visualization Project

<img src="/assets/img/Screenshot 2025-11-30 210120.png" width="100%" style="border-radius:8px;">

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

