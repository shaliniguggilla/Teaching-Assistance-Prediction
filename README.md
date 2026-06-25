# 🎓 Teaching Assistant Performance Prediction

## 📌 Project Overview

The Teaching Assistant Performance Prediction project aims to predict the performance of teaching assistants based on various factors such as English proficiency, course instructor, course, semester, and class size. This is a multiclass classification problem where the target variable represents the teaching performance as Low, Medium, or High. The project demonstrates the complete machine learning workflow, including data preprocessing, exploratory data analysis (EDA), model training, evaluation, and performance comparison.

---

## 🎯 Problem Statement

Predict the teaching performance of a teaching assistant using historical evaluation data.

---

## 📊 Dataset Information

- **Dataset:** Teaching Assistant Evaluation (TAE)
- **Source:** UCI Machine Learning Repository
- **Records:** 151
- **Features:** 5
- **Target Classes:** 3

### Features

| Feature | Description |
|----------|-------------|
| Native_English_Speaker | Whether the teaching assistant is a native English speaker (1 = Yes, 2 = No) |
| Course_Instructor | Unique instructor ID |
| Course | Course ID |
| Semester | 1 = Summer, 2 = Regular |
| Class_Size | Number of students in the class |
| Performance | Target Variable (1 = Low, 2 = Medium, 3 = High) |

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📈 Exploratory Data Analysis (EDA)

The following analyses were performed:

- Dataset inspection
- Data type verification
- Missing value analysis
- Statistical summary
- Class distribution analysis
- Histograms
- Count plots
- Box plots
- Feature relationship analysis

> Note: A correlation heatmap was not used because most features are categorical variables encoded as integers, making Pearson correlation less meaningful.

---

## 🤖 Machine Learning Workflow

1. Import libraries
2. Load dataset
3. Rename columns
4. Data preprocessing
5. Exploratory Data Analysis (EDA)
6. Split data into training and testing sets
7. Train classification model
8. Evaluate model performance
9. Compare evaluation metrics

---

## 📊 Model Used

- Random Forest Classifier

---

## 📈 Model Evaluation

### Classification Report

| Class | Precision | Recall | F1-Score |
|--------|----------:|--------:|----------:|
| Low Performance | 0.77 | 0.91 | 0.83 |
| Medium Performance | 0.70 | 0.64 | 0.67 |
| High Performance | 0.62 | 0.56 | 0.59 |

### Overall Performance

- **Accuracy:** 71%
- **Weighted Precision:** 70%
- **Weighted Recall:** 71%
- **Weighted F1-Score:** 70%

---

## 📌 Key Insights

- The model achieved an overall accuracy of **71%**.
- Low-performance teaching assistants were identified with the highest recall (91%).
- Medium-performance predictions were reasonably accurate.
- High-performance teaching assistants were comparatively more difficult to classify.
- Class size alone was not a strong predictor of teaching performance.

---

## 📂 Project Structure

```
Teaching-Assistant-Performance-Prediction/
│
├── data/
│   └── tae.csv
│
├── notebooks/
│   └── Teaching_Assistant_Prediction.ipynb
│
├── models/
│   └── random_forest_model.pkl
│
├── README.md
└── requirements.txt
```

---

## 🚀 How to Run

### Clone Repository

```bash
git clone https://github.com/shaliniguggilla/Teaching-Assistant-Performance-Prediction.git
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run the Notebook

```bash
jupyter notebook
```

---

## 📦 Required Libraries

```text
pandas
numpy
matplotlib
seaborn
scikit-learn
```

Install them using:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

---

## 🎯 Future Improvements

- Hyperparameter tuning using GridSearchCV
- Compare multiple machine learning algorithms
- Feature selection techniques
- Cross-validation
- Build a Streamlit web application for deployment

---

## 📚 Learning Outcomes

- Data preprocessing
- Exploratory Data Analysis
- Multiclass Classification
- Random Forest Classifier
- Model Evaluation
- Precision, Recall, F1-Score
- Machine Learning Workflow

---

## 👩‍💻 Author

**Shalini Guggilla**

Aspiring Data Scientist | Machine Learning Enthusiast

GitHub: https://github.com/shaliniguggilla
