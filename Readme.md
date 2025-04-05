 Breast Cancer Prediction using Machine Learning

This project uses machine learning models to predict whether a tumor is **benign** or **malignant** using features from the **Breast Cancer Wisconsin Dataset**. It includes data visualization, model comparison, and evaluation metrics to ensure reliable predictions.

 Project Contents

- `BCP_Enhanced.ipynb`: Main notebook with complete data loading, preprocessing, model training, evaluation, and visualization.
- Visualizations: Heatmaps, ROC Curve, Feature Importance chart.
- Models: Logistic Regression, Random Forest, Support Vector Machine (SVM), K-Nearest Neighbors (KNN).

 Models Compared

| Model                | Description                      |
|---------------------|----------------------------------|
| Logistic Regression | Simple and fast linear model     |
| Random Forest       | Ensemble learning, good accuracy |
| SVM                 | Works well with clear margins    |
| KNN                 | Instance-based learning          |

 Features

- Correlation Heatmap
- Confusion Matrix
- Classification Report
- ROC Curve & AUC Score
- Feature Importance (Random Forest)

How to Run

1. Open the notebook in Google Colab or Jupyter Notebook.
2. Run all cells in order.
3. All required libraries are standard (e.g., `pandas`, `sklearn`, `seaborn`, `matplotlib`).

## Dataset Info

- Source: `sklearn.datasets.load_breast_cancer()`
- Samples: 569
- Features: 30 numerical features related to cell nuclei
- Target: `0 = Malignant`, `1 = Benign`

## Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you'd like to change.

## License

This project is open-source and available under the [MIT License](https://opensource.org/licenses/MIT).
