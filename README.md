# Predictive Modeling for Real Estate Valuation: Advanced Regression Techniques and Feature Engineering

This project applies **advanced regression techniques** to predict house prices using **machine learning models**. It focuses on **feature engineering, data preprocessing, and model optimization**.

---

## Project Aim  
This project aims to **build a predictive model** that accurately estimates house prices based on key housing attributes. The dataset contains **79 features** describing various aspects of residential homes in **Ames, Iowa**.

---

## Technical Skills Demonstrated  
- **Feature Engineering**: Extracting insights from housing attributes.  
- **Data Preprocessing & Cleaning**: Handling **missing values**, encoding categorical variables, and feature selection.  
- **Regression Models**: Implementing **Random Forest** and **Gradient Boosting** for prediction.  
- **Model Evaluation**: Using **Root Mean Squared Error (RMSE)** to assess performance.  
- **Hyperparameter Tuning**: Optimizing models using **Randomized Search & Cross-validation**.  

---

## Files in This Repository  
| File | Description |
|------|------------|
| `Predictive Modeling for Real Estate Valuation Advanced Regression Techniques and Feature Engineering.ipynb` | Jupyter Notebook with data preprocessing, feature engineering, and model training. |
| `train.csv` | Training dataset with house attributes and sale prices. |
| `test.csv` | Test dataset for making predictions. |
| `submission.csv` | Final predicted house prices for competition submission. |

---

## How to Run This Project  
1. **Clone the repository**  
   ```bash
   git clone https://github.com/JordanConallLuthaisWright/Predictive Modeling for Real Estate Valuation Advanced Regression Techniques and Feature Engineering.git
   ```
2. **Navigate to the project directory**
   ```bash
   cd Predictive Modeling for Real Estate Valuation Advanced Regression Techniques and Feature Engineering
   ```
3. **Install dependencies**
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn xgboost
   ```
4. **Launch Jupyter Notebook**
   ```bash
   jupyter notebook
   ```
5. Open and run `Predictive Modeling for Real Estate Valuation Advanced Regression Techniques and Feature Engineering.ipynb`

---

## Business Scenario  
The housing market is influenced by multiple factors beyond basic attributes like **number of bedrooms** or **size of the house**. This project aims to answer key business questions:

- **Which housing features most strongly influence sale prices?**  
- **How can feature engineering improve prediction accuracy?**  
- **Which regression model performs best for price estimation?**  
- **What techniques optimize model generalization?**  

---

## Methodology & Technical Implementation  

### 1. Data Preprocessing & Feature Engineering  
- **Handled missing values** using mean, mode, and median imputation.  
- **Encoded categorical features** for machine learning compatibility.  
- **Dropped irrelevant features** that do not contribute to predictions.  

### 2. Exploratory Data Analysis (EDA)  
- **Visualized key housing features** using histograms, box plots, and heatmaps.  
- **Identified outliers** and transformed skewed variables.  

### 3. Model Implementation  
- **Built baseline models** using **Linear Regression** and **Decision Trees**.  
- **Implemented ensemble models**: **Random Forest, Gradient Boosting (XGBoost)**.  
- **Fine-tuned hyperparameters** to optimize performance.  

### 4. Model Evaluation  
- **Used RMSE** to measure prediction errors.  
- **Performed cross-validation** to improve generalization.  

---

## Key Findings & Conclusion  
- **Feature selection significantly impacts accuracy**. Removing irrelevant features reduced noise.  
- **Gradient Boosting outperformed other models** in predictive accuracy.  
- **Hyperparameter tuning improved model generalization**.  
- **Handling missing values appropriately enhanced model robustness**.  

---

## **Contact & Contributions**  
Feel free to explore and contribute. If you have any suggestions, reach out or submit a pull request.  

- **Email**: [jordan.c.l.wright@gmail.com](mailto:jordan.c.l.wright@gmail.com)  

---

### **Author:** Jordan  
[GitHub Profile](https://github.com/JordanConallLuthaisWright)
