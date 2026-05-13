# Diabetes Prediction System

A machine learning project that predicts whether a patient is likely to have diabetes based on medical diagnostic measurements. Built using Python and scikit-learn in a Jupyter Notebook environment.

---

## 📌 About the Project

Diabetes is one of the most common chronic diseases worldwide. Early prediction can help in timely diagnosis and treatment. This project uses supervised machine learning on the **Pima Indians Diabetes Dataset** to classify patients as diabetic or non-diabetic based on health indicators.

---

## 🛠️ Tech Stack

| Tool | Purpose |
|---|---|
| Python | Core programming language |
| Pandas | Data loading and manipulation |
| NumPy | Numerical computations |
| Matplotlib / Seaborn | Data visualization |
| Scikit-learn | ML model building and evaluation |
| Jupyter Notebook | Development and experimentation environment |

---

## 📁 Project Structure

```
Diabetes-Prediction-system/
│
├── Diabetes.ipynb      # Main notebook — EDA, model training, evaluation
├── diabetes.csv        # Pima Indians Diabetes Dataset
└── README.md           # Project documentation
```

---

## 📊 Dataset

**Pima Indians Diabetes Dataset** — A well-known medical dataset originally from the National Institute of Diabetes and Digestive and Kidney Diseases.

| Feature | Description |
|---|---|
| Pregnancies | Number of times pregnant |
| Glucose | Plasma glucose concentration |
| BloodPressure | Diastolic blood pressure (mm Hg) |
| SkinThickness | Triceps skin fold thickness (mm) |
| Insulin | 2-hour serum insulin (mu U/ml) |
| BMI | Body mass index |
| DiabetesPedigreeFunction | Diabetes likelihood based on family history |
| Age | Age of the patient |
| Outcome | 1 = Diabetic, 0 = Non-diabetic (Target variable) |

- Total records: **768 patients**
- Target: Binary classification (0 or 1)

---

## 🧠 How It Works

**1. Data Exploration (EDA)**
- Checked dataset shape, data types, and missing values
- Analyzed distribution of each feature
- Visualized correlations between features using heatmaps

**2. Data Preprocessing**
- Handled zero values in medical columns (Glucose, BMI, etc.) that represent missing data
- Scaled features using StandardScaler for better model performance

**3. Model Building**
- Split data into training and testing sets (80/20)
- Trained classification model(s) using scikit-learn

**4. Model Evaluation**
- Evaluated using Accuracy, Precision, Recall, F1 Score
- Confusion Matrix to visualize predictions

---

## 📈 Model Evaluation Metrics

| Metric | Description |
|---|---|
| Accuracy | Overall correct predictions |
| Precision | Out of predicted diabetic, how many actually are |
| Recall | Out of actual diabetic patients, how many were caught |
| F1 Score | Balance between Precision and Recall |
| Confusion Matrix | Breakdown of TP, TN, FP, FN |

---

## ⚙️ Run Locally

**1. Clone the repository**
```bash
git clone https://github.com/shourya512/Diabetes-Prediction-system.git
cd Diabetes-Prediction-system
```

**2. Install dependencies**
```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

**3. Launch the notebook**
```bash
jupyter notebook Diabetes.ipynb
```

---

## 🙋 Author

**Shourya Parashar** — [GitHub](https://github.com/shourya512)
