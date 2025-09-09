# 📰 Fake News Detection Using NLP

## 📌 Overview
This project applies **Natural Language Processing (NLP)** and **Machine Learning** techniques to detect fake news articles. Using **TF-IDF vectorization** and classifiers like **Logistic Regression** and **Support Vector Machine (SVM)**, the model achieves strong accuracy in distinguishing between real and fake news.

---

## 📂 Project Structure
- **`fake-news-with-tf-idf-0-99385.ipynb`** → Core notebook containing the full pipeline.  

### Notebook Workflow
1. Problem Definition & Dataset Overview  
2. Data Loading & Exploration  
3. Text Preprocessing (cleaning, tokenization, stopword removal)  
4. Feature Extraction with **TF-IDF**  
5. Model Training & Evaluation (Logistic Regression, SVM, etc.)  
6. Performance Analysis (Accuracy, Precision, Recall, F1-score)  
7. Feature Importance & Interpretability  
8. Conclusions & Next Steps  

---

## 📊 Dataset
- Contains labeled news items with text content and target labels.  
- **Labels:** `1 = Fake`, `0 = Real`  
- Used primarily for binary classification tasks.  

---

## 🔧 Methodology

### 1. Preprocessing
- Lowercasing  
- Removing punctuation, special characters, and stopwords  
- Tokenization  

### 2. Feature Engineering
- **TF-IDF Vectorization**: Converts text into weighted numerical features representing term importance.  

### 3. Models
- **Logistic Regression** → Baseline classifier  
- **Support Vector Machine (SVM)** → Captures complex decision boundaries  
- **(Optional)** Random Forest / other classifiers for comparison  

### 4. Evaluation Metrics
- Accuracy  
- Precision  
- Recall  
- F1-score  
- Confusion Matrix  

---

## ✅ Results
- **Accuracy:** ~99% (on test data)  
- Both Logistic Regression and SVM performed well, with Logistic Regression offering interpretability and SVM excelling in classification.  
- Feature importance revealed common linguistic cues for fake vs. real news.  

---

## 🛠️ Tech Stack
- **Python**  
- **Pandas, NumPy** → Data handling  
- **Scikit-learn** → TF-IDF & ML models  
- **Matplotlib, Seaborn** → Visualizations  

---

## 🚀 How to Run
1. Clone this repository:  
   ```bash
   git clone https://github.com/Subhojeet28/Fake-News-Detection-Using-NLP.git
   cd Fake-News-Detection-Using-NLP
