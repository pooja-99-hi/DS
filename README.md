# DS
# DATA SCIENCE INTERNSHIP :

# 🤖 LLM Benchmarks & Capabilities: End-to-End Data Science Project 📊

Welcome to the **LLM Benchmarks & Capabilities Analysis** project! This repository contains four distinct Google Colab automated notebooks covering the entire data lifecycle: from rigorous data engineering and exploratory data analysis (EDA) to predictive machine learning and strategic industry insights. 

The entire suite is optimized for a zero-configuration, **"copy, paste, and run"** workflow using a relational 5-file Large Language Model (LLM) benchmark dataset.

---

## 📂 Repository Structure & Deliverables

| Task | Notebook File Name | Primary Objective | Generated Outputs 📥 |
| :--- | :--- | :--- | :--- |
| **Task 1** | `Task1_Data_Cleaning_Visualization_LLM.ipynb` | Data integration, missing/duplicate handling, and feature distribution profiling. | `cleaned_llm_master.csv`, `dashboard.png`, `params_growth.png`, `pricing_trend.png` |
| **Task 2** | `Task2_Predictive_Modeling_LLM.ipynb` | Supervised learning regression models to predict evaluation scores from architectural features. | `best_model.pkl`, `model_comparison.png`, `feature_importance.png` |
| **Task 3** | `Task3_EDA_LLM.ipynb` | Comprehensive statistical analysis, skewness assessment, and multi-variable correlation mapping. | `eda_dashboard.png`, `correlation_heatmap.png`, `benchmark_trends.png`, `pricing_decline.png` |
| **Task 4** | `Task4_Realworld_LLM_Industry_Analysis.ipynb` | Applied domain analysis tracking ecosystem economics, open-vs-closed paradigms, and scaling efficiency. | `llm_master_analysis.csv`, `capability_predictor.pkl`, `final_dashboard.png` |

---

## 📈 Dataset Architecture

The project seamlessly merges five relational domain CSV files on the structural keys `model_id` and `model_name`:

1.  **`models_catalog.csv`**: Baseline architectural data (parameters, modality, access type, context window, organization details).
2.  **`compute_estimates.csv`**: Computational resource metrics (FLOPs, GPU hours, estimated training costs, energy/CO2 footprints).
3.  **`benchmark_scores.csv`**: Evaluation metrics across various testing paradigms mapping raw model capabilities (`score_pct`).
4.  **`pricing_history.csv`**: Longitudinal API commercial data tracking input/output and blended pricing trends over time.
5.  **`capability_milestones.csv`**: Qualitative tracking of technological breakthrough events categorized by calendar years.

---

## 🚀 Execution & Workflow Instructions

To achieve a true **one-click execution**, follow this exact sequence for each of the four tasks:

### 1️⃣ Set Up in Google Colab
* Navigate to [Google Colab](https://colab.research.google.com).
* Create a new notebook (`File` ➡️ `New notebook`).
* Rename the notebook to match the respective task filename (e.g., `Task1_Data_Cleaning_Visualization_LLM.ipynb`).

### 2️⃣ Code Deployment
* Copy the complete Python script provided for the corresponding task.
* Paste it directly into the first code cell in your Colab workspace. 
* *Optional:* You can separate code segments using standard Colab Markdown blocks for enhanced readability.

### 3️⃣ File Upload & Runtime Trigger
* Execute the code cell (`Shift + Enter` or click the **Play** icon).
* Step 2/3 of each notebook invokes an interactive file picker console.
* Click **"Choose Files"** and select **all 5 CSV files** from your local computer storage simultaneously.
* The processing engines will automatically detect files, perform safe dataset inner/left joins, run pipelines, and output corresponding graphical reports.

### 4️⃣ Automatic Asset Harvesting
* During execution, the scripts dynamically build statistical plots and serialize machine learning models.
* The notebooks automatically trigger a client-side download utility upon completion, exporting all generated `.csv`, `.png`, and `.pkl` assets directly into your default local downloads folder.

---

## 🎓 Submission Framework Guide

If submitting this portfolio for evaluation, internship certification, or academic credit, use the following structured delivery protocol:

```text
📁 Submission_Package/
│
├── 📄 README.md                        <-- This documentation file
│
├── 📁 Source_Notebooks/                <-- Downloaded from Colab (File -> Download -> Download .ipynb)
│   ├── 📓 Task1_Data_Cleaning_Visualization_LLM.ipynb
│   ├── 📓 Task2_Predictive_Modeling_LLM.ipynb
│   ├── 📓 Task3_EDA_LLM.ipynb
│   └── 📓 Task4_Realworld_LLM_Industry_Analysis.ipynb
│
├── 📁 Cleaned_Datasets/                <-- Auto-downloaded data footprints
│   ├── 📊 cleaned_llm_master.csv
│   └── 📊 llm_master_analysis.csv
│
├── 📁 Production_Models/               <-- Serialized model artifacts
│   ├── ⚙️ best_model.pkl
│   └── ⚙️ capability_predictor.pkl
│
└── 📁 Generated_Visuals/               <-- High-resolution analytical graphics
    ├── 🖼️ dashboard.png
    ├── 🖼️ model_comparison.png
    ├── 🖼️ eda_dashboard.png
    └── 🖼️ final_dashboard.png
