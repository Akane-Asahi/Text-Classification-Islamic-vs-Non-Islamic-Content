# 🕌 Islamic Text Classifier (AI/NLP Project)

This project uses machine learning to classify whether a given piece of text is **Islamic** (faith-based) or **Non-Islamic** (general/worldly content). It's the first step in a broader roadmap to build a responsible, explainable **Muslim scholar chatbot** — grounded in verified Islamic knowledge and ethical AI principles.

## 📌 Project Overview

- **Goal**: Train a text classification model to distinguish Islamic content from non-Islamic content.
- **Approach**: TF-IDF vectorization + Naive Bayes classifier
- **Dataset**: 200 short texts (121 Islamic, 110 Non-Islamic)
- **Result**: Achieved **96% accuracy** on a diverse validation set

This notebook serves as a foundation for more advanced NLP projects like semantic search, intent classification, and faith-safe chatbots.

---

## 🏃 Getting Started

### 🔧 Requirements

- Python 3.8+
- Jupyter Notebook or Google Colab
- Libraries:
  - pandas
  - scikit-learn
  - matplotlib
  - seaborn

### 💻 Run Locally

1. Clone the repository:
```bash
git clone https://github.com/YOUR_USERNAME/islamic-text-classifier.git
cd islamic-text-classifier
```

(Optional) Create a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # or use `venv\Scripts\activate` on Windows
```
