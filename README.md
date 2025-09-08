# 🌐 Multilingual Mobile App Review Analysis  
#### 📊 An insightful analysis of multilingual mobile app reviews by **Vineet**

---

## 🚀 Project Overview  
This project explores a dataset of **multilingual mobile app reviews** collected from Kaggle, focusing on analyzing user sentiments and identifying key trends across various languages and app categories.

---

## 🧱 Analysis Steps  

1. ✅ **Data Loading & Initial Inspection**  
   - Loaded the dataset and examined its structure to identify inconsistencies and missing values.

2. ✅ **Missing Data Handling**  
   - Dropped the column `user_gender` due to a high number of missing values.  
   - Removed rows with missing values in important columns:  
     `review_text`, `rating`, `user_country`, `app_version`.

3. ✅ **Review Language Analysis**  
   - Analyzed language distribution, revealing a **highly diverse multilingual dataset** without a dominant language.

4. ✅ **Sentiment Analysis**  
   - Applied an English-based sentiment model to classify reviews into:  
     - ✔️ Positive  
     - ❌ Negative

5. ✅ **Sentiment Distribution by App and Category**  
   - Explored how sentiment varies across different **apps and app categories**.

6. ✅ **Data Visualization**  
   - Created intuitive visualizations to display:  
     - Sentiment label distribution  
     - Language distribution of reviews  
     - Sentiment trends across app categories

---

## 🔍 Key Findings  

- ✔️ The dataset contained missing values which were successfully addressed during preprocessing.  
- ✔️ Reviews are written in a wide range of languages, demonstrating its **multilingual nature**.  
- ✔️ Sentiment analysis categorized most reviews as either Positive or Negative.  
- ✔️ Sentiment trends varied significantly by **app category** (e.g., Games vs. Finance).

---

## 💡 Insights & Next Steps  

👉 To improve analysis quality:  
- Apply **automatic translation** of reviews into a common language (English) before sentiment analysis.  
- Investigate the missing `user_gender` field to enhance data collection in future projects.  
- Explore advanced multilingual sentiment analysis models (e.g., mBERT, XLM-R) for deeper insights.

---

## 📁 Repository Structure  

```bash
📦 Multilingual-App-Review-Analysis-and-visualization/
│
├── multilingual_review.ipynb     # Jupyter notebook with full analysis pipeline
├── README.md                     # Project overview & steps (this file)
└── data/                         # Folder where dataset can be stored (optional)
