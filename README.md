
# Titanic Machine Learning Task 🚢

This project is a simple **Machine Learning & Data Analysis** task using the famous Titanic dataset.  
It is designed as a **mock task** to showcase basic ML and data analysis skills, often used for freelancing platforms like Upwork.

---

## 📌 Project Overview
The goal is to predict **passenger survival** on the Titanic using Python.  
The steps include:
1. **Data Loading** – Titanic dataset from Seaborn library.
2. **Exploratory Data Analysis (EDA)** – Understanding dataset structure, checking missing values, and summary statistics.
3. **Data Cleaning** – Handling missing values (e.g., filling Age with median, dropping rows with missing Embarked).
4. **Encoding** – Converting categorical variables (Sex, Embarked) into numeric form using One-Hot Encoding.
5. **Model Training** – Logistic Regression model to predict survival.
6. **Evaluation** – Accuracy, Confusion Matrix, Classification Report, and ROC Curve.

---

## 📊 Visualizations
- Survival rates by gender and passenger class.  
- Confusion matrix showing model performance.  
- ROC curve to evaluate model classification ability.

---

## 🛠️ Technologies Used
- Python (Pandas, NumPy, Seaborn, Matplotlib, Scikit-learn)
- Jupyter Notebook

---

## 📂 Files
- `ML_Titanic_Task.ipynb` → Jupyter Notebook with code and outputs.
- `README.md` → Project documentation.

---

## 📈 Results
- Logistic Regression achieved **~79% accuracy** on test data.  
- The model shows survival is highly correlated with **Gender** and **Passenger Class**.

---

## 🚀 How to Run
1. Clone the repository:  
   ```bash
   git clone https://github.com/your-username/Titanic_ML_Task.git
   cd Titanic_ML_Task
   ```

2. Install dependencies:  
   ```bash
   pip install pandas numpy seaborn matplotlib scikit-learn
   ```

3. Open Jupyter Notebook and run:  
   ```bash
   jupyter notebook ML_Titanic_Task.ipynb
   ```

---

## 🎯 Future Improvements
- Try more ML models (Random Forest, Decision Tree, SVM).  
- Hyperparameter tuning for better accuracy.  
- Deploy as a simple web app using **Streamlit** or **Flask**.

---

## 📌 Author
Created by *Mariam Nasser* – Machine Learning Engineer.
