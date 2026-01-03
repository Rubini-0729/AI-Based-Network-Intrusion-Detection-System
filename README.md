
# 🔐 AI-Based Network Intrusion Detection System (NIDS)

An AI-powered Network Intrusion Detection System built using **Machine Learning (Random Forest)** and **Streamlit** to detect malicious network traffic in real time.

## 📌 Project Overview

This project analyzes network traffic data and classifies it as:

- ✅ **Benign** – Normal, safe network activity  
- 🚨 **Malicious** – Potential cyberattacks such as DDoS, Port Scans, etc.

The system uses a **Random Forest Classifier** trained on simulated network traffic data inspired by the **CIC-IDS2017 dataset structure**.

## 🧠 Technologies Used
- **Python 3.13**
- **Streamlit** – Web dashboard
- **Pandas & NumPy** – Data processing
- **Scikit-learn** – Machine Learning
- **Matplotlib & Seaborn** – Visualization

## 📂 Project Structure

AI_NIDS_Project/
│
├── nids_main.py # Main Streamlit application
├── README.md # Project documentation
├── requirements.txt # Python dependencies (optional)
## ⚙️ Installation & Setup

### 1️⃣ Install Python
Make sure Python **3.10 or above** is installed.

Check version:
```bash
python --version
2️⃣ Install Required Libraries
Run the following command in terminal or PowerShell:

bash
Copy code
pip install streamlit pandas numpy scikit-learn matplotlib seaborn
▶️ How to Run the Project
Step 1: Navigate to Project Folder
bash
Copy code
cd AI_NIDS_Project
Step 2: Run Streamlit App
bash
Copy code
python -m streamlit run nids_main.py
Step 3: Open in Browser
If browser does not open automatically, manually visit:

arduino
Copy code
http://localhost:8501
