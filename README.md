# NYC Restaurant Inspection – Final Project

## Overview
A data story exploring hygiene bias in NYC restaurants using the DOHMH Restaurant Inspection Results dataset (NYC OpenData). The project investigates whether cuisine type and neighborhood predict inspection scores, challenging common assumptions about restaurant cleanliness.

## Files

| File | Purpose |
|------|---------|
| `FinalReport_DeliverMerge.ipynb` | **Main explainer notebook** — full analysis pipeline: data cleaning, EDA, machine learning, visualization rationale, and discussion |
| `WebPage_Visualizations.ipynb` | **Web asset notebook** — generates the interactive and static plots embedded in the website |

## Project Structure

```
├── FinalReport_DeliverMerge.ipynb   # Explainer notebook (behind-the-scenes analysis)
├── WebPage_Visualizations.ipynb     # Plot generation for the website
├── README.md
└── [website/]                       # Self-contained data story for general audiences
```

## Dataset
**NYC DOHMH Restaurant Inspection Results** — published on NYC OpenData, updated daily.  
Covers active restaurants across all 5 boroughs, with inspection scores, letter grades (A/B/C), cuisine type, and geolocation.

## How to Run
1. Install dependencies: `pip install pandas numpy matplotlib seaborn plotly folium scikit-learn`
2. Run `FinalReport_DeliverMerge.ipynb` for the full analysis
3. Run `WebPage_Visualizations.ipynb` to regenerate web-ready plots

## Key Question
> *Do cuisine type and neighborhood predict inspection outcomes — and does the data challenge our hygiene biases?*