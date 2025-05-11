# 🔍 Rock vs Mine Prediction using Logistic Regression

This project uses a simple machine learning model to classify sonar signals as either **Rock** or **Mine**, based on sonar frequency data.

## 📊 Dataset

- **Source**: [UCI Machine Learning Repository - Sonar Dataset](https://archive.ics.uci.edu/ml/datasets/connectionist+bench+(sonar,+mines+vs.+rocks))
- **Features**: 60 numeric values (sonar signal readings).
- **Target**:
  - `R` → Rock
  - `M` → Mine

## 🛠️ Tools & Libraries

- Python 3.x
- `numpy`
- `pandas`
- `scikit-learn` (`train_test_split`, `LogisticRegression`, `accuracy_score`)

## 📁 Project Structure

rock-vs-mine/
├── rock_vs_mine_prediction.ipynb # Main notebook
├── sonar.csv # Dataset file
└── README.md # Project info

## 🚀 How to Run This Project

1. **Clone the repository:**

```bash
git clone https://github.com/TabiaWani/RockVsMinePrediction/blob/master/RockVsMinePrediction.ipynb
cd rock-vs-mine-prediction

Install required libraries:
pip install numpy pandas scikit-learn

Open and run the notebook:
jupyter notebook

Open rock_vs_mine_prediction.ipynb and run all cells.

 ## 🧠 Workflow Overview
Load and explore dataset
Preprocess data (label encoding)
Split into training and testing sets
Train a Logistic Regression model
Evaluate with accuracy score

##✅ Sample Output
Model Accuracy: 87.3%
(Accuracy may vary depending on data split.)


##📌 Future Enhancements
Try other classification models (SVM, RandomForest, etc.)
Add visualizations (confusion matrix, ROC curve)
Implement feature scaling and cross-validation

