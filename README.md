# 📰 Fake News Detection Using Reinforcement Learning

This project implements and compares reinforcement learning approaches — **Q-Learning** and **Policy Gradient** — with **Neural Network (NN)** and **LSTM** architectures to accurately classify fake news articles. The models are trained using textual features extracted from real-world datasets and benchmarked based on Accuracy and F1-Score.

## 📌 Project Overview

- ✅ Binary classification of news as **Fake (1)** or **Real (0)**
- 🤖 Algorithms used:
  - Q-Learning with NN and LSTM
  - Policy Gradient with NN and LSTM
- 📈 Metrics: Accuracy, Precision, Recall, F1-Score
- 📊 Comparison of all 4 model configurations using visualizations

---

## 📂 Repository Structure

```bash
Fake-News-Detection-Using-Reinforcement-Learning
├── Musketeers_V3.ipynb              # Main implementation notebook
├── Functions.docx                   # Documentation of functions used
├── Installation & execution.docx    # Setup & run instructions
├── Test_cases.docx                  # Test cases written for functionality verification
├── requirements.txt                 # Required Python libraries
├── Classification_report_*.png      # Model performance reports
├── Comparison_*.png                 # Accuracy & F1-score charts
```

---

## 🚀 How to Run

1. **Clone this repository:**
   ```bash
   git clone https://github.com/Yaswanthkumar1405/Fake-New-Detection-Using-Reinforcement-learning.git
   cd Fake-New-Detection-Using-Reinforcement-learning
   ```

2. **Install required dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Open the notebook:**
   ```bash
   jupyter notebook Musketeers_V3.ipynb
   ```

---

## 📊 Model Performance Summary

| Model Variant              | Accuracy | F1-Score |
|---------------------------|----------|----------|
| Q-Learning + LSTM         | 95.08%   | 94.76%   |
| Policy Gradient + LSTM    | 94.73%   | 94.41%   |
| Q-Learning + NN           | 95.28%   | 94.95%   |
| Policy Gradient + NN      | 95.13%   | 94.81%   |

📌 **Best performance**: Q-Learning with NN  
📌 Models show consistent and robust classification results

---

## 📎 Visual Results

- 🔍 Comparison charts of Accuracy and F1-Score across all models
- 📷 Sample output plots included in `/Comparison_*.png` files

---

## ✅ Features

- Clean implementation with modular functions
- Reinforcement learning integration in NLP pipeline
- Side-by-side model evaluation
- Comprehensive documentation

---

## 📌 Future Improvements

- Expand dataset to include multilingual articles
- Integrate more advanced transformers (e.g., BERT, RoBERTa)
- Deploy as a web app using Flask/Streamlit

---

## 👨‍💻 Author

**Yaswanth Kumar Chaganti**  
📧 yaswanthkumarchaganti@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/yaswanthkumar1405/) | [GitHub](https://github.com/Yaswanthkumar1405)

