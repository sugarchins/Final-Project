# 🏨 Hotel Reviews Sentiment Analysis  

## 📌 What the Project Does  
This project classifies **hotel reviews** as **Positive (1)** or **Negative (0)**. It compares **classical machine learning** models (Logistic Regression, Naïve Bayes, Random Forest, Decision Tree) with **deep learning RNNs** (SimpleRNN, LSTM, GRU, BiLSTM, Stacked LSTM).  

The best model, **GRU**, achieves ~87.5% accuracy and ~0.865 F1-score, showing the effectiveness of sequential deep learning for NLP sentiment tasks.  

---

## 💡 Why the Project is Useful  
- Helps **travelers** quickly see overall sentiment without reading thousands of reviews.  
- Assists **hotel managers** in monitoring guest satisfaction and identifying issues early.  
- Provides a **baseline NLP pipeline** that students, researchers, and developers can adapt for other sentiment classification tasks (restaurants, e-commerce, etc.).  

---

## 🚀 How Users Can Get Started  
1. **Clone the repository**:  
   ```bash
   git clone https://github.com/your-username/hotel-review-sentiment.git
   cd hotel-review-sentiment
   ```
2. **Install dependencies**:  
   ```bash
   pip install -r requirements.txt
   ```
3. **Run preprocessing and training**:  
   ```bash
   python train_sentiment.py
   ```
4. **Test with a new review**:  
   ```python
   from predict import predict_sentiment
   predict_sentiment("The room was clean but the staff was rude.")
   # Output → Negative
   ```

---

## 🆘 Where Users Can Get Help  
- Open an [Issue](https://github.com/your-username/hotel-review-sentiment/issues) on GitHub for bug reports, feature requests, or troubleshooting.  
- Check the [Discussions](https://github.com/your-username/hotel-review-sentiment/discussions) section for community Q&A.  
- Contact the maintainer (see below) for direct support.  

---

## 👥 Who Maintains and Contributes  
- **Maintainer:** Chetna Mishra (GitHub: [your-username])  
- **Contributors:** Based on pull requests and collaborations from the community.  
- Contributions are welcome! Please fork the repo, make changes, and submit a pull request.  

---

## 📊 Results Snapshot  

| Model     | Accuracy | Precision | Recall | F1 | ROC-AUC |
|-----------|---------:|----------:|-------:|---:|--------:|
| Logistic Regression (TF-IDF) | 0.676 | 0.677 | 0.676 | 0.677 | – |
| Naïve Bayes (TF-IDF)         | 0.674 | 0.671 | 0.674 | 0.673 | – |
| **GRU**                      | **0.876** | **0.864** | **0.876** | **0.866** | **0.917** |
| BiLSTM                       | 0.876 | 0.860 | 0.876 | 0.862 | 0.917 |

---

## 📝 License  
This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.  
