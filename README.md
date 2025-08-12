# earnings-call-sentiment-analysis
Machine Learning project analysing prosodic features from earnings call audio to predict market sentiment.

# Earnings Call Prosodic Feature Analysis for Market Sentiment

## 📌 Project Overview
This project analyzes prosodic features from corporate earnings call audio recordings to uncover patterns in vocal tone, pitch, intensity, speech rate, and hesitations.  
The goal is to predict **market sentiment** based on executives' vocal delivery patterns, which may reflect confidence, stress, or uncertainty.

## 🎯 Objectives
- Extract prosodic features (pitch, jitter, shimmer, HNR, speech rate, hesitations, etc.) from audio.
- Perform exploratory data analysis to identify patterns in speech delivery.
- Train a machine learning model to predict sentiment or market impact.
- Visualize trends in vocal tone across the earnings call timeline.

## 🛠️ Tech Stack
- **Python**
- `librosa`, `praat-parselmouth`, `pandas`, `numpy`, `matplotlib`, `seaborn`
- `scikit-learn` for model training
- `Jupyter Notebooks` for experimentation

## 📂 Repository Structure
- `audio/` → raw audio & extracted features
- `transcripts/` → audio transcripts
- `src/` → Python scripts for reproducibility
- `models/` → saved ML models

## 🚀 How to Run
1. Clone the repo:
   ```bash
   git clone https://github.com/yourusername/earnings-call-sentiment-analysis.git
   cd earnings-call-sentiment-analysis

