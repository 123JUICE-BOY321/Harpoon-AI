# 🐟 Harpoon AI  
### **Built to catch the phish.**

Harpoon AI is a machine-learning–powered phishing URL detection system designed to identify malicious links with high accuracy. Using modern NLP techniques, hashing vectorization, and multiple ML classifiers, Harpoon AI helps secure your browsing environment by spotting dangerous URLs before they strike.

## 🚀 Features
- Automated URL Classification – Predicts whether a URL is good or malicious
- Multiple ML Models – Logistic Regression, Linear SVM, Naive Bayes, and more
- Hashing Vectorizer Pipeline – Efficient, scalable text input processing
- Performance Metrics – Accuracy, confusion matrix, and classification report
- Visualization Tools – Seaborn and Matplotlib plots for insights
- External Verification – Validates model performance using real PhishTank data

## 📁 Project Structure
HarpoonAI
```
├── harpoon_ai_notebook.ipynb
├── phishing_site_urls.csv
├── verified_online.csv
├── README.md
└── models
```

## 🧠 How It Works
Harpoon AI transforms URLs into numeric vectors using HashingVectorizer, then feeds them into a machine-learning pipeline.

## 🛠 Installation
```
git clone https://github.com/yourusername/HarpoonAI.git
cd HarpoonAI
pip install -r requirements.txt
```

## ▶️ Usage
Run the notebook or import the model.

## 📦 Dataset Sources
Phishing URLs dataset and PhishTank verified URLs.

## 🔮 Future Enhancements
- Deep learning classification
- Browser extension
- API deployment
- Ensemble models

## 🛡️ License
GNU General Public License v3.0
