
# 🫀 Heart Disease Detection

This project implements a **machine learning-based system** to predict the presence of heart disease using patient medical data. The system leverages multiple classification algorithms and evaluates their performance using standard metrics.

---

## 📂 Project Structure
- `heart_disease.ipynb` → Main Jupyter Notebook with code, experiments, and results  
- `data.csv` → Dataset containing patient medical records (age, cholesterol, blood pressure, etc.)  

---

## ⚙️ Methodology
1. **Dataset Preparation**
   - Source: UCI Heart Disease dataset (or equivalent medical dataset).  
   - Features include: age, sex, chest pain type, resting blood pressure, cholesterol, fasting blood sugar, ECG results, maximum heart rate, exercise-induced angina, etc.  
   - Target variable: Presence (1) or absence (0) of heart disease.  

2. **Data Preprocessing**
   - Handling missing values.  
   - Feature scaling and normalization.  
   - Splitting into training and test sets.  

3. **Models Used**
   - Logistic Regression  
   - Decision Trees  
   - Random Forests  
   - K-Nearest Neighbors (KNN)  
   - Support Vector Machine (SVM)  
   - Naive Bayes  

4. **Evaluation Metrics**
   - Accuracy  
   - Precision  
   - Recall  
   - F1-Score  
   - Confusion Matrix  

---

## 📊 Results (Sample)
- Logistic Regression: **85% Accuracy**  
- Random Forest: **90% Accuracy**  
- SVM: **88% Accuracy**  
- KNN: **84% Accuracy**  

The **Random Forest** model achieved the best performance on the dataset.

---

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/heart-disease-detection.git
   cd heart-disease-detection
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook heart_disease.ipynb
   ```

---

## 📌 Key Takeaways
- Machine learning models can provide significant insights for **early detection of heart disease**.  
- Feature importance analysis can help identify the most critical medical indicators.  
- Random Forest showed the best overall results in this study.  

---

## 📧 Contact
Developed by **Hana Ibrahim Elsayed Ibrahim**  
Feel free to connect for collaborations or improvements!  
