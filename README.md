# SVM Breast Cancer Classification

This project applies Support Vector Machines (SVMs) to classify tumors as malignant or benign using the Breast Cancer Wisconsin dataset. The implementation includes both linear and RBF kernel SVMs, visualization of decision boundaries, hyperparameter tuning with GridSearchCV, and model evaluation using cross-validation.

## 📊 Dataset

The [Breast Cancer Wisconsin Dataset](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_breast_cancer.html) is a built-in dataset from Scikit-learn that contains features computed from digitized images of breast mass samples.

- **Number of Samples:** 569
- **Number of Features:** 30
- **Target Classes:** Malignant (0), Benign (1)

## 🧠 Project Workflow

1. **Data Preprocessing**
   - Feature standardization using `StandardScaler`
   - Dimensionality reduction (PCA) for visualization purposes

2. **Model Training**
   - SVM with linear kernel
   - SVM with RBF kernel

3. **Visualization**
   - Plotting decision boundaries in 2D using PCA-transformed features

4. **Hyperparameter Tuning**
   - Tuning `C` and `gamma` using `GridSearchCV`

5. **Model Evaluation**
   - Cross-validation accuracy
   - Confusion matrix and classification report

## 📈 Results

- Hyperparameter tuning improves accuracy significantly.
- RBF kernel generally performs better than linear in capturing complex decision boundaries.
- Achieved **>97% cross-validated accuracy** with tuned parameters.

## 🛠️ Technologies Used

- Python
- NumPy
- Scikit-learn
- Matplotlib
- PCA for visualization
