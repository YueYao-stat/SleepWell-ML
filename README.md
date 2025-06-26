# SleepWell-ML

**An Interpretable Machine Learning Framework for Sleep Quality Prediction and Visualization**

This repository contains the full source code and interactive tools for my undergraduate thesis project:  
*《基于机器学习与SHAP可解释性分析的睡眠质量预测与交互式应用研究》*
(*Sleep Quality Prediction with Interpretable Machine Learning and Shiny-based Application*)

---

## Project Overview

This project aims to predict individual sleep quality using behavioral and physiological data, with an emphasis on model interpretability and real-world usability.

- Built supervised models (Random Forest, DNN) using a health-related survey dataset.
- Applied SHAP (SHapley Additive exPlanations) to visualize and quantify global/local feature importance.
- Developed an interactive **R Shiny** dashboard for user-friendly prediction and interpretation.

---

## Features

- Data preprocessing and feature engineering (age, heart rate, BMI, stress level, activity)
- Sleep quality classification using machine learning
- SHAP analysis for explainability
- Subgroup analysis (e.g., sleep vs. BMI groups)
- Shiny app for real-time interactive prediction and explanation

---

## Project Structure

```plaintext
├── SleepWell.Rmd            # Main RMarkdown analysis file
├── shiny_app/               # Interactive Shiny app source code
│   ├── ui.R
│   ├── server.R
├── figures/                 # Model results, SHAP plots, correlation heatmaps
├── data/                    # Preprocessed dataset
├── README.md                # Project overview (this file)
