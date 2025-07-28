# Harnessing AI for Science–Policy Interface: Plastic LCA Case Study

This repository contains all source code and scripts supporting the research article:

**"Harnessing artificial intelligence-driven approach for science-policy interface: A case study on plastic life-cycle environmental impacts"**

The codebase includes three major components:

## 📂 Structure

### 1. `./llm_extraction` — LLM-based Literature Extraction

- Implements a domain-knowledge-enhanced pipeline using large language models (LLMs) to extract structured information from plastic LCA publications.
- Extracted dimensions include: resin types, upstream process routes, recycling technologies, system boundaries, impact values, etc.
- Outputs structured datasets in standardized formats (`.json`, `.csv`) for downstream analysis.

### 2. `./visualization` — Statistical Analysis & Data Visualization

- Contains scripts to reproduce the figures and tables presented in the manuscript.
- Supports multi-dimensional statistical summaries, information distribution heatmaps, and indicator comparison plots, etc.

### 3. `./shap_analysis` — Explainable ML Attribution

- Implements SHAP (SHapley Additive exPlanations)-based analysis on machine learning models trained to predict environmental impact metrics (GWP).
- Identifies key indirect factors (e.g., data source, uncertainty analysis, availability) contributing to the observed variance across LCA studies.
- Includes visualizations for SHAP value distribution, feature importance ranking, and model evaluation.

## ⚙️ Installation

Python version: `>=3.8`
