Iris Flower Classification — Summary

1.Objective:
Classify Iris flowers into Setosa, Versicolor, and Virginica using their sepal and petal measurements.

2.Dataset:
- Total samples: 150
- Features: 4
- Classes: 3
- Balanced dataset

3.Model Used:
A simple ML pipeline:
- StandardScaler
- Logistic Regression (multinomial)

4.Performance:
The model achieves strong accuracy on the test dataset:
- Accuracy: ~93%
- Very few misclassifications
- Clear separation between classes

5.Files Generated:
- `notebook.ipynb` — main code
- `iris_dataset.csv` — dataset used
- `iris_model.pkl` — trained model saved using joblib

