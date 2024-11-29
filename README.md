# Horse Colic Dataset Analysis

## Project Overview
This project focuses on analyzing and predicting outcomes from the Horse Colic dataset using Python. The notebook demonstrates data preprocessing, exploratory data analysis (EDA), and machine learning techniques to classify outcomes effectively. By tackling issues such as missing data, class imbalance, and feature engineering, this project provides insights into the dataset while building robust predictive models.

---

## Dataset
The dataset contains medical records for horses, including features like rectal temperature, pulse, pain level, and mucous membranes, among others. The target variable is the `Outcome`, which represents the condition of the horse after treatment.

- **Data Source**: `horse-colic.data`
- **Metadata**: Descriptions are available in `horse-colic.names`.
- **Size**: 368 rows × 28 columns

---

## Key Steps and Methods
### 1. Data Preprocessing
- **Handling Missing Values**: Identified and addressed columns with high missing value ratios.
- **Feature Engineering**:
  - Categorical, numerical, and ordinal features were categorized.
  - Outliers were managed, and scaling techniques were applied to numerical features.
- **Data Splitting**: Train-test split with stratification to preserve class distribution.

### 2. Exploratory Data Analysis (EDA)
- Visualized class distributions and feature relationships using:
  - Pair plots for numerical features.
  - Count plots for categorical features.
  - Heatmaps for feature correlations.

### 3. Machine Learning Pipeline
- Designed a preprocessing pipeline with:
  - Imputation (Simple and Iterative).
  - Encoding for categorical variables.
  - Scaling of numerical features.
- Built baseline models and fine-tuned classifiers, including:
  - **Logistic Regression**
  - **Random Forest**

### 4. Evaluation
- Used metrics such as accuracy, precision, recall, and F1-score to evaluate models.
- Conducted hyperparameter tuning to optimize performance.

---

## Results
- The Random Forest model with optimized hyperparameters achieved the best results, balancing accuracy and recall across all classes.
- Logistic Regression performed well as a baseline model but was less effective in handling imbalanced classes.

---

## How to Use
### Prerequisites
- Python 3.x
- Libraries: `pandas`, `numpy`, `seaborn`, `matplotlib`, `scikit-learn`

### Steps to Run
1. Clone the repository.
2. Ensure the dataset files (`horse-colic.data` and `horse-colic.names`) are in the same directory as the notebook.
3. Run the notebook (`Horse_Colic_Notebook.ipynb`) in Jupyter or any compatible Python IDE.

---

## Visualizations

![output_12_2](https://github.com/user-attachments/assets/59a10be8-f908-406f-9bed-005723664d5f)
![output_27_0](https://github.com/user-attachments/assets/859e2564-b8d9-4c09-bade-1252455f4e99)
![output_28_1](https://github.com/user-attachments/assets/3963bb9b-8494-40f2-a727-132f0b278188)
![output_30_0](https://github.com/user-attachments/assets/8d2bd44d-302f-4b44-a36a-553249ec2d9e)

---

## Future Work
- Experiment with advanced models like Gradient Boosting or Neural Networks.
- Perform feature selection to identify key predictors.
- Investigate methods to better handle imbalanced data, such as SMOTE.

---

## Acknowledgments
- Dataset provided as part of a case study for classification and medical diagnostics.
- Special thanks to all contributors and open-source libraries used in this project.
