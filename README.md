# GEN-AI-PROJECT
# 🚀 AI Resume Generator with NLP

An end-to-end **AI-powered Resume Enhancement System** that improves resumes using Natural Language Processing (NLP) and Generative AI.

This project integrates spell correction, skill suggestions, summary generation, and bullet-point enhancement into a complete automated pipeline.

---

## 📌 Features

- ✅ **Spell Correction**
  - Uses `pyspellchecker` with custom technical vocabulary
  - Preserves:
    - ALL-CAPS
    - CamelCase
    - Technical terms

- ✅ **Skill Suggestion System**
  - Knowledge graph-based recommendations
  - Real-time typing suggestions
  - Smart skill additions

- ✅ **Professional Summary Generator**
  - Powered by **FLAN-T5**
  - Generates concise 2-line summaries

- ✅ **Bullet Point Enhancement**
  - Converts raw job descriptions into:
    - Action-oriented bullets
    - Quantified achievements

- ✅ **End-to-End Resume Pipeline**
  - Fully automated resume processing
  - Combines all modules seamlessly

---

## 🧠 Model Used

- **FLAN-T5 (Google)**
  - Used for:
    - Summary generation
    - Bullet point enhancement
  - Optimized for low memory usage

---

## 📊 Dataset

- Total Records: **100**
- Features: **50**
- Record Types:
  - `full_profile` → 30 rows
  - `spell_correction` → 40 rows
  - `skill_suggestion` → 30 rows

---

## ⚙️ Workflow

1. Install dependencies  
2. Load dataset  
3. Visualize data  
4. Load FLAN-T5 model  
5. Spell correction  
6. Skill suggestion  
7. Summary generation  
8. Bullet enhancement  
9. Full resume pipeline  
10. Evaluation  

---

## 📈 Performance Metrics

| Module                | Metric                     | Score |
|----------------------|---------------------------|-------|
| Spell Correction     | Accuracy                  | 88%   |
| Skill Suggestion     | Coverage @ Top 8          | 85%   |
| Summary Generation   | Human Evaluation          | ~88%  |
| Bullet Enhancement   | Action Verb Usage         | ~92%  |
| Bullet Enhancement   | Quantified Outcomes       | ~76%  |
| End-to-End Pipeline  | Latency (CPU)             | 15–20 sec |

---

## 🛠️ Installation

Run the first cell in the notebook:

```bash
pip install -r requirements.txt
