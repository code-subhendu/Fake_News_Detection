# 📰 Fake News Detection System

<div align="center">

![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)
![Flask](https://img.shields.io/badge/Flask-Backend-black.svg)
![TensorFlow](https://img.shields.io/badge/TensorFlow-LSTM%20+%20CNN-orange.svg)
![React](https://img.shields.io/badge/Frontend-React-61DAFB.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)

### 🔍 AI-Powered Multi-Modal Fake News Detection System

Detect fake news using **Raw Text**, **News Articles**, **Online News URLs**, or **Images** with an intelligent evidence verification pipeline.

</div>

---

# 📖 Overview

The Fake News Detection System is an AI-powered web application that helps users identify whether a piece of news is **Real** or **Fake**.

Unlike traditional fake news classifiers, this system first verifies information using trusted evidence sources before using a deep learning model.

The application accepts multiple input formats:

- 📝 Raw text
- 📰 News article
- 🔗 Online news URL
- 🖼️ Image containing news

---

# ✨ Features

✅ Detect fake news from raw text

✅ Detect fake news from copied news articles

✅ Detect fake news from online news links

✅ Detect fake news from uploaded images

✅ OCR-based text extraction from images

✅ Evidence verification layer

✅ Deep Learning (LSTM + CNN)

✅ User-friendly React interface

✅ Fast prediction

---

# 🏗 System Architecture

```
                    User Input
                         │
      ┌──────────────────┼──────────────────┐
      │                  │                  │
   Raw Text         News URL            Image
      │                  │                  │
      └──────────────┬───┴──────────────────┘
                     │
          Evidence Verification Layer
       (News API + Wikipedia Verification)
                     │
          ┌──────────┴──────────┐
          │                     │
     Verified Real?         Not Verified
          │                     │
      Return Result        LSTM + CNN Model
                                │
                          Fake / Real
```

---

# 🚀 Technologies Used

## Frontend

- React.js
- HTML
- CSS
- JavaScript

## Backend

- Flask
- Python

## Machine Learning

- TensorFlow
- Keras
- LSTM
- CNN

## NLP

- NLTK
- Transformers
- OCR
- Tokenizer

## Evidence Verification

- News API
- Wikipedia

---

# 📂 Project Structure

```
Fake_News_Detection/

│
├── backend/
│   ├── app.py
│   ├── model/
│   ├── utils/
│   └── requirements.txt
│
├── frontend/
│   ├── src/
│   ├── public/
│   └── package.json
│
├── models/
│
├── dataset/
│
├── README.md
│
└── LICENSE
```

---

# ⚙ Installation

## Step 1

Clone the repository

```bash
git clone https://github.com/code-subhendu/Fake_News_Detection.git
```

---

## Step 2

Navigate into the project

```bash
cd Fake_News_Detection
```

---

## Step 3

Install Backend Dependencies

```bash
pip install -r requirements.txt
```

---

## Step 4

Install Frontend Dependencies

```bash
cd frontend
npm install
```

---

## Step 5

Run Backend

```bash
python app.py
```

---

## Step 6

Run Frontend

```bash
npm start
```

---

# 👨‍💻 How to Use

## Method 1 — Raw Text

1. Open the application.
2. Select **Text Detection**.
3. Enter the news content.
4. Click **Predict**.
5. View the prediction.

---

## Method 2 — News Article

1. Copy the complete article.
2. Paste into the text area.
3. Click **Predict**.

---

## Method 3 — News URL

1. Open **URL Detection**.
2. Paste the news website link.
3. Click **Verify**.
4. The system extracts the article automatically.
5. Prediction is displayed.

---

## Method 4 — Image Detection

1. Select **Image Detection**.
2. Upload an image.
3. OCR extracts text.
4. Evidence verification begins.
5. Final prediction is displayed.

---

# 🔍 Detection Workflow

```
Input Received
      │
      ▼
Extract Text
      │
      ▼
Evidence Verification
      │
 ┌────┴─────┐
 │          │
Real     Not Verified
 │          │
 ▼          ▼
Return   LSTM + CNN
            │
            ▼
     Fake / Real
```

---

# 📊 Model Information

Model Type:

Hybrid Deep Learning

Architecture:

```
Embedding Layer

↓

LSTM Layer

↓

CNN Layer

↓

Dense Layer

↓

Output
```

---

# 🎯 Supported Inputs

| Input Type | Supported |
|------------|-----------|
| Raw Text | ✅ |
| News Article | ✅ |
| News URL | ✅ |
| Image | ✅ |

---

# 📷 Screenshots

## Home Page

```
(Add Screenshot Here)
```

---

## Prediction Result

```
(Add Screenshot Here)
```

---

## URL Detection

```
(Add Screenshot Here)
```

---

## Image Detection

```
(Add Screenshot Here)
```

---

# 💡 Future Improvements

- Voice News Detection
- Video News Detection
- Explainable AI
- Browser Extension
- Mobile Application
- Multi-language Support

---

---

# 👨‍🎓 Final Year Project

This project was developed as the **Final Year B.Tech Project** in the Department of **Computer Science & Engineering** at **Budge Budge Institute of Technology**.

## 👥 Project Team

This project was collaboratively developed by:

- **Rudranil Guchhait**
- **Subhendu Maiti**
- **Apurba Mondal**
- **Sujan Samanta**
- **Hafijul Mondal**
---

## 🎓 Project Guide

**Prof. (Dr.) Himadri Biswas**

Project Supervisor

Department of Computer Science & Engineering

Budge Budge Institute of Technology

---

## 🤝 Acknowledgement

We sincerely express our heartfelt gratitude to **Prof. (Dr.) Himadri Biswas** for his valuable guidance, continuous encouragement, and expert suggestions throughout the development of this project. His support and mentorship played a vital role in the successful completion of this work.

We also thank the faculty members of the Department of Computer Science & Engineering, Budge Budge Institute of Technology, for providing the necessary resources, technical support, and academic environment that enabled us to complete this project successfully.

---

## 📚 Academic Information

**Project Title:**
**Fake News Detection System using Hybrid Deep Learning (LSTM + CNN) with Evidence Verification**

**Institution:** Budge Budge Institute of Technology

**Department:** Computer Science & Engineering

**Academic Year:** 2025–2026

---

## ⭐ Support

If you found this project useful, please consider giving this repository a **⭐ Star** on GitHub. Your support motivates us to continue improving the project.

---

## 📜 License

This project was developed for **academic and research purposes** as part of the Bachelor of Technology (B.Tech) curriculum.

---

## ❤️ Thank You

Thank you for visiting our project repository!

We hope this project contributes to ongoing research and awareness in the field of **Fake News Detection** and **Artificial Intelligence**.

Happy Coding! 🚀
