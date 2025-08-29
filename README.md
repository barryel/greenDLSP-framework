# 🌱 GreenDLSP Framework  
Reducing the carbon footprint of deep learning pipelines, developed as part of my MSc thesis project.  

This project extends and builds upon the work in [MariaSL/carbon-tracking](https://github.com/MariaSL/carbon-tracking), adapting it into a more structured framework for comparing the carbon emissions of machine learning and deep learning experiments.

---

## 🚀 Project Overview
- **Goal:** Provide a framework to track and reduce the carbon footprint of ML/DL pipelines.  
- **Approach:**
  1. Measure energy consumption of CPU/GPU during training.  
  2. Estimate carbon footprint using emission factors.  
  3. Benchmark across different frameworks (PySpark, Pandas, Dask, etc).  
  4. Provide insights into sustainable AI practices.  

---

## 📂 Repository Structure
- `notebooks/` → Jupyter notebooks for experiments  
- `src/` → Core framework code (functions, scripts)  
- `reports/` → Visualizations, results, thesis-related documentation  
- `requirements.txt` → Python dependencies  
- `LICENSE` → MIT License  
- `data/` → (not included; see instructions below)  

---

## 📊 Dataset
The dataset used for this research is **not included in this repository** (due to size/privacy).  

👉 To reproduce results:  
- Download the dataset from [insert dataset link/source here].  
- Place the files in the `/data/` folder before running notebooks.  

---

## 🔧 Requirements
Install dependencies with:  
```bash
pip install -r requirements.txt

---

## ▶️ How to Run Locally
1. Clone this repo:  
   ```bash
   git clone https://github.com/barryel/greenDLSP-framework.git
   cd greenDLSP-framework

📊 Example Experiments
Compare CO₂ footprint across:
Pandas vs Dask vs PySpark
Single-machine vs distributed execution
Different model complexities (Logistic Regression, Random Forest, Neural Networks)

---

## 🙏 Acknowledgements
This project builds upon the work in [MariaSL/carbon-tracking](https://github.com/MariaSL/carbon-tracking).  
The original repository inspired the framework, and significant extensions were made as part of my MSc thesis project to adapt it into a more structured benchmarking framework.
