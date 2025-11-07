# 🩺 HealthIntel CLI — Python Health Data Tracker

A **command-line health tracking application** built in **Python**, designed to record, analyze, and visualize user health data such as BMI, weight, and category over time.  
It combines **Python fundamentals**, **data structures**, **file handling**, and **data analytics** into one practical, beginner-friendly CLI project.

---

## 📘 Overview

**HealthIntel CLI** helps users log their daily health metrics, automatically calculate BMI, and visualize progress trends.  
All data is stored in a CSV file, analyzed with **Pandas**, and visualized using **Matplotlib** — fully compatible with **Google Colab** or any local Python environment.

---

## 🚀 Features

| Feature | Description |
|----------|-------------|
| 🧭 **Menu-Driven CLI** | Add, View, Analyze, Visualize, Export, or Exit — all from one interface |
| ⚖️ **BMI Calculation** | Calculates BMI and assigns category (Underweight, Healthy, Overweight, Obese) |
| 💾 **Persistent Storage** | Saves all records with timestamps — complete BMI history |
| 🧩 **Input Validation** | Prevents invalid or empty user inputs |
| 📊 **Analytics** | Computes total records, average BMI, and distribution by category |
| 📈 **Visualization** | Generates bar chart (category) and user-specific trend line |
| 📥 **Auto CSV Export** | Automatically downloads updated CSV when exiting Colab |
| 🧱 **Error Handling** | Robust with `try-except` blocks — no crashes |

---

## 🧠 Tech Stack

- **Language:** Python 3  
- **Libraries:**  
  - `pandas` – data analysis  
  - `matplotlib` – visualization  
  - `csv`, `os`, `datetime` – file & system utilities  
  - `google.colab.files` – auto-download for Colab users

---

## ⚙️ Installation & Setup

### 🟢 Run in Google Colab (Recommended)
1. Open [Google Colab](https://colab.research.google.com/).  
2. Create a new notebook.  
3. Paste the full **HealthIntel CLI** code.  
4. Run cells and follow on-screen prompts.

### 💻 Run Locally
1. Install Python 3.x  
2. Install dependencies:
   ```bash
   pip install pandas matplotlib
