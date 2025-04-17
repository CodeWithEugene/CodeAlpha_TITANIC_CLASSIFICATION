🚀 **Thrilled to share my first project as a CodeAlpha Data Science Intern!**

---

## 🚢 Titanic Survival Prediction: Who Survived the Sinking?

I just wrapped up Task 1 of my internship—building a machine learning system to predict survival on the Titanic and uncovering the key factors that determined who made it out alive.

_Spoiler: It wasn’t just luck!_

---

### 🔍 The Challenge

- The goal was to analyze passenger data (891 records) and answer:  
  **What socio-economic, demographic, or situational factors—like class, age, or gender—most influenced survival?**

---

### 💡 My Approach

1. **Data Cleaning & Prep**  
   - Handled missing values: Filled age gaps with mean, embarked with mode.  
   - Dropped irrelevant features (e.g., Cabin with 687 missing entries).  
   - Engineered new features like `AgeGroup` (Children, Adults, etc.) for deeper insights.

2. **Exploratory Analysis (EDA)**  
   - Visualized survival disparities:  
     - **Gender**: 74% of women survived vs. 19% of men.  
     - **Class**: 63% of 1st-class passengers survived vs. 24% in 3rd class.  
     - **Age**: Children had a 65% survival rate, while the elderly faced just 25%.

3. **Model Building**  
   - Trained Logistic Regression, Random Forest, and SVM models.  
   - Evaluated using accuracy, ROC‑AUC, and confusion matrices.

---

### 📊 Key Results

- **Best Model:** Random Forest (82.12% accuracy, ROC‑AUC 0.86)  
- **Top Survival Factors:**  
  1. **Gender:** Women prioritized in lifeboat access.  
  2. **Class:** Wealthier passengers had higher survival rates.  
  3. **Age:** Children evacuated first; elderly faced challenges.

---

_Curious about the code or my approach? Let’s chat!_ 📊
