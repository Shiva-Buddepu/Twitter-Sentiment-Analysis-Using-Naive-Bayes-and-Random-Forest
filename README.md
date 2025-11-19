# Twitter Sentiment Analysis Using Naive Bayes and Random Forest

This project focuses on performing sentiment analysis on Twitter data using classical machine learning algorithms—**Naive Bayes** and **Random Forest**. The dataset used includes `twitter_training.csv` and `twitter_validation.csv`. The goal is to classify tweets into sentiment categories by applying text preprocessing, exploratory data analysis (EDA), and machine learning modeling.

---

##  Project Workflow

### **1. Import Needed Modules**
- pandas  
- numpy  
- matplotlib / seaborn  
- sklearn modules  
- nltk / spaCy for preprocessing  

---

### **2. Exploratory Data Analysis (EDA)**
- Checking dataset shape  
- Displaying sample records  
- Analyzing sentiment distribution  
- Visualizing data patterns  

---

### **3. Preprocessing**
Performed the following text preprocessing operations:

- Lowercasing  
- Removing special characters  
- Tokenization  
- Stopword removal  
- Lemmatization  
- Converting text into numerical features using TF-IDF / CountVectorizer  

---

### **4. Model Building**
Implemented two machine learning models:

#### ✔ **Naive Bayes Classifier**
- Multinomial Naive Bayes  
- Fast baseline model  
- Good performance for text classification tasks  

#### ✔ **Random Forest Classifier**
- Ensemble-based model  
- Handles non-linear decision boundaries  
- Generally more robust than NB  

---

### **5. Model Evaluation**
Used metrics such as:

- Accuracy  
- Precision  
- Recall  
- F1-score  
- Confusion Matrix  

Also tested and validated performance on the validation dataset.

---

##  Test Model on Validation Data
- Transformed validation tweets with the same preprocessing steps  
- Evaluated both NB and RF models  
- Compared results between models  

---

##  Results
- Naive Bayes: Good baseline accuracy and faster training  
- Random Forest: More robust but computationally heavier  
- Final model comparison included accuracy and F1-score  

---
