<div align="center">

# Hi, I'm Daniel Akinbankole 👋

### MSc AI & Data Science · Healthcare AI · Deep Learning · LLM Integration

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)

</div>

I build end-to-end machine learning systems with a focus on healthcare and clinical applications.
My background spans deep learning, computer vision, NLP, EEG signal processing, and applied data
engineering, with hands-on experience in NHS inpatient settings supporting young people with
neurodevelopmental conditions.

---

## Projects

### ⚽ Football Match Predictor
Predicts Premier League match outcomes (Home Win / Draw / Away Win) with calibrated confidence
scores, using an XGBoost classifier trained on 2014–2025 historical data. Features include rolling
form, rest days, head-to-head history, and Elo ratings, all engineered with strict guards against
data leakage. Reached ~51.5% accuracy on a chronological hold-out set (vs. 42.3% for the majority
baseline), with a Streamlit app for browsing fixtures and tracking real-world prediction accuracy
over time. Built as a personal ML engineering exercise, with an honest account of its limitations
(draw prediction, no injury data) documented in the repo.
*(Private repository)*

### 🧠 EEG Sleep Stage Classification
Automated sleep staging from raw EEG signals using a 1D CNN, MNE-Python, and interpretable AI.
Built on the Sleep-EDF Expanded dataset (22,683 epochs, 13 subjects). Achieved balanced accuracy
of 0.718 and Cohen's Kappa of 0.430, a large improvement over a Random Forest baseline. Applied
SHAP and Grad-CAM to explain model decisions — the CNN independently identified sleep spindle
locations without explicit labelling. Clinically motivated by sleep difficulties in children with
autism, ADHD, and epilepsy.
→ [github.com/danielakbank/eeg-sleep-staging](https://github.com/danielakbank/eeg-sleep-staging)

### 🛣️ UK Motorway Asset Density & Maintenance Priority Mapper
Interactive GIS project mapping real M1 and M6 motorway junctions, built around live junction data
fetched from OpenStreetMap via the Overpass API. Builds maintenance priority zones with proper
coordinate reprojection (WGS84 to British National Grid) and runs a spatial join to flag simulated
roadside assets falling within those zones. Demonstrates practical spatial analysis with GeoPandas,
Shapely, and Folium, deployed as an interactive Streamlit app.
→ [Live app](https://uk-motorway-asset-mapper.streamlit.app/) ·
[github.com/danielakbank/uk-motorway-asset-mapper](https://github.com/danielakbank/uk-motorway-asset-mapper)

### 🔨 Tradesman Finder
Search tool for finding tradesmen (plumbers, electricians, carpenters, etc.) near any location,
built on the Google Places API (New). Returns contact details, ratings, and Google Maps links,
with cached searches and session rate limiting to control API costs.
→ [github.com/danielakbank/tradesman-finder](https://github.com/danielakbank/tradesman-finder)

### 🔬 Breast Ultrasound Segmentation (BUSI)
U-Net with ResNet50V2 backbone for lesion detection and segmentation. Validation Dice ~0.71.
Two-phase transfer learning. Deployed on Hugging Face Spaces via Gradio.
→ [Live demo](https://huggingface.co/spaces/daniel-akbank/ultrasound-segmentation) ·
[github.com/danielakbank/BUSI-Segmentation](https://github.com/danielakbank/BUSI-Segmentation)

### 🌊 Underwater Image Enhancement
Compared classical CV preprocessing against a U-Net with EfficientNetB0 encoder on the UIEB
benchmark. PSNR improvement of +3.03dB over the raw baseline, using two-phase transfer learning
and a combined MAE/SSIM loss. Includes an interactive Gradio demo app.
→ [github.com/danielakbank/underwater-image-enhancement](https://github.com/danielakbank/underwater-image-enhancement)

### 🤖 CV Job Matcher
AI-powered job matching platform aggregating live listings from Adzuna, Reed, and Remotive APIs,
scored against uploaded CVs using an LLM-driven engine. Deployed on Streamlit Cloud.
→ [github.com/danielakbank/cv-job-matcher](https://github.com/danielakbank/cv-job-matcher)

### 📊 Children's Social Care Intelligence Dashboard
Python ETL pipeline ingesting 5M+ DfE records across 150+ UK local authorities. Engineered a
custom risk-flag combining re-referral rates and case duration, surfaced through an interactive
Power BI dashboard built for non-technical stakeholders.
→ [github.com/danielakbank/childrens-social-care-analysis](https://github.com/danielakbank/childrens-social-care-analysis)

### 📈 AI Dataset Insight Generator
Streamlit app that turns any uploaded CSV into automated visualisations, statistical summaries,
and plain-English AI insights, powered by Mistral running locally via Ollama for private, cost-free
analysis.
→ [Live demo](https://data-insight-generator-bfktkwkcrhcf5hmcciziam.streamlit.app/) ·
[github.com/danielakbank/Data-Insight-Generator](https://github.com/danielakbank/Data-Insight-Generator)

### 🛍️ Review Sentiment Analyser
End-to-end NLP app classifying product reviews as positive or negative, trained on 500,000+ Amazon
Fine Food reviews. Logistic Regression matched a neural network at 94% accuracy while being faster
and lighter to deploy. Includes cross-category breakdowns, sentiment trends over time, and keyword
extraction.
→ [Live demo](https://danielakbank-review-sentiment-analyser-appapp-lkyajt.streamlit.app/) ·
[github.com/danielakbank/review-sentiment-analyser](https://github.com/danielakbank/review-sentiment-analyser)

### 📱 Flow Breath
Breathing exercise app built with Flutter. Published on the Google Play Store.

---

## Skills

**ML & AI**
![TensorFlow](https://img.shields.io/badge/-TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/-Keras-D00000?style=flat-square&logo=keras&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/-Scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![XGBoost](https://img.shields.io/badge/-XGBoost-006ACC?style=flat-square)
![SHAP](https://img.shields.io/badge/-SHAP%20%2F%20Grad--CAM-4B8BBE?style=flat-square)

1D CNN · U-Net · Transfer Learning · NLP (TF-IDF) · LLM Integration (Mistral/Ollama) ·
EEG Signal Processing (MNE-Python)

**Data Engineering**
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/-Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/-NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![SQL](https://img.shields.io/badge/-SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)

ETL Pipelines · API Integration · Web Scraping

**Geospatial**
![GeoPandas](https://img.shields.io/badge/-GeoPandas-139C5A?style=flat-square)
![Folium](https://img.shields.io/badge/-Folium-77B829?style=flat-square)

Shapely · Coordinate Reference Systems · Spatial Joins

**Visualisation & BI**
![Power BI](https://img.shields.io/badge/-Power_BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)
![Matplotlib](https://img.shields.io/badge/-Matplotlib-11557C?style=flat-square)
![Seaborn](https://img.shields.io/badge/-Seaborn-3776AB?style=flat-square)

DAX

**Software & Deployment**
![Streamlit](https://img.shields.io/badge/-Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![Gradio](https://img.shields.io/badge/-Gradio-F97316?style=flat-square)
![Flask](https://img.shields.io/badge/-Flask-000000?style=flat-square&logo=flask&logoColor=white)
![Flutter](https://img.shields.io/badge/-Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/-Git-F05032?style=flat-square&logo=git&logoColor=white)

Hugging Face Spaces

---

## GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=danielakbank&show_icons=true&theme=default&hide_border=true&count_private=true" alt="GitHub Stats" height="165"/>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=danielakbank&layout=compact&hide_border=true&theme=default" alt="Top Languages" height="165"/>

</div>

---

## Background

- Healthcare Support Worker, Cygnet Health Care CAMHS (2025–present)
- MSc AI & Data Science, University of Hull (2023–2024)
- BSc Computer Science, ESAE University (2018–2021)

---

<div align="center">

## Contact

📧 [akinbankoled@gmail.com](mailto:akinbankoled@gmail.com) &nbsp;·&nbsp;
🔗 [github.com/danielakbank](https://github.com/danielakbank)

</div>
