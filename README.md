# 🧠 Logistic Regression Binary Classifier

This project builds a binary classification model using **Logistic Regression** to predict whether a breast tumor is **malignant (1)** or **benign (0)** based on diagnostic features.

---

## 📁 Dataset

**Source**: Breast Cancer Wisconsin (Diagnostic) Dataset  
**Target Variable**: `diagnosis`  
- `M` = Malignant → 1  
- `B` = Benign → 0  

**Features**: 30 numerical columns extracted from digitized images of a breast mass.

---

## 🛠️ Tools & Libraries

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib (optional for ROC curve)

---

## 📊 Project Steps

### 1. Load and Clean Data
- Drop irrelevant columns (`id`, `Unnamed: 32`)
- Encode target (`diagnosis`) into 0 and 1
  
![Screenshot 2025-05-30 181406](https://github.com/user-attachments/assets/7e30df4d-33a1-448e-8a22-c27072a1fe56)

### 2. Train/Test Split & Standardization
- Split the dataset into training and test sets (80/20)
- Standardize features using `StandardScaler`
  ![Screenshot 2025-05-30 181913](https://github.com/user-attachments/assets/850a11ca-3acb-4b7e-a22b-0e00c003fe7b)

### 3. Fit Logistic Regression Model
- Train using `LogisticRegression()` from `sklearn`
  ![Screenshot 2025-05-30 181930](https://github.com/user-attachments/assets/93d1cb8f-ec55-4442-8684-e56c7b62c9d5)

### 4. Evaluate Model
- **Confusion Matrix**
- **Classification Report** (precision, recall, F1-score)
- **ROC-AUC Score**
- ![Screenshot 2025-05-30 181959](https://github.com/user-attachments/assets/6f3297df-b170-48c0-b1d4-244a8a80dc5d)


### 5. Tune Threshold & Explain Sigmoid
- Show how changing the classification threshold affects performance
- Explain the sigmoid function used to output probabilities
![Screenshot 2025-05-30 182017](https://github.com/user-attachments/assets/01b71f52-2474-4ef8-ad4a-7107c84d8094)



