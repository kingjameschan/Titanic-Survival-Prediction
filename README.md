# Titanic Survival Prediction

This project is a solution to the [Kaggle Titanic competition](https://www.kaggle.com/competitions/titanic), focusing on predicting passenger survival using machine learning models.

## 📂 Project Structure

```
Titanic-Survival-Prediction/
├── train.csv                 # Training dataset
├── test.csv                  # Test dataset
├── submission.csv            # Your prediction output (optional)
├── titanic_predict.ipynb     # Main notebook with data processing and modeling
├── requirements.txt          # Python dependencies
└── README.md                 # Project documentation
```

## 🚀 Features

- Missing value imputation (Age, Fare, Embarked)
- Categorical encoding (Sex, Embarked)
- Feature engineering: `FamilySize`, `HasCabin`
- Models: Logistic Regression, Support Vector Machine (SVM)
- Output submission file for Kaggle competition

## 📦 Dataset

Please place the original `train.csv` and `test.csv` files in the root directory.  
Alternatively, unzip the provided [`titanic_data.zip`](./titanic_data.zip) if available.

## 🧪 How to Run

1. Install dependencies:

```bash
pip install -r requirements.txt
```

2. Launch the notebook:

```bash
jupyter notebook
```

3. Open `titanic_predict.ipynb` and run all cells.

## 📤 Submission

After generating predictions, export your `submission.csv` in the required Kaggle format:

```
PassengerId,Survived
892,0
893,1
...
```

## 📌 Author

Created by kingjameschan
GitHub: [kingjameschan](https://github.com/kingjameschan)

---