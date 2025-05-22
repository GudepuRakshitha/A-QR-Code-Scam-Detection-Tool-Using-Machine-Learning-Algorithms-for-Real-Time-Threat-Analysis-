# A QR Code Scam Detection Tool Using Machine Learning Algorithms for Real-Time Threat Analysis

## 📌 Project Overview

This project presents a smart and secure **QR Code Scam Detection Tool** that utilizes **machine learning algorithms** to identify and flag potentially malicious or fraudulent QR codes in real time. The system analyzes encoded URL patterns and associated metadata to detect scams, ensuring user safety during QR interactions.

---

## 🚀 Key Features

- 📷 Scan and extract data from QR codes
- 🧠 Use machine learning models (e.g., Logistic Regression, Random Forest) to detect scam patterns
- 🔐 Flag suspicious URLs and redirection behaviors
- 📊 Real-time analysis with immediate threat feedback
- 🌐 Optional UI using **Streamlit** or **Flask**

---

## 🧠 Technologies Used

- **Python 3.10+**
- **OpenCV** – QR Code detection from images
- **Pandas**, **NumPy** – Data preprocessing
- **Scikit-learn** – ML algorithms (classification)
- **Joblib** – Model serialization
- **Streamlit / Flask** – UI for real-time detection
- **Jupyter Notebook** – Analysis and model training

---

---

## ⚙️ How It Works

1. **Scan QR Code**: Extracts encoded text (usually a URL) using OpenCV or pyzbar.
2. **Preprocess Input**: Extracts URL features like domain, path length, presence of special characters, etc.
3. **Classification**: Uses a trained ML model to classify the URL as Safe or Scam.
4. **Display Result**: Shows threat level with justification (e.g., contains phishing keywords, uses URL shortener, etc.)

---

### ✅ Setup Environment

pip install -r requirements.txt
Run Detection Script: python detector.py --image ./data/sample_qr.png
Launch Streamlit App: streamlit run app.py

## Sample Output 
QR Scan Result:
URL: http://bit.ly/secure-login-page
⚠️ Alert: This QR code redirects to a suspicious domain.
Threat Type: URL Shortener + Phishing Keywords
Prediction: SCAM

## Future Enhancements
🔁 Live camera QR scanning integration

🧠 Deep Learning-based scam detection (e.g., LSTM, BERT for URL)

🌍 Integration with online URL threat intelligence APIs

📱 Android/iOS App using React Native or Flutter

## 👩‍💻 Author
Gudepu Rakshitha Reddy

📧 rakshithareddy1985@gmail.com

🔗 Hugging Face Profile: https://huggingface.co/GudepuRakshithaReddy

🔗 LinkedIn:https://www.linkedin.com/in/gudepu-rakshitha-reddy-516aa72a9/



