# Credit Card Fraud Detection 🕵️‍♂️💳

This project demonstrates a machine learning approach to detect fraudulent credit card transactions using a logistic regression model. It uses an imbalanced dataset and applies under-sampling to address the class imbalance problem.

## 📂 Dataset

- The dataset is highly imbalanced:
  - `0` → Normal transactions
  - `1` → Fraudulent transactions
- Total fraudulent transactions: **492**

> Dataset Source: [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud?resource=download)

## 🧪 Approach

1. **Exploratory Data Analysis**
2. **Handling Imbalance**: 
   - Applied **under-sampling** to create a balanced subset of the data.
3. **Model Training**:
   - Trained a **Logistic Regression** model.
4. **Evaluation**:
   - Evaluated the model using **accuracy**, **confusion matrix**, and **classification report**.

## 📊 Results

While accuracy is not always the best metric in imbalanced datasets, other metrics like precision, recall, and F1-score were also used to ensure robust evaluation.

## 📁 Project Structure

```
credit-card-fraud-detection/
│                   
├── notebooks/
│   └── Credit_Card_Fraud_Detection.ipynb
├── requirements.txt
├── README.md
└── .gitignore
```

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/credit-card-fraud-detection.git
   cd credit-card-fraud-detection
   ```

2. (Optional) Set up a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use: venv\Scripts\activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Open the Jupyter notebook:
   ```bash
   jupyter notebook notebooks/Credit_Card_Fraud_Detection.ipynb
   ```

## ✅ Requirements

- numpy
- pandas
- scikit-learn

> See `requirements.txt` for specific versions.

---


