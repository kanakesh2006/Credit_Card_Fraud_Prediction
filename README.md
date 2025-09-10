# Credit Card Fraud Prediction

This repository contains an end-to-end **Machine Learning project** for detecting fraudulent credit card transactions. The goal is to build a predictive model that distinguishes between genuine and fraudulent transactions using real-world data.

---

## 📂 Dataset

- **Source**: [Kaggle - Credit Card Fraud Detection Dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud)
- **Description**:
  - Transactions made by European cardholders in September 2013.
  - Contains **284,807 transactions**, of which **492 are frauds** (highly imbalanced dataset).
  - Features:
    - `V1, V2, … V28`: PCA-transformed features (for confidentiality).
    - `Time`: Seconds elapsed between transactions.
    - `Amount`: Transaction amount.
    - `Class`: Target variable (0 = legitimate, 1 = fraud).

---

## 🛠️ Preprocessing

Steps performed before training the ML models:

1. **Loading Dataset**

2. **Checking for Missing Values**

3. **Feature Scaling**

---

## 🤖 Model Training

Different ML models were trained and compared:

- Logistic Regression
- Random Forest
- K-Nearest Neighbors (KNN)

---

## 📊 Evaluation & Results

Evaluation metrics used:

- **Accuracy**
- **Precision**
- **Recall**
- **F1-Score**

### Model Performance Table



### Performance Comparison Plot



### Confusion Matrices



### Accuracy Comparison (Bar Plot)



---

## 📷 Outputs

All generated results and plots are stored inside the `results/` folder. These include:

- Model evaluation tables
- Performance comparison plots
- Confusion matrices for each model
- Accuracy comparison visualizations

---

## 🚀 How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/Credit_Card_Fraud_Prediction.git
   cd Credit_Card_Fraud_Prediction
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

4. Open `Credit_Card_Fraud_Prediction.ipynb` and execute cells.

---

## License

This project is for **educational purposes only**. Dataset © Kaggle & ULB ML Group.

