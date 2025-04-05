

---

# 🏭 Tata-Steel-Machine-Failure

**Machine Failure Prediction Using XGBoost and Random Forest**

This project focuses on predicting machine failures in the steel manufacturing industry to **minimize downtime** and **improve operational efficiency**. Using operational data such as temperature, rotational speed, torque, and tool wear, we build robust models to anticipate machine failures — enabling proactive maintenance and reducing production losses.

---

## 📂 Project Structure

- **1. Data Preprocessing**
  - Handled missing values
  - Removed outliers
  - Applied data type conversions and normalization where required

- **2. Exploratory Data Analysis (EDA)**
  - Analyzed distributions of key features
  - Visualized correlations and relationships
  - Identified trends related to machine failure

- **3. Feature Engineering & Selection**
  - Dropped irrelevant or redundant columns
  - Selected features with strong predictive power

- **4. Model Building**
  - Trained models using:
    - ✅ Random Forest
    - ✅ XGBoost

- **5. Hyperparameter Tuning**
  - Utilized `GridSearchCV` to fine-tune models for optimal performance

- **6. Model Evaluation**
  - Evaluated using:
    - Accuracy
    - Classification Report
    - Confusion Matrix

- **7. Final Comparison**
  - Compared performance of:
    - Logistic Regression (baseline)
    - Random Forest
    - XGBoost

---

## 🛠️ Technologies Used

- **Languages & Libraries**
  - Python
  - Pandas, NumPy
  - Scikit-learn
  - XGBoost
  - Matplotlib, Seaborn

---

## 📊 Outcome

This project demonstrates a full machine learning workflow — from data preprocessing to model evaluation — on an industry-relevant problem. It showcases:
- Real-world data handling
- Solid model building
- Optimization using GridSearchCV
- Clear performance interpretation

---

## 🚀 Future Work

- Deploy using **FastAPI + Docker** for serving predictions
- Integrate monitoring/logging for real-time inference
- Incorporate anomaly detection techniques

---

