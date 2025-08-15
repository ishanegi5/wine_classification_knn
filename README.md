# wine_classification_knn

A K-Nearest Neighbors (KNN) classification project using the Wine dataset from scikit-learn. Includes data preprocessing, model training, and performance evaluation.

##  Description

This project implements the KNN algorithm to classify wine samples by chemical properties. It includes steps for data splitting, feature scaling, model training, and evaluation using accuracy, confusion matrix, and classification report.

##  Dataset Details

- **Source**: `sklearn.datasets.load_wine()`  
- **Total Samples**: 178  
- **Features**: 13 numeric chemical measurements (e.g., alcohol, malic_acid, hue, etc.)  
- **Classes**: 3 wine types labeled 0, 1, and 2

##  Project Workflow

1. Load the Wine dataset  
2. Create DataFrame for features and target  
3. Split into train and test sets  
4. Scale features using `StandardScaler`  
5. Train KNN classifier  
6. Generate predictions on test set  
7. Evaluate model using:
   - Accuracy score
   - Confusion matrix
   - Classification report (precision, recall, F1-score)

##  Evaluation Results

- **Accuracy**: ~94.44%  
- **Confusion Matrix**:
[[14 0 0]
[ 1 12 1]
[ 0 0 8]]

- **Classification Report**:

| Class | Precision | Recall | F1-Score | Support |
|-------|-----------|--------|----------|---------|
| 0     | 0.93      | 1.00   | 0.97     | 14      |
| 1     | 1.00      | 0.86   | 0.92     | 14      |
| 2     | 0.89      | 1.00   | 0.94     | 8       |

##  How to Run

1. Clone the repo:
  ```bash
  git clone https://github.com/ishanegi5/wine_classification_knn.git
  cd wine_classification_knn
  ```
2. Install dependencies:
  ```bash
  pip install scikit-learn pandas numpy
  ```
3. Run your script or Jupyter notebook (e.g., `python wine_knn.py` or `jupyter notebook`).

##  Dependencies

- Python 3.x  
- scikit-learn  
- pandas  
- numpy

##  License

This project is open-source. Feel free to use and modify it.

---

Let me know if you want customized badges (like build or coverage), a GitHub Actions workflow, or pretty visuals to enhance the README!
::contentReference[oaicite:0]{index=0}
