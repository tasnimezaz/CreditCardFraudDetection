# # 💳 Credit Card Fraud Detection

This project implements a machine learning-based system to detect fraudulent credit card transactions using a real-world, highly imbalanced dataset. It applies effective data balancing techniques, trains and evaluates multiple classifiers, and saves the best-performing model for real-time predictions.

---

## **Why This Project Matters**

Credit card fraud is a growing threat to global financial systems, costing billions annually. Transactions are often processed in milliseconds, leaving very little time for human intervention. That's why it's critical to have an intelligent system that can flag potential fraud instantly and accurately.

I personally found this project meaningful because I’ve faced suspicious transactions on my own card several times. These incidents inspired me to explore how machine learning could proactively prevent financial fraud and protect users like myself. By building this project, I wanted to learn how real-world fraud detection works and how models can be trained to spot rare but dangerous patterns in data.

---

## **Features**

 **Data Exploration and Cleaning**  
Loaded and inspected the dataset using Pandas. Cleaned nulls, standardized the 'Amount' feature using StandardScaler, and removed the 'Time' column for cleaner training.

 **Feature Scaling and Optimization**  
Normalized transaction values for model consistency and removed duplicate records to avoid data skewing.

⚖️ **Data Balancing Techniques**  
- Undersampling: Randomly selected a subset of non-fraud cases to balance the dataset  
- Oversampling: Used SMOTE to generate synthetic fraud samples and increase representation

📊 **Model Training and Evaluation**  
Trained and evaluated:
- Logistic Regression  
- Decision Tree Classifier  

Measured performance using:
- Accuracy  
- Precision  
- Recall  
- F1 Score  

Each metric was carefully chosen due to the highly imbalanced nature of fraud data.

 **Model Export and Prediction**  
Saved the trained Decision Tree Classifier using joblib. Demonstrated real-time prediction on a sample transaction.

---

## **Tech Stack**

**Frontend (planned)**: Flask or Streamlit for deployment  
**Backend**: Python  
**Machine Learning**: scikit-learn  
**Data Handling**: pandas, NumPy  
**Visualization**: seaborn, matplotlib  
**Imbalanced Data Handling**: SMOTE via imbalanced-learn  
**Model Persistence**: joblib

---

## **Getting Started **

### **1. Clone the Repository**

```bash
git clone https://github.com/your-username/credit-card-fraud-detection.git
cd credit-card-fraud-detection
