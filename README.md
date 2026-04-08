# 🤰 Maternal AI – Pregnancy Risk Prediction

An AI-powered system that predicts **pregnancy risk levels** as **Low, Medium, or High** using machine learning techniques.

---

## 🚀 Overview

Maternal health is a critical aspect of healthcare, and early detection of potential risks during pregnancy can significantly improve outcomes for both mother and baby.

This project leverages **Artificial Intelligence (AI)** to analyze health parameters and classify pregnancy risk levels, enabling **early intervention and better decision-making**.

AI-based models can analyze medical data to identify high-risk cases and support healthcare providers with timely insights ([PMC][1]).

---

## 🎯 Features

* 🔍 Predicts pregnancy risk level: **Low / Medium / High**
* 🤖 Machine Learning-based classification model
* 📊 Uses health parameters such as:

  * Age
  * Blood Pressure (Systolic & Diastolic)
  * Blood Sugar Levels
  * Body Temperature
  * Heart Rate
* ⚡ Fast and accurate predictions
* 💡 Helps in early detection of complications

---

## 🧠 How It Works

The model is trained on a maternal health dataset containing key medical attributes collected from healthcare systems.

Typical input features include:

* Age
* Systolic BP
* Diastolic BP
* Blood Sugar
* Body Temperature
* Heart Rate

The model processes these inputs and outputs a **risk category**, which helps in identifying potential complications early.

Such datasets are commonly collected from hospitals and IoT-based monitoring systems for maternal care ([Kaggle][2]).

---

## 🏗️ Tech Stack

* **Programming Language:** Python
* **Libraries:**

  * Scikit-learn
  * Pandas
  * NumPy
  * Matplotlib / Seaborn
* **Model Type:** Classification (e.g., Random Forest / Logistic Regression / etc.)

---

## 📁 Project Structure

```
Maternal-AI/
│── data/                # Dataset files
│── models/              # Trained ML models
│── notebooks/           # Jupyter notebooks (EDA & training)
│── src/                 # Source code
│── app.py               # Main application file
│── requirements.txt     # Dependencies
│── README.md            # Project documentation
```

---

## ⚙️ Installation & Setup

1. Clone the repository:

```bash
git clone https://github.com/srijana28/Maternal-Ai.git
cd Maternal-Ai
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Run the project:

```bash
python app.py
```

---

## 📊 Model Output

The model classifies pregnancy risk into:

* 🟢 **Low Risk** – Normal pregnancy conditions
* 🟡 **Medium Risk** – Requires monitoring
* 🔴 **High Risk** – Immediate medical attention recommended

---

## 📈 Use Cases

* 🏥 Healthcare providers for early diagnosis
* 👩‍⚕️ Doctors & clinics for patient monitoring
* 📱 Health-tech applications
* 🌍 Rural healthcare systems with limited resources

---

## ⚠️ Disclaimer

This project is intended for **educational and research purposes only**.
It should **not be used as a substitute for professional medical advice**.

---

## 🤝 Contributing

Contributions are welcome!
Feel free to fork the repository and submit a pull request.

---

## 📬 Contact

* GitHub: https://github.com/srijana28
* Project Link: https://github.com/srijana28/Maternal-Ai

---

⭐ If you like this project, consider giving it a star!

[1]: https://pmc.ncbi.nlm.nih.gov/articles/PMC10354509/?utm_source=chatgpt.com "Deep hybrid model for maternal health risk classification in pregnancy: synergy of ANN and random forest - PMC"
[2]: https://www.kaggle.com/datasets/csafrit2/maternal-health-risk-data?utm_source=chatgpt.com "Maternal Health Risk Data"
