# 🛡️ Security Layer for AI Hub

## 📄 Overview
This project implements a **Security Layer** for BeamData’s **AI Hub** — an additional protection module designed to detect and prevent unsafe or malicious interactions with LLM-based systems.

The goal is to ensure that user inputs (prompts) are properly classified before being processed by the LLM, preventing **data leakage**, **prompt injection**, or **unauthorized access**.

---

## 🎯 Objectives
- Classify prompts into **SAFE**, **SENSITIVE**, and **MALICIOUS** categories.  
- Strengthen AI Hub’s overall **data security** and **trustworthiness**.  
- Build a foundation for a scalable **AI Security Infrastructure**.

---

## ⚙️ Project Structure

---

## 🧩 How It Works
1. **Input:** User prompts are loaded from a labeled dataset (`prompts.csv`).  
2. **Processing:** Each prompt is analyzed using an **LLM-based classifier**.  
3. **Output:** The model returns a label (SAFE, SENSITIVE, or MALICIOUS).  
4. **Evaluation:** Results are saved and visualized for further analysis.

---

## 📊 Results
- Dataset: 30 labeled prompts (balanced 10 per class).  
- Accuracy: High consistency between predicted and labeled data.  
- Output visualization shows a balanced classification distribution.

*(Optional: add an image here later)*  
```markdown
![Classification Distribution](outputs/classification_chart.png)
🛡️ Security & Ethics

All data used is synthetic — no real or sensitive information is included.
Future work includes testing the model with anonymized BeamData logs under controlled access.
🚀 Next Steps

Integrate output filtering (detect unsafe responses).

Expand dataset with real sanitized AI Hub data.

Build evaluation dashboard for security incidents.
👥 Team
Haitham Alsaloumi
Ghadi Bakhshwain
Danah Al-Sarrani
Rana ALsulami
