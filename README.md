# Hate Speech Detection

## 📌 Overview
This project implements a **Hate Speech Detection** system to classify text data (tweets) into three categories:
- **0** → Hate Speech  
- **1** → Offensive Language  
- **2** → Neutral  

The goal is to explore multiple machine learning algorithms for detecting harmful or inappropriate language, helping to build safer online communication platforms.

---

## 📂 Dataset
- **File**: `hate_speech.csv`  
- **Source**: Public dataset containing tweets labeled as hate speech, offensive, or neutral.  
- **Size**: ~25k samples  
- **Preprocessing**:
  - Lowercasing text
  - Removing punctuation
  - Removing stopwords
  - Lemmatization
  - Balancing dataset via oversampling

---

## 🛠 Tech Stack
- **Language**: Python  
- **Libraries**:
  - `pandas`, `numpy`
  - `matplotlib`, `seaborn`, `wordcloud`
  - `nltk`
  - `scikit-learn`
  - `tensorflow`, `keras` (for preprocessing utilities)

---

## 📊 Models & Results
Three machine learning algorithms were tested:
1. **Logistic Regression**
2. **Decision Tree Classifier**
3. **Random Forest Classifier**

**Best Performance**:  
- **Accuracy**: `90%`
- Metrics were evaluated using a train-test split.

---

## 🚀 How to Run
1. **Clone the repository**
   ```bash
   git clone https://github.com/jhvyas07/Hate-Speech-Detection-Model.git
   cd Hate_Speech
   ```
   
2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Jupyter Notebook**
   ```bash
    jupyter notebook Hate_Speech_Detection.ipynb
   ```
