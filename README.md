# 🩸 Coronary Heart Disease Prediction using Machine Learning

## 📄 Project Overview
This project aims to predict the **10-year risk of coronary heart disease (CHD)** using **Machine Learning** techniques. The dataset consists of **demographic, behavioral, and medical risk factors**, which are analyzed to train a predictive model. The objective is to enable early diagnosis and timely intervention to reduce **heart disease mortality**.

## 📊 Dataset Information
- **Source:** Framingham Heart Study Dataset
- **Attributes:**
  - Demographic factors: Age, Gender
  - Behavioral factors: Smoking, Alcohol consumption
  - Medical risk factors: Cholesterol levels, Blood pressure, Glucose levels, etc.
- **Target Variable:** 10-year risk of coronary heart disease (Binary: 0 or 1)

## 📚 Approach
### 1. Data Preprocessing
- Handled **missing values** in glucose column using mean imputation.
- Renamed **target variable** (CHD risk) for clarity.
- **Splitting the dataset** into **train (80%) and test (20%)** sets.

### 2. Model Selection & Training
Two models were tested:
#### 🌍 Logistic Regression
- Used as it is well-suited for binary classification.
- Applied **sigmoid function** to determine decision boundary.
- **Max Iterations:** 500 for optimization.
- **Accuracy:** ~85%

#### 📝 Support Vector Machine (SVM)
- Used for handling **high-dimensional data**.
- Applied **linear kernel function** for classification.
- **Accuracy:** ~84%

## 🔮 Performance Evaluation
### Logistic Regression:
- **Confusion Matrix:** ![Insert Image]
- **Classification Report:** Precision, Recall, and F1-score calculated.

### Support Vector Machine:
- **Confusion Matrix:** ![Insert Image]
- **Classification Report:** Model performance metrics.

## 🚀 How to Run the Project
### 1. Clone the Repository
```bash
git clone https://github.com/your-username/heart-disease-prediction.git
cd heart-disease-prediction
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Train the Model
```bash
python train.py
```

### 4. Make Predictions
```bash
python predict.py --input "sample_data.csv"
```

### 5. (Optional) Run Web Interface
```bash
streamlit run app.py
```

## 🔄 Future Improvements
- Implement **Deep Learning models (ANN, CNN)**.
- Deploy the model as a **web-based prediction tool**.
- Optimize **feature selection** for better accuracy.


## 💊 Conclusion
Early identification of heart disease risk factors and **prompt intervention** are crucial for **preventing and managing** this condition. Machine learning provides an efficient way to analyze medical data and assist healthcare professionals in decision-making.


