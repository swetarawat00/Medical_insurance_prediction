# 🏥 Medical Insurance Cost Prediction using Linear Regression

This project predicts **medical insurance charges** based on personal and lifestyle features such as:

- Age  
- Sex  
- BMI  
- Number of children  
- Smoking status  
- Region  

The entire workflow is implemented in a **Jupyter Notebook inside VS Code** using Python and Scikit-Learn.

---

## 🔧 Tech Stack

- Python  
- NumPy, Pandas  
- Matplotlib, Seaborn  
- Scikit-Learn  
- Jupyter Notebook  

---

## 📂 Project Structure

medical_insurance_prediction/
│── src/
│ └── medical_insurance_model.ipynb
│── insurance.csv
│── requirements.txt
│── README.md


---

## 📊 Machine Learning Pipeline

### 1️⃣ Data Loading  
- Loaded the dataset using Pandas  
- Checked shape, info, and missing values  

### 2️⃣ Exploratory Data Analysis (EDA)  
- Visualized numerical features (age, BMI, charges)  
- Count plots for categorical variables  
- Summary statistics and dataset insights  

### 3️⃣ Data Preprocessing  
- Converted categorical data into numerical encodings:  
  - `sex`: male → 0, female → 1  
  - `smoker`: yes → 1, no → 0  
  - `region`: southeast → 0, southwest → 1, northeast → 2, northwest → 3  

### 4️⃣ Train-Test Split  
- 80% data → training  
- 20% data → testing  

### 5️⃣ Model Training (Linear Regression)  
- Trained the model using Scikit-Learn  
- Interpreted feature coefficients  

### 6️⃣ Model Evaluation  
Metrics used:  
- **R² Score (Train & Test)**  
- **Mean Absolute Error (MAE)**  
- **Root Mean Squared Error (RMSE)**  

These metrics evaluate prediction accuracy and model reliability.

### 7️⃣ Predictive System  
A custom input example is used to predict medical insurance charges in USD.

---

## 🚀 How to Run the Project

### 1️⃣ Install Dependencies
Run the following command:
pip install -r requirements.txt

### 2️⃣ Open the Notebook
Navigate to:
src/medical_insurance_model.ipynb

### 3️⃣ Run All Cells  
The notebook will perform:
- EDA  
- Preprocessing  
- Model training  
- Model evaluation  
- Final prediction  

---

## 📈 Example Results

- Training R² Score: *(your notebook will show the value)*  
- Testing R² Score: *(your notebook will show the value)*  
- Sample prediction showing estimated medical cost for a given input  

---

## 📝 Author  
👩‍💻 **Sweta Rawat**  
Machine Learning & Backend Developer      

## ⭐ Future Enhancements
- Try advanced models (Random Forest, XGBoost)  
- Hyperparameter tuning  
- Build a Streamlit web UI  
- Deploy the model online (Render / AWS / Heroku)  






