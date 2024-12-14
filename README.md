# 🧠 **Intent Classification for Text Queries**

This project implements **Intent Classification** techniques to identify the purpose or intent behind user text queries. This is a fundamental task in **Natural Language Processing (NLP)** with applications ranging from virtual assistants to customer support systems and search engines.

---

## 📂 Dataset

The dataset includes labeled text queries, each associated with an intent category such as:
- 💳 **Financial Transactions** (e.g., "Why was my card declined?")
- 🔄 **Transfers** (e.g., "How do I transfer money to another account?")
- ❓ **Random Queries** (e.g. "Who made you?", "I know you're a bot")

Data preprocessing involves:
- Tokenization
- Lemmatization
- Stop-word removal

---

## 🎯 Objective

To classify user input into predefined intent categories with high accuracy. Key goals include:
- Building and evaluating **machine learning models** for classification.
- Analyzing the impact of **text preprocessing** techniques on performance.
- Comparing the results of various **algorithms** like SVM, Naive Bayes, and Neural Networks.

---

## ⚙️ Approach

### 🔄 Data Preparation
1. **Preprocessing Steps:**
   - Removed noise, punctuation, and stop-words.
   - Applied stemming/lemmatization for word normalization.

2. **Feature Extraction:**
   - Used **TF-IDF vectors** to represent text numerically.
   - Experimented with **word embeddings** for semantic representation.

### 🛠️ Models
- **Baseline Model:** Random classifier.
- Naive Bayes classifier with bag-of-words.
- **Models to compare:**
  - TF-IDF Classifier.  
  - Naive Bayes Classifier.
 
---

## 🌟 Results

### Performance Insights
- **Baseline Model (Random Classifier):** As it was expected, increasing the number of categories decreases it's accuracy.
- **TF-IDF Classifier:** Reached a decent accuracy, although it requires a long time to train.
- ⭐ **Naive Bayes:** Best accuracy of the three with a short training time.

---

## 🔮 Future Improvements

- **Expanded Dataset:** Incorporate more diverse and multilingual queries.
- **Context Awareness:** Leverage sequence models like LSTMs or Transformers.
- **Real-Time Deployment:** Implement in a live environment for continuous learning and feedback.

