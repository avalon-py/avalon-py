<h1 align="center">Hoy, I'm Stefan 👋</h1>

<p align="center">
Data Science student @ BINUS University · building at the intersection of ML and quantitative finance
</p>

<p align="center">
<a href="https://stefano-budi.vercel.app">🌐 Portfolio</a> ·
<a href="https://www.linkedin.com/in/stefano-budi">💼 LinkedIn</a> ·
<a href="mailto:stefano.budi@binus.ac.id">✉️ Email</a>
</p>

---

### 🔭 Currently building

- **F1 Laptime Prediction** — predicting lap times from telemetry data (FastF1), the successor to my earlier Monte Carlo F1 race result predictor.
- Continuous-training infrastructure for **Speech2Market** (monthly retrain + automated quality gating).

### 🧠 About me

- B.S. Computer Science, Data Science Specialization Track @ BINUS University (2024–2028)
- Independent study in MIT 15.401 (Finance Theory), Harvard STAT110 (Probability), Stanford CS229 (ML)
- 2nd author on a published paper on dynamic classifier selection for heterogeneous model pools
- Passionate about quantitative finance and end-to-end ML systems — from data pipelines to deployment

---

### 🚀 Featured projects

**[Speech2Market](https://github.com/avalon-py/speech2market)** — End-to-end NLP pipeline predicting SPX/Gold/VIX moves from Fed speeches
- FinBERT embeddings → two-stage sign classifier + magnitude regressor (HistGradientBoosting), validated via paired bootstrap testing (n=2,000)
- Automated daily ETL (GitHub Actions) scraping Fed transcripts, embedding into Supabase, syncing macro/price data
- Monthly continuous training with automated quality gating and FP16 ONNX deployment under a 1GB memory constraint

**F1 Race Result Predictor** — Monte Carlo race simulation with chaos-weighted XGBoost
- 75 years of race data, 20+ temporally-masked recency-weighted features to prevent leakage
- 1,000+ run Monte Carlo layer modeling DNF risk and Safety Car/VSC/Red Flag events
- Beat the grid baseline by 9.1% MAE on the 2025 held-out season, validated via walk-forward backtesting

**Laptop Price Predictor** — End-to-end ensemble ML deployment
- Stacking ensemble (XGBoost, LightGBM, CatBoost → RidgeCV meta-learner) tuned via Optuna
- Self-scraped dataset (BeautifulSoup + Playwright), deployed as a Streamlit app with ~65–75ms P90 latency

**Makan Bergizi Gratis (MBG) Investment Priority Mapping** — Graph-based clustering research
- Spectral clustering with a Laplacian structure to map investment priority across 38 Indonesian provinces
- 15+ derived features from raw government data (BPS, Badan Pangan Nasional), filtered via RFECV
- Validated via Calinski-Harabasz index (3.94 vs. 1.01 random baseline); selected by BINUS's CS faculty as presentation material at PPI BRIDA, presenting to government stakeholders and civil servants

---

### 🛠️ Tech stack

**Languages:** Python, SQL, C, Java, R

**ML / Modeling:** Gradient Boosting (XGBoost, LightGBM, CatBoost), Optuna, PCA/LDA, SVM, Temporal Fusion Transformers, Spectral Clustering

**Transfer Learning:** FinBERT, DINOv2, ConvNeXt, ONNX Runtime

**Data & Deployment:** Pandas, BeautifulSoup, Playwright, GitHub Actions, Supabase, Streamlit, AWS, Git

---

<p align="center"><i>Open to Data Science / ML Engineer internships.</i></p>
