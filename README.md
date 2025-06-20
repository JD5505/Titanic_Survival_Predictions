
# Titanic Survival Prediction 🚢

This project uses machine learning models to predict passenger survival on the Titanic using the famous [Kaggle Titanic dataset](https://www.kaggle.com/c/titanic).

## 📁 Project Structure

```
titanic-ml/
├── dataset/
│   ├── train.csv
│   ├── test.csv
│   ├── train_processed.csv
│   └── test_processed.csv
├── Logistic_Pred.ipynb
├── knn_pred.ipynb
├── RandomForestPred.ipynb
├── requirements.txt
└── README.md
```

## ✅ Models Implemented

- **Logistic Regression**
- **K-Nearest Neighbors (KNN)**
- **Random Forest Classifier**

Each model was trained and tested after:
- Handling missing values
- Encoding categorical variables (`Sex`, `Embarked`)
- (Optional) Scaling numerical features

## 📊 Dataset

The original data was taken from [Kaggle Titanic Competition](https://www.kaggle.com/c/titanic/data), and it includes:
- `train.csv`: Original training dataset
- `test.csv`: Original test dataset
- `train_processed.csv`: Cleaned and encoded training dataset
- `test_processed.csv`: Cleaned and encoded test dataset

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/titanic-ml.git
   cd titanic-ml
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Open any notebook:
   - `Logistic_Pred.ipynb`
   - `knn_pred.ipynb`
   - `RandomForestPred.ipynb`

4. Run all cells to preprocess data and make predictions.

## 📦 Requirements

See [`requirements.txt`](requirements.txt) for all necessary Python packages.

---

## 📌 Author

**Jivan Divate**  
Machine Learning Beginner | Aspiring AI Engineer

---

## 🏁 Future Ideas

- Try deep learning models (e.g. with PyTorch)
- Use grid search for hyperparameter tuning
- Deploy using Flask/Streamlit
