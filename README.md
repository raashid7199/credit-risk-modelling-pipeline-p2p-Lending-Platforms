# credit-risk-modelling-pipeline-p2p-Lending-Platform

## **Project Overview**
This project focuses on analyzing and predicting loan defaults for Bondora, a leading European peer-to-peer (P2P) lending company. By preprocessing the dataset, transforming target variables, and creating a binary classification model, we aim to provide actionable insights into reducing financial risks for lenders and borrowers.

---

## **Project Goals**
- Clean and preprocess the dataset to handle missing values, duplicates, and outliers.
- Create a binary target variable (`Default` or `Not Default`) based on loan statuses.
- Encode categorical variables and transform the data into a model-ready format.
- Perform exploratory data analysis (EDA) to understand key features influencing loan defaults.
- Build predictive models to assess default risks.

---

## **Dataset Details**
The dataset contains historical loan data from Bondora, including:
- Loan statuses
- Borrower details
- Loan amount and interest rates
- Payment history and more

## Data Link

The data required for preprocessing, cleaning and labeling tasks can be downloaded from the following Google Drive link:

[Download Data](https://drive.google.com/file/d/1WJGK6fBAIQgszLOSbYyifTIdsxf-QDJ6/view?usp=sharing)

### **Target Variable**
The `Status` column is transformed into a binary variable:
- **1 (Default):** Includes statuses like "Charged Off," "Late," and "Defaulted."
- **0 (Not Default):** Includes statuses like "Fully Paid" and "Current."

---

## **Data Preprocessing Steps**
### **1. Data Cleaning**
- Handle missing values using appropriate imputation techniques.
- Remove duplicates and standardize column names.
- Convert columns (e.g., date columns) to their appropriate formats.

### **2. Target Variable Transformation**
- Map the `Status` column into binary values:
  - `1` for loan defaults.
  - `0` for non-defaults.

### **3. Data Encoding**
- Apply label encoding for binary categorical columns.
- Use one-hot encoding for multi-category columns.

### **4. Outlier Detection and Handling**
- Detect outliers in numeric columns using statistical methods.
- Cap extreme values to the 1st and 99th percentiles.

---

## **How to Use This Repository**
1. Clone the repository:
   ```bash
   git clone https://github.com/Technocolabs100/credit-risk-modelling-pipeline-p2p-Lending-Platform.git
   ```
2. Install the required Python libraries:
   ```bash
   pip install -r requirements.txt
   ```
---

## **Technologies Used**
- **Programming Language:** Python
- **Libraries and Tools:**
  - Pandas, NumPy (Data Preprocessing)
  - Scikit-learn (Modeling)
  - Matplotlib, Seaborn (Visualization)
  - Jupyter Notebook
  - PowerBI and Tableau Dashboards (Visualization)

---

## **Contributing**
We welcome contributions! If you'd like to contribute:
1. Fork this repository.
2. Create a new branch.
3. Commit your changes and push to your branch.
4. Create a pull request, and we’ll review it.

---

## **License**
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

