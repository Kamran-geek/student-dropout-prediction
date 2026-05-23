# 🎓 Student Dropout Prediction Using Machine Learning

**Author:** Kamran Shafiq Dar  
**GitHub:** [@Kamran-geek](https://github.com/Kamran-geek)  
**Submitted as:** Self-Made Production — MSc 1 Data Science & Artificial Intelligence Application  
**Institution:** Université Côte d'Azur, Nice, France  
**eCandidat File:** EM57IO52

---

## 📌 Project Overview

Student dropout is one of the most critical challenges in higher education.
This project uses real-world data from the **Open University Learning Analytics
Dataset (OULAD)** to explore whether machine learning can predict — early —
which students are at risk of withdrawing from their course.

The analysis covers the full data science pipeline:
- Data loading and exploration
- Cleaning and preprocessing
- Visualisation and pattern discovery
- ML model training and evaluation (Decision Tree Classifier)
- Results interpretation and reflection

---

## 📂 Repository Structure

student-dropout-prediction/
│
├── student_dropout_analysis.ipynb   ← Main Jupyter Notebook
├── data/
│   └── studentInfo.csv              ← OULAD student dataset
├── images/                          ← Charts exported from notebook
└── requirements.txt                 ← Python dependencies

---

## 📊 Dataset

**Open University Learning Analytics Dataset (OULAD)**  
Source: https://analyse.kmi.open.ac.uk/open_dataset  
File used: `studentInfo.csv` (32,593 students, 12 features)

The dataset contains anonymised demographic and academic information
about students registered on Open University courses between 2013 and 2014.

---

## 🛠️ Tools & Libraries

| Tool | Purpose |
|------|---------|
| Python 3.11 | Core language |
| pandas | Data loading and manipulation |
| matplotlib | Data visualisation |
| seaborn | Statistical charts |
| scikit-learn | Machine learning model |
| Jupyter Notebook / Google Colab | Development environment |

---

## 🔍 Key Questions Explored

1. What is the distribution of student outcomes (Pass / Fail / Withdrawn)?
2. Does age group affect dropout rates?
3. Does previous education level influence outcomes?
4. Can a Decision Tree classifier predict dropout from student profile data?
5. Which features matter most in the prediction?

---

## 📈 Key Findings

*(Updated as notebook sections are completed)*

---

## ▶️ How to Run

**Option 1 — Google Colab (recommended):**  
Click the badge below to open directly in Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Kamran-geek/student-dropout-prediction/blob/main/student_dropout_analysis.ipynb)

**Option 2 — Local:**
```bash
git clone https://github.com/Kamran-geek/student-dropout-prediction
cd student-dropout-prediction
pip install -r requirements.txt
jupyter notebook
```

---

## 📬 Contact

**Kamran Shafiq Dar**  
📧 Kamrandar128@gmail.com  
🔗 [linkedin.com/in/kamran-dar-auramaxweb](https://linkedin.com/in/kamran-dar-auramaxweb)
