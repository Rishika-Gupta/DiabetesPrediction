#  Diabetes Prediction using Machine Learning

This project predicts whether a person is diabetic or not using machine learning. It is built using Python in Google Colab and leverages the PIMA Indian Diabetes dataset. The notebook includes data preprocessing, visualization, model training, and evaluation.

##  Dataset

- **Dataset**: PIMA Indian Diabetes Dataset
- **Source**: [Kaggle / UCI Repository](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)
- **Features**:
  - Pregnancies
  - Glucose
  - Blood Pressure
  - Skin Thickness
  - Insulin
  - BMI
  - Diabetes Pedigree Function
  - Age
  - Outcome (Target: 1 = Diabetic, 0 = Non-Diabetic)

##  Technologies Used

- Python
- Google Colab
- NumPy, Pandas – Data manipulation
- Matplotlib, Seaborn – Visualization
- Scikit-learn – Machine Learning modeling and evaluation

## Exploratory Data Analysis (EDA)

- Checked for missing/null values
- Analyzed correlations using a heatmap
- Visualized feature distributions with pairplots and histograms
- Class distribution for diabetic vs non-diabetic cases

##  Machine Learning Model

- **Model Used**: Logistic Regression
- **Train-Test Split**: 80% training, 20% testing
- **Evaluation Metrics**:
  - Accuracy Score
  - Confusion Matrix
  - Classification Report (Precision, Recall, F1-Score)

##  Results

- Model performance evaluated on the test set
- Visualized confusion matrix to show correct and incorrect predictions

##  How to Run

1. Open [Google Colab](https://colab.research.google.com/).
2. Upload and open the `DiabetesPrediction.ipynb` notebook.
3. Run all cells sequentially.
4. The notebook will perform data preprocessing, train a logistic regression model, and display evaluation results.

## Outcome

This model provides a simple and interpretable solution for diabetes prediction, which can be extended to use other models or be integrated into healthcare applications.

---

## Note

This project is for educational purposes and should not be used for real-world medical diagnosis without proper validation.
