# Sonar Mine vs Rock Classification using Machine Learning

## 📌 Overview
This project focuses on classifying underwater objects as either **mines** or **rocks** using sonar signal data. Accurate identification is critical for naval safety, as misclassification can lead to serious risks. The objective is to develop a reliable machine learning model for this binary classification task.

---

## 📊 Dataset
- **Name:** Sonar Dataset  
- **Source:** Kaggle  
- **Total Samples:** 208  
- **Features:** 60 numerical attributes  
- **Classes:**  
  - M → Mine  
  - R → Rock  

Each feature represents the energy of sonar signals reflected at different frequencies.

---

## ⚙️ Methodology
- Data preprocessing and label encoding  
- Train-test split (80:20)  
- Feature scaling using StandardScaler  
- Model training using multiple algorithms:
  - Logistic Regression  
  - K-Nearest Neighbors (KNN)  
  - Decision Tree  
  - Random Forest  
- Model evaluation using:
  - Accuracy  
  - Precision  
  - F1-score  

---

## 📈 Results
- Random Forest and KNN achieved the highest accuracy (~85%)  
- Random Forest demonstrated the best overall performance based on F1-score  
- Ensemble methods showed more consistent and reliable results  

---

## 🎯 Key Insights
- Ensemble models handle complex sonar patterns effectively  
- F1-score provides a more reliable evaluation than accuracy alone  
- Machine learning significantly improves classification performance  

---

## 🚀 Applications
- Naval defense systems  
- Underwater object detection  
- Marine exploration and safety  

---

## 📌 Conclusion
Machine learning models effectively classified sonar signals, with Random Forest providing the most reliable performance. The project demonstrates the potential of ML in improving accuracy and efficiency in safety-critical underwater detection systems.

---

## 🛠️ Technologies Used
- Python  
- NumPy  
- Pandas  
- Scikit-learn  
- Matplotlib  

---

## 📎 Dataset Link
https://www.kaggle.com/datasets/rupakroy/sonarcsv
