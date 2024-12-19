# Stars Classification 🌟

### Overview
This project classifies stars into categories like Main Sequence, Giants, and Hypergiants using supervised learning techniques. Achieved a **perfect score** in this project, demonstrating exceptional predictive performance and robust data handling.

---

## Dataset
The dataset contains several features related to stars:
- **Temperature (K)**: Absolute temperature.
- **Luminosity (L/Lo)**: Relative luminosity.
- **Radius (R/Ro)**: Relative radius.
- **Absolute Magnitude (Mv)**: Brightness.
- **Star Color**: Categorical (e.g., Red, White).
- **Spectral Class**: Categorical (O, B, A, F, G, K, M).
- **Star Category**: Target variable (e.g., Main Sequence, Supergiants).

---

## Workflow
### 1. **Data Preprocessing**
- Handled outliers representing valid star types.
- Standardized inconsistent values (e.g., `Star Color`).
- Normalized features with wide ranges.

### 2. **Exploratory Data Analysis (EDA)**
- Visualized distributions and relationships using histograms, KDE plots, and scatter plots.
- Used heatmaps to examine feature correlations.

### 3. **Model Building**
- Selected a Random Forest model for its robustness and feature importance analysis.
- Achieved:
  - **Accuracy**: 99.58%
  - **Precision**: 99.60%
  - **Recall**: 99.55%
  - **F1 Score**: 99.57%
  - **ROC-AUC Curve**: Perfect AUC of 1.0 for all classes.

### 4. **Evaluation**
- Validated with cross-validation (10 folds).
- Visualized model performance using ROC-AUC curves, confusion matrix, and learning curves.

### 5. **Challenges**
- Managing valid outliers for extreme star types like Hypergiants.
- Balancing class imbalance without oversampling.

---

## Results
The model effectively classified all star categories with minimal error, leveraging key features like Absolute Magnitude, Radius, and Luminosity.

---

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/stars-classification.git
