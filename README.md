# 2024-28_mdkamranrais_2410030957_5th_3cse23

# Student Feedback Sentiment Analysis System

An internship project that lets students log in, submit course feedback, and have their free-text comments automatically classified as **Positive**, **Negative**, or **Neutral** using Natural Language Processing (NLP) — with results visualized on an analytics dashboard for faculty.

## 📌 Overview

Educational institutions regularly collect student feedback to evaluate teaching quality, course content, and overall learning experience. Manually reading and interpreting large volumes of open-ended feedback is slow and prone to inconsistent judgement.

This project solves that problem with a four-stage pipeline:

1. **Login / Authentication** — student logs in with roll number and password
2. **Feedback Collection** — student submits ratings and free-text comments
3. **Sentiment Analysis Engine** — NLP cleans, tokenizes, and classifies the text with a confidence score
4. **Analytics Dashboard** — aggregated results are rendered as charts and summary statistics

## 🎯 Objectives

- Design a secure login page so only registered students can access the feedback form
- Build a feedback submission module capturing structured ratings and free-text comments
- Apply NLP techniques to automatically classify textual feedback
- Present analyzed results on a dashboard for quick interpretation by faculty/administrators

## 🧰 Tech Stack

| Component | Technology |
|---|---|
| Frontend | HTML5, CSS3, JavaScript |
| Backend | Python (Flask), REST APIs |
| Database | MySQL / SQLite |
| NLP / Sentiment Engine | Python — NLTK / TextBlob / VADER |
| Visualization | Chart.js / Plotly |
| Authentication | Session-based login with hashed password storage |

## 📂 Repository Contents

| File | Description |
|---|---|
| `Internship_Report_Md_Kamran_Rais_2410030957.docx` | Full internship report covering project description, methodology, and outcomes |
| `Student_Feedback_Sentiment_Analysis_Md_Kamran_Rais.pptx` | Project presentation slide deck |
| `OFFER LETTER.pdf` | Internship offer letter issued by Codec Technologies |
| `Internship Certificate.pdf` | Certificate of internship completion |
| `README.md` | This file |

## 📊 Sample Sentiment Classification

| Feedback Text | Predicted Sentiment | Confidence |
|---|---|---|
| "The faculty explained the concepts very clearly." | Positive | 0.86 |
| "The lab sessions were okay, nothing special." | Neutral | 0.52 |
| "The course pace was too fast and confusing." | Negative | 0.79 |

## 🚀 Scope

**In scope now**
- Student login & authentication
- Course-wise ratings + free-text comments
- Automated sentiment classification
- Aggregated dashboard visualization

**Future extensions**
- Multiple departments
- Multilingual feedback support
- Real-time analytics

## 🎓 Internship Details

- **Intern:** Md Kamran Rais
- **Roll No.:** 2410030957
- **Class / Section:** 3CSE23
- **Batch:** 2024–28
- **Institute:** School of Computer Science and Engineering, IILM University, Greater Noida, U.P.
- **Organization:** Codec Technologies
- **Designation:** Full Stack Developer Intern
- **Duration:** 02/10/2026 – 08/10/2026

## 📄 License

This project was developed for academic and internship purposes as part of the B.Tech CSE curriculum at IILM University.
