# 📚 Studies — Interactive Learning Repository

## 🚀 Overview
This repository is an **interactive study system** designed to support continuous learning and public examination preparation through **HTML-based study tools**.

Instead of relying solely on static notes, this repository uses **browser-executable interfaces** (HTML + JS) to deliver a more active and structured learning experience.

---

## 🎯 Core Concept

> **Learn by interacting, not just reading.**

All study sessions are executed through:
- Interactive HTML pages
- Structured question flows
- Immediate feedback mechanisms

---

## 🧩 Architecture

This repository is organized into two main layers:

### 1. Study Engine (Logic Layer)

projects/
└── study-tools/
└── quiz-engine/
├── index.html
├── style.css
└── script.js


- Responsible for rendering questions
- Handles interaction and feedback
- Acts as the **core learning interface**

---

### 2. Study Content (Data Layer)

content/
├── law/
├── it/
├── accounting/
└── others/


- Organized by subject/domain
- Contains structured questions and study material
- Designed to be consumed by the study engine

---

## 🗂️ Full Repository Structure


Studies/
│
├── projects/ # Interactive study tools (HTML-based)
│ └── study-tools/
│ └── quiz-engine/
│
├── content/ # Structured study content (questions, topics)
│ ├── law/
│ ├── it/
│ └── accounting/
│
├── notes/ # Complementary summaries and annotations
├── resources/ # External references and materials
└── README.md


---

## 🧠 Study Methodology

This system follows a **practical and iterative learning loop**:

1. **Load Content** → Select subject/topic  
2. **Execute HTML Tool** → Interact with questions  
3. **Immediate Feedback** → Validate understanding  
4. **Error Analysis** → Identify weak points  
5. **Reinforcement** → Repeat with variation  

---

## ⚙️ Design Principles

- **Separation of Concerns**
  - Content ≠ Interface
- **Scalability**
  - One engine, multiple subjects
- **Consistency**
  - Standardized HTML structure
- **Reusability**
  - Modular components
- **Simplicity First**
  - Avoid premature complexity

---

## 🔮 Roadmap

- [ ] Standardize question format (JSON/Markdown)
- [ ] Integrate LLM-generated question pipelines
- [ ] Add exam simulation mode (CEBRASPE-style)
- [ ] Implement scoring and performance tracking
- [ ] Create reusable HTML templates
- [ ] Add tagging and filtering system

---

## 📌 Usage

1. Navigate to the study tool:

projects/study-tools/quiz-engine/index.html

2. Open in your browser
3. Load or connect your study content
4. Start practicing

---

## ⚠️ Important Notes

- HTML files are the **primary interface for study**
- Content should remain **structured and reusable**
- Avoid mixing logic and data in the same file

---

## 👤 Author

Fabio Everton

---

## 📄 License

This repository is intended for **personal and educational use**.
