#  GlucoGuide: Your Diabetes Checkpoint

**GlucoGuide** is a smart, ML-powered health assistant that predicts the likelihood of **diabetes** using real health metrics like Glucose, BMI, Insulin, and more. It is specifically designed to assess diabetes risk in **women**, based on the Pima Indian Diabetes dataset — making it especially useful as a women-focused health awareness tool.

---

##  Try it Now on Google Colab

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Purnika19/GlucoGuide-Your-Diabetes-Checkpoint/blob/main/glucoguide.ipynb)


##  Features

*  **Diabetes prediction** using ML (SVM)
*  **Health summary** for each user
*  Personalized **health tips**
*  Colorful & interactive Gradio interface
*  Clean UI with soft themes and animations

---

##  Machine Learning Model

* **Algorithm Used:** Support Vector Machine (SVM) with Linear Kernel
* **Accuracy:**

  * Training: \~78.66%
  * Testing: \~77.27%

### 📈 Input Features Used:

| Feature                  | Description                 |
| ------------------------ | --------------------------- |
| Pregnancies              | No. of pregnancies          |
| Glucose                  | Glucose concentration       |
| BloodPressure            | Diastolic blood pressure    |
| SkinThickness            | Triceps skin fold thickness |
| Insulin                  | 2-Hour serum insulin        |
| BMI                      | Body mass index             |
| DiabetesPedigreeFunction | Genetic function            |
| Age                      | Age in years                |

---

##  Tech Stack

* Python, NumPy, pandas
* scikit-learn (SVM, train-test split, accuracy)
* StandardScaler for data normalization
* Gradio for GUI

---

##  Run Instructions

1. Open the notebook on Google Colab
2. Install required packages:

   ```python
   !pip install gradio pandas numpy scikit-learn
   ```
3. Run all cells (`Runtime > Run all`)
4. Interact with the UI and get results!


##  How to Use

* Enter your health metrics in the fields
* Click **Predict**
* View prediction + risk score
* Get a health summary + lifestyle tip
* Check tips for daily health improvement

---

##  Sample Inputs

| Parameter                | Example |
| ------------------------ | ------- |
| Pregnancies              | 2       |
| Glucose                  | 120     |
| Blood Pressure           | 80      |
| Skin Thickness           | 20      |
| Insulin                  | 85      |
| BMI                      | 32.5    |
| DiabetesPedigreeFunction | 0.6     |
| Age                      | 29      |

---

##  Outputs Provided

* Diabetes prediction (Yes/No)
* Risk Score (using decision function)
* Personalized tip (e.g. drink more water)
* Saved health summary (can re-view by name)

---

##  Data Source

* Dataset: `diabetes.csv` from Pima Indian Diabetes dataset
* Records: 768 rows, 9 columns
* Note: This dataset includes only **female patients**

---

##  License

This project is open-sourced under the [MIT License](LICENSE).

---

##  Built By

**Purnika** with love for health awareness and tech empowerment.

---

Stay safe. Stay informed.

> *"Your health is your real wealth."*
