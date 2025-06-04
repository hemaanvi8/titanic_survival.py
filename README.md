# titanic_survival.py

This is a machine learning project that predicts whether a passenger survived the Titanic disaster using logistic regression. The project is implemented in a Jupyter Notebook using Python and scikit-learn.

## Dataset

The dataset used is a CSV file containing features such as:
- Pclass (Ticket class)
- Sex
- Age
- SibSp (Number of siblings/spouses aboard)
- Parch (Number of parents/children aboard)
- Fare (Passenger fare)
- Embarked (Port of embarkation)
- Outcome (0 = did not survive, 1 = survived)

## How to Run

1. Clone this repository or download the files.
2. Make sure you have the required Python libraries:
   - pandas
   - numpy
   - scikit-learn
   - matplotlib (optional)
   - seaborn (optional)

3. Open the notebook in Jupyter:

```
jupyter notebook titanic_survival.ipynb
```

4. Run all cells to preprocess the data, train the model, and evaluate performance.

## Model

The project uses a logistic regression model from scikit-learn. The process includes:
- Handling missing values
- Encoding categorical variables
- Splitting data into training and test sets
- Training and evaluating the model

## Example Output

```
Accuracy: 0.79
Classification Report:
              precision    recall  f1-score   support

           0       0.81      0.87      0.84       105
           1       0.75      0.66      0.70        70

    accuracy                           0.79       175
   macro avg       0.78      0.77      0.77       175
weighted avg       0.79      0.79      0.79       175
```
