# 📝 Text Data Classification

This project demonstrates a complete workflow for text data classification using various preprocessing techniques and machine learning models.  

---

## 🚀 Project Steps

1. **Load the Dataset**  
   - Initial inspection of dataset shape: **(72,000, 4)**  

2. **Exploratory Data Analysis (EDA)**  
   - Checked output label ratio  
   - Visualized dataset distribution  
   - Created **word clouds** for better understanding of text data  

3. **Text Preprocessing**  
   - Cleaning text (lowercasing, removing special characters, etc.)  
   - **Lemmatization** applied for normalization  

4. **Feature Engineering**  
   - Converted text into numerical form using **TF-IDF Vectorization**  

5. **Train-Test Split**  
   - Dataset split into training (70%) and testing (30%) sets  

6. **Model Training**  
   - **Multinomial Naive Bayes**  
   - **Bernoulli Naive Bayes**  
   - **Logistic Regression**  

7. **Model Evaluation**  
   - Performance evaluation using accuracy, precision, recall, F1-score  
   - Visualized performance with **histograms**  

8. **Pipeline Creation**  
   - Built an end-to-end machine learning pipeline for reproducibility  

---

📊 Results

Logistic Regression achieved the highest accuracy (0.95), outperforming Naive Bayes classifiers.

Model performance visualizations aid in understanding strengths and weaknesses.
---

## 🛠️ Tech Stack
- **Python**
- **scikit-learn**
- **NLTK / spaCy**
- **Matplotlib / Seaborn / WordCloud**
- **Pandas, NumPy**

---




