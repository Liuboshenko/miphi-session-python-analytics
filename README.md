# 📊 Python Data Analysis Project — First Session Assignment (MIPHI)

## 🛠️ Tech Stack

<p align="left">
  <img src="https://img.shields.io/badge/Python_3.10-3776AB?logo=python&logoColor=white" alt="Python 3.10" />
  <img src="https://img.shields.io/badge/Jupyter_Notebook-F37626?logo=jupyter&logoColor=white" alt="Jupyter Notebook" />
  <img src="https://img.shields.io/badge/numpy-013243?logo=numpy&logoColor=white" alt="NumPy" />
  <img src="https://img.shields.io/badge/pandas-150458?logo=pandas&logoColor=white" alt="pandas" />
  <img src="https://img.shields.io/badge/matplotlib-11557C?logo=plotly&logoColor=white" alt="matplotlib" />
  <img src="https://img.shields.io/badge/seaborn-4C72B0?logoColor=white" alt="seaborn" />
  <img src="https://img.shields.io/badge/plotly-3F4F75?logo=plotly&logoColor=white" alt="plotly" />
</p>

## 📖 Project Overview

This project is a first data science assignment analyzing a resume dataset. It demonstrates a complete **Exploratory Data Analysis (EDA)** workflow, including data processing, visualization, and result interpretation.

The analysis is implemented strictly in **Jupyter Notebook** using the following tools and conventions:
- **Languages & Libraries:** Python 3.10, NumPy, Pandas, Matplotlib, Seaborn, Plotly
- **Programming Constructs:** Basic data structures, loops, and functions
- **Visualization Standards:** All graphs include clear titles, axis labels, and are accompanied by concise Markdown conclusions

---

## 🚀 Getting Started

### Prerequisites
- Python 3.10
- Git

### Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/Liuboshenko/miphi-session-python-analytics.git
   cd miphi-session-python-analytics
   ```

2. **Create and activate a virtual environment**
   ```bash
   python3.10 -m venv .venv
   source .venv/bin/activate  # On Windows: .venv\Scripts\activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

---

## 📁 Dataset

### Original Dataset
The original dataset exceeds GitHub's 25 MB file size limit.

**Download Instructions:**
1. Download the dataset: [dst-3.0_16_1_hh_database.tar.gz](https://drive.google.com/uc?export=download&id=1VThUHppeDyjJwPwDRg1GITQkyIpXfK5P)
2. **Verification checksum:**
   ```bash
   md5sum: f01ea25d131f56e8ec96888abee6163c
   ```
3. Extract the archive:
   ```bash
   tar -xzvf ./dst-3.0_16_1_hh_database.tar.gz
   ```

### Processed Dataset
The cleaned and processed dataset is also available for download:

**Download Instructions:**
1. Download: [dst-3.0_16_1_hh_database_after_processing.tar.gz](https://drive.google.com/uc?export=download&id=1BpQVezzFJk_qaLHoSX5VJvnU-DEbu0Qm)
2. **Verification checksum:**
   ```bash
   md5sum: 50b84e456316a191301cab1ceceb1f49
   ```
3. Extract the archive:
   ```bash
   tar -xzvf ./dst-3.0_16_1_hh_database_after_processing.tar.gz
   ```

> **Note:** Both dataset files are included in `.gitignore` to prevent accidental uploads to the repository.

---

## 📊 Visualization Notes

### Interactive Plots
This project uses **Plotly** to create interactive visualizations. Since GitHub cannot render Plotly charts directly, you can view them by opening the HTML files located in the `/plotly_html` directory.

---

## ✅ Project Requirements Checklist

- [x] Notebook follows the provided template structure
- [x] Each task implemented in separate, dedicated cells
- [x] Clean, readable, and well-commented code
- [x] Uses only permitted libraries (Python 3.10, NumPy, Pandas, Matplotlib, Seaborn, Plotly)
- [x] All visualizations include proper titles, axis labels, and Markdown interpretations
- [x] No external tools or unapproved libraries used

---

## 🗂️ Project Structure
```
miphi-session-python-analytics/
├── Python_для_анализа_данных__Итоговыи__проект_Ноутбук-шаблон.ipynb          # Main Jupyter notebook with full analysis
├── requirements.txt        # Project dependencies
├── plotly_html/            # Directory containing interactive Plotly charts
├── .gitignore             # Git ignore file excluding datasets
└── README.md              # Project documentation (this file)
```

---
