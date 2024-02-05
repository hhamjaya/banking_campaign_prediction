# Machine Learning Lab 1

## Project Overview

This project aims to predict whether a customer will subscribe to a term deposit following a banking marketing campaign. The marketing campaign involves phone calls to clients, and multiple contacts might be required to assess whether the client subscribes ('yes') or not ('no'). We will employ machine learning techniques to predict the likelihood of a client subscribing based on various features.

## Data Description

The dataset includes various features related to bank client information, campaign details, and social/economic context. These features will be used to predict the target variable, whether the client subscribes to a term deposit.

### Input Variables

- **Bank Client Data:**
  1. **Age** (numeric)
  2. **Job**: Type of job (categorical: `'admin.'`, `'blue collar'`, `'entrepreneur'`, `'housemaid'`, `'management'`, `'retired'`, `'self-employed'`, `'services'`, `'student'`, `'technician'`, `'unemployed'`, `'unknown'`)
  3. **Marital**: Marital status (categorical: `'divorced'`, `'married'`, `'single'`, `'unknown'`; note: `'divorced'` means divorced or widowed)
  4. **Education**: Education level (categorical: `'basic.4y'`, `'basic.6y'`, `'basic.9y'`, `'high.school'`, `'illiterate'`, `'professional.course'`, `'university.degree'`, `'unknown'`)
  5. **Default**: Has credit in default? (categorical: `'no'`, `'yes'`, `'unknown'`)
  6. **Housing**: Has housing loan? (categorical: `'no'`, `'yes'`, `'unknown'`)
  7. **Loan**: Has personal loan? (categorical: `'no'`, `'yes'`, `'unknown'`)

- **Campaign Data:**
  8. **Contact**: Communication type (categorical: `'cellular'`, `'telephone'`)
  9. **Month**: Last contact month (categorical: `'jan'`, `'feb'`, `'mar'`, ..., `'dec'`)
  10. **Day of Week**: Last contact day of the week (categorical: `'mon'`, `'tue'`, `'wed'`, `'thu'`, `'fri'`)
  11. **Duration**: Last contact duration (numeric). This variable highly affects the output target and should be used for benchmark purposes but discarded for realistic predictive models.

- **Other Attributes:**
  12. **Campaign**: Number of contacts performed during this campaign (numeric)
  13. **Pdays**: Number of days since the last contact (numeric; 999 means the client was not previously contacted)
  14. **Previous**: Number of contacts performed before this campaign (numeric)
  15. **Poutcome**: Outcome of the previous marketing campaign (categorical: `'failure'`, `'nonexistent'`, `'success'`)

- **Social and Economic Context:**
  16. **Emp.var.rate**: Employment variation rate (numeric)
  17. **Cons.price.idx**: Consumer price index (numeric)
  18. **Cons.conf.idx**: Consumer confidence index (numeric)
  19. **Euribor3m**: Euribor 3-month rate (numeric)
  20. **Nr.employed**: Number of employees (numeric)

### Output Variable

- **y**: Has the client subscribed to a term deposit? (binary: `'yes'`, `'no'`)

## Task Description

The goal of this project is to build machine learning models that predict the likelihood of a customer subscribing to a term deposit, based on the features provided.

### Steps Involved:

1. **Data Preprocessing:**
   - Analyze and clean the data.
   - Choose the features for the model and justify the selection.
   - Process categorical data and handle missing values.

2. **Model Training:**
   - Train at least two different machine learning models to predict the target variable.
   - Achieve at least 80% accuracy.

3. **Model Evaluation:**
   - Visualize and interpret the performance of the models.
   - Compare the results and explain any differences between the models.

4. **Reporting:**
   - Document your process and analysis in a written report.

## Approach

1. **Data Processing:**
   - **Feature Selection:** Only relevant features will be selected, and categorical features will be encoded appropriately (e.g., One-Hot Encoding).
   - **Missing Data Handling:** Missing values will be imputed or removed based on the distribution of the data.
   - **Scaling:** Numeric features will be scaled (if necessary) to ensure that all features contribute equally to the model.

2. **Machine Learning Algorithms:**
   - We will train two different machine learning algorithms, such as:
     - Logistic Regression
     - Random Forest Classifier
   - **Model Evaluation:** We will evaluate the models using metrics such as accuracy, confusion matrix, ROC-AUC, etc.

3. **Model Performance Visualization:**
   - Visual tools such as confusion matrices, precision-recall curves, and ROC curves will be used to compare model performance.

4. **Results Comparison:**
   - The performance of the models will be compared, and insights into why one model may perform better than the other will be provided.


## Overall Feedback:
Very impressive report and notebooks. 
The data analysis was very nicely done as was the visualisation. 