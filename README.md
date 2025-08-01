[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/raskolnikoff/loto6-deeplearning/blob/main/loto6-deeplearning.ipynb)

# Loto6 Deep Learning Prediction

A deep learning experiment for predicting Japan's Loto6 lottery numbers using BiLSTM and Monte Carlo Dropout.  
**No guarantee of winning. Use responsibly.**

---

## 📌 Features
- Automatic fetch of the latest Loto6 results
- 4-layer BiLSTM with L2 regularization + Monte Carlo Dropout
- Regression output with uncertainty estimation (mean ± std)
- 1 main prediction + up to 3 Monte Carlo-based subsets

---

## 🚀 How to Run (Google Colab Recommended)
1. Click the **Open in Colab** badge above to open the notebook `Loto6_DeepLearning.ipynb` located at the root of the `loto6-deeplearning` repository.
2. Run `Runtime → Run all` from the top of the notebook.
3. Check the learning curves and the predicted numbers.

---

## ⚠️ Disclaimer
- This notebook is **for research and educational purposes only**
- No guarantee of winnings, use at your own risk
- Please gamble responsibly

---

## 🏷️ Requirements (Colab default)
- numpy
- pandas
- matplotlib
- tensorflow >= 2.12
- scikit-learn