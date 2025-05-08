# Vehicle_Fraud_Insurance_Detection
This project uses machine learning to predict whether a vehicle insurance claim is fraudulent. The goal is to use policy, vehicle and incident features to classify fraudulent activity and help insurance companies detect possible fraud more effectively.

## 📁 Dataset

**Features used:**
- Policy Type
- Make
- Agent Type
- Vehicle Categoty
- Fault
- Age
- Days Policy Claim
- Accident Area
- Age of Vehicle
- ... (and more)

**Target variable:**
- `FraudFound_P` (0 = Yes, 1 = No)

---

## 🛠️ Tools & Libraries

**Language:** Python

**Libraries Used:**
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- XGBoost

---

## 🔍 Steps Performed

1. Data Cleaning & Preprocessing  
   - Handled missing values  
   - Encoded categorical variables using Label Encoding  

2. Exploratory Data Analysis (EDA)  
   - Checked value distributions and relationships

3. Feature Selection  
   - Dropped irrelevant features

4. Train-test split  
   - 80% training / 20% testing

5. Model Building  
   - XGBoost Classifier

6. Threshold Tuning  
   - Applied custom probability threshold (default = 0.3)

7. Evaluation  
   - Accuracy  
   - Confusion Matrix  
   - Classification Report  

---

## 📈 Results

- **XGBoost Classifier Accuracy (Threshold = 0.3):** ~[0.97]%  
- Good balance between **precision** and **recall**
- Model performance improved by adjusting threshold

---

## ✅ Conclusion

This basic fraud detection model shows how claim-related and customer-related data can help predict fraudulent activities. It offers a strong foundation for risk assessment in the insurance industry.

---

## 🔗 Project Status

**Completed** – Future enhancements may include:
- Hyperparameter tuning
- Trying other ensemble methods
- Feature importance analysis
- Model deployment using Streamlit or Flask

Feel free to fork this repo, try the model, or suggest improvements!
