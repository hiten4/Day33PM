# ML Algorithm Cheat Sheet & Model Comparison (SVM, KNN & More)
---

##  Project Structure

- **Part A** – 8 Algorithm Cheat Sheet + Model Comparison  
- **Part B** – Text Classification using TF-IDF + SVM vs Logistic Regression  
- **Part C** – Interview Preparation (concepts, coding, debugging)  
- **Part D** – AI-assisted Algorithm Selection Guide  

---

##  Dataset

- **Tabular Dataset:** Breast Cancer Dataset (sklearn)  
- **Text Dataset:** 20 Newsgroups (4 categories)  

---

##  Workflow

### Part A:
1. Created an **8-algorithm cheat sheet**  
2. Each algorithm includes:
   - When to use  
   - Key hyperparameters  
   - Pros & Cons  
   - Code snippet  
3. Performed **cross-validation comparison**  
4. Ranked models based on performance  

### Part B:
1. Applied **TF-IDF vectorization** on text data  
2. Built pipelines:
   - Linear SVM  
   - Logistic Regression  
3. Compared performance using classification metrics  

---

##  Algorithms Covered

- Logistic Regression  
- Decision Tree  
- Random Forest  
- SVM  
- KNN  
- Naive Bayes  
- Gradient Boosting  
- AdaBoost  

---

##  Results

- Ensemble models (Random Forest, Gradient Boosting) performed best on tabular data  
- SVM performed best for text classification  
- Logistic Regression provided a strong baseline  

---

##  Key Insights

- **Feature Scaling** is critical for SVM and KNN  
- **SVM** works well in high-dimensional spaces  
- **KNN** suffers from curse of dimensionality  
- **Tree-based models** handle non-linearity effectively  
- **Boosting vs Bagging** shows tradeoff between bias and variance  

---

##  Interview Highlights (Part C)

- High-dimensional data → prefer SVM / Logistic Regression  
- Overfitting in SVM → tune C and gamma  
- Model selection → use cross-validation + statistical tests  

---

##  AI-Augmented Insights (Part D)

### Algorithm Selection Guide:
- Small dataset → Logistic Regression / SVM  
- High-dimensional → SVM  
- Large tabular → Random Forest / Gradient Boosting  
- Interpretability needed → Decision Tree  

### Improvements:
- Added real-world constraints (cost, scaling, latency)  
- Identified edge cases ignored by AI  

---

##  Tools & Libraries

- Python  
- NumPy  
- Pandas  
- Scikit-learn  
- Matplotlib  

---

##  How to Run

1. Open notebooks in Google Colab  
2. Run all cells sequentially  
3. Analyze outputs and model performance  

---

##  Author

**Hiten Mistry**
