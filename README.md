# Titanic Survival Prediction using Logistic Regression

## Project Overview
This project uses Machine Learning to predict whether a passenger survived the Titanic disaster using Logistic Regression.

## Technologies Used
- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## Project Workflow
1. Load the Titanic dataset.
2. Perform Exploratory Data Analysis (EDA).
3. Handle missing values.
4. Remove unnecessary columns.
5. Convert categorical variables into numerical values using Label Encoding.
6. Split the dataset into training and testing sets.
7. Train a Logistic Regression model.
8. Predict passenger survival.
9. Evaluate the model using:
   - Accuracy Score
   - Confusion Matrix
   - Precision
   - Recall
   - F1-score

## Model Performance
The Logistic Regression model achieved approximately **80% accuracy** on the test dataset.

## Dataset
The dataset is loaded using Seaborn's built-in Titanic dataset.

```python
import seaborn as sns
df = sns.load_dataset("titanic")
```

## How to Run
1. Clone this repository.
2. Install the required libraries.
3. Open the Jupyter Notebook.
4. Run the cells sequentially.
