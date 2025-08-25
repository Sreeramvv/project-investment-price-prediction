### Overview
This project focuses on predicting stock prices using Machine Learning techniques. Financial markets are highly dynamic and influenced by various factors, making price prediction a challenging task. In this project, I analyze historical stock market data and build predictive models to forecast future stock prices.The goal is to provide insights that can assist investors in making informed decisions

### Technologies Used
- **Programming Language**: Python  
- **Libraries**: Pandas, NumPy, Matplotlib, Scikit-learn  
- **Visualization**: Matplotlib, Seaborn  
- **ML Models**: Random Forest, KNN, SVM, Naive Bayes, Decision Tree  

## Key steps
**Data**
  - CSV
**Data Cleaning & Preprocessing**
  - Handling missing values
  - Outlier treatment
  - Normalization & scaling
 **Exploratory Data Analysis (EDA)**  
   - Used **Seaborn** and **Matplotlib** for data visualization  
   - Analyzed correlations, distributions, and outliers
**Model Building**
   - Train-Test split
   - Training ML/DL models
### Model Evaluation

| Model               | Accuracy | Precision | Recall  | F1-score |
|---------------------|----------|-----------|---------|----------|
| KNN                 | 0.9403   | 0.5242    | 0.4119  | 0.4613   |
| Logistic Regression | 0.9469   | 0.6667    | 0.2888  | 0.4030   |
| Naive Bayes         | 0.9167   | 0.4011    | 0.6930  | 0.5081   |
| Decision Tree       | 0.9546   | 0.6920    | 0.4848  | 0.5702   |
| Random Forest       | 0.9551   | 0.6865    | 0.5091  | 0.5846   |
| SVM                 | 0.9459   | 0.6892    | 0.2325  | 0.3477   |

### Results and Observation
- Random Forest performed the best overall with the highest Accuracy (95.5%) and balanced Precision-Recall.
- Naive Bayes had the highest Recall but lower Precision.
- Logistic Regression and SVM showed decent performance but struggled with Recall.
- Decision Tree also performed strongly, slightly behind Random Forest.
