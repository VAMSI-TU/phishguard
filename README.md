# phishguard
PHISHGUARD is a machine learning-based web application that detects phishing websites in real time. It analyzes URL structure, HTML content, WHOIS, and DNS data using a Random Forest model to classify websites and provide risk scores through an interactive FastAPI-powered interface.
# 🔐 PHISHGUARD – ML-Based Phishing Detection System

PHISHGUARD is a full-stack machine learning application that detects phishing websites in real time. It analyzes multiple features from URLs, HTML content, WHOIS, and DNS data to classify websites as legitimate or malicious.

---

## 🚀 Features

* 🔍 Real-time phishing detection
* 🧠 Machine learning model (Random Forest)
* 📊 25+ feature extraction (URL, HTML, WHOIS, DNS)
* ⚡ FastAPI backend for high performance
* 🎨 Interactive frontend interface
* 📈 Risk score and confidence output

---

## 🧠 Tech Stack

* **Backend:** Python, FastAPI
* **Machine Learning:** Scikit-learn, Pandas, NumPy
* **Frontend:** HTML, CSS, JavaScript
* **Libraries:** BeautifulSoup, Requests, Python-WHOIS, DNSPython

---

## ⚙️ How It Works

1. User inputs a URL
2. System extracts features (URL, HTML, WHOIS, DNS)
3. Features are converted into a vector
4. Random Forest model predicts result
5. Output is displayed with risk score and confidence

---

## 📁 Project Structure

```
PHISHGUARD/
│
├── backend/
│   ├── main.py
│   ├── feature_extractor.py
│   ├── train_model.py
│   ├── requirements.txt
│   └── models/
│
├── frontend/
│   ├── index.html
│   ├── style.css
│   └── script.js
│
├── dataset/
├── screenshots/
├── report/
├── README.md
├── LICENSE
└── .gitignore
```

---

## ⚙️ Installation & Setup

```bash
git clone https://github.com/your-username/phishguard.git
cd phishguard
pip install -r backend/requirements.txt
uvicorn backend.main:app --reload
```

Open in browser:

```
http://127.0.0.1:8000
```

---

## 📸 Screenshots

(Add your images in /screenshots folder)

```
screenshots/dashboard.png
screenshots/result.png
```

---

## 📊 Output Example

* Prediction: Legitimate / Phishing
* Confidence Score: 0–100%
* Risk Score: 0–100

---

## 🎯 Future Improvements

* 🌐 Browser extension integration
* ☁️ Cloud deployment (Render / AWS)
* 🤖 Deep learning models
* 📡 Real-time phishing dataset updates

---

## 👨‍💻 Author

**Vamsi T U**

---

## 📄 License

This project is licensed under the MIT License.
