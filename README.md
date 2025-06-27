# 🕌 Islamic Text Classifier (AI/NLP Project)

This project uses machine learning to classify whether a given piece of text is **Islamic** (faith-based) or **Non-Islamic** (general/worldly content). It's the first step in a broader roadmap to build a responsible, explainable **Muslim scholar chatbot** — grounded in verified Islamic knowledge and ethical AI principles.

But the most interesting part for this classification is, how it perform in the grey area. There are many miracles and science based statements in Quran that are stated 1400 years ago. So I put some of those discovery in Islamic where it states in Quran it was stated. And I also put those exact same discoveries without mentioning any Quranic reference. And It still surprisingly did well. But of course there are always rooms to make it better, especially if the dataset is way bigger than this.

## 📌 Project Overview

- **Goal**: Train a text classification model to distinguish Islamic content from non-Islamic content.
- **Approach**: TF-IDF vectorization + Naive Bayes classifier
- **Dataset**: 231 short texts (121 Islamic, 110 Non-Islamic)
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

2. (Optional) Create a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # or use `venv\Scripts\activate` on Windows
```
3. Install dependencies:

```bash
pip install -r requirements.txt
```
4. Run the notebook:

```bash
jupyter notebook classifier.ipynb
```

🌐 Run on Google Colab
Click below to run instantly in the cloud (no installation needed):

Then:

Upload islamic_text_data.csv when prompted

Run all cells in the notebook

📁 Project Structure
```bash
islamic-text-classifier/
├── islamic_text_data.csv        # Input dataset
├── classifier.ipynb             # Jupyter notebook with full code
├── requirements.txt             # Install dependencies
└── README.md                    # Project overview and instructions
```

📊 Results
Label	Precision	Recall	F1-Score
Islamic	1.00	0.89	0.94
Non-Islamic	0.93	1.00	0.97

Overall Accuracy: 96%

Macro Avg F1: 0.95

🔍 Confusion Matrix:
nginx
Copy
Edit
                Predicted
               Islamic  Non-Islamic
Actual Islamic     17         2
Actual Non-Islamic  0        28
The model correctly predicted all Non-Islamic examples and most Islamic ones. Just 2 Islamic texts were misclassified — a good sign of generalization.

🧠 What I Learned
How to process text data using TF-IDF

How Naive Bayes works for real-world text classification

Importance of recall in faith-based models (to avoid missing relevant Islamic content)

How to analyze model performance using precision, recall, F1, and confusion matrix

This project is like building the "eyes" of a future AI system — it learns to see and understand what kind of content it's dealing with before responding.

🧱 Next Steps (AI Research Roadmap)
This is the first step in building an explainable, ethical AI system for Islamic knowledge applications:

🔎 Project 2: Qur’an & Hadith semantic search (QA retrieval)

🧠 Project 3: Islamic intent classifier (Dialogue Act Tagging)

🧩 Project 4: Build a rule-based + ML-based chatbot engine

🤖 Project 5: Fine-tune LLMs on faith-aligned data (e.g., FaithDial)

🤝 Author & Motivation
Built by [Your Name] as part of a personal and academic journey to explore the intersection of:

📜 Faith-based knowledge

🧠 Responsible AI

🧪 Research in NLP and conversational agents

This project is my first practical step toward a Muslim scholar chatbot that is rooted in verified sources and ethical design.

📬 Contact
Want to collaborate, mentor, or discuss faith-aware AI?
📧 Reach out at: your_email@example.com
🌐 LinkedIn: [Your LinkedIn Profile]

🪪 License
This project is open source under the MIT License.
