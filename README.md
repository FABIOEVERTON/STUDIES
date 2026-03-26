# 📚 Studies — Interactive Learning System

## 🚀 Overview
This repository contains an interactive, browser-based study system designed to support continuous learning and preparation for public examinations.

The system allows users to:
- Import structured questions
- Complete simulated quizzes
- Track mistakes automatically
- Reinforce knowledge through written (dissertative) answers

All functionality runs entirely in the browser using a single HTML application.

---

## 🎯 Purpose

The main objective of this project is to provide an efficient and structured learning workflow based on:

- Active recall through quizzes
- Immediate feedback
- Error tracking (“error notebook”)
- Written reinforcement of incorrect answers

---

## ⚙️ How It Works

The system follows this cycle:

1. **Import Questions**
   - Paste questions using a structured format
   - The system parses and stores them by discipline

2. **Run Simulations**
   - Answer questions in quiz mode
   - Receive immediate correction after submission

3. **Track Errors**
   - Incorrect answers are automatically stored
   - Each error includes the correct answer and explanation

4. **Reinforce Learning**
   - Answer incorrectly answered questions again
   - Write explanations in your own words to improve retention

---

## 🧩 Features

- Multi-discipline support
- Custom question import (structured text format)
- Quiz engine with pagination
- Automatic error tracking
- Dissertative answer system (error notebook)
- Local data persistence using browser storage
- Search and filtering within error notebook

---

## 🗂️ Repository Structure


studies/
│
├── docs/
│ └── index.html # Main application (deployed via GitHub Pages)
│
├── projects/ # Experimental or future improvements
│
└── README.md


---

## 🌐 Deployment

This project is deployed using **GitHub Pages**.

After deployment, the application can be accessed directly in the browser:


https://your-username.github.io/studies/


---

## ⚠️ Data Persistence

All data is stored locally in the browser using `localStorage`.

Important implications:
- Data is **not shared across devices**
- Clearing browser data will erase your progress
- It is recommended to implement backup/export in future versions

---

## 🔮 Future Improvements

- Data export/import (JSON backup)
- Cloud synchronization (multi-device access)
- Standardized question format (JSON-based)
- Integration with LLMs for automatic question generation
- Performance tracking and analytics

---

## 👤 Author

Fabio Everton

---

## 📄 License

This project is intended for personal and educational use.
