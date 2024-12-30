# Bankruptcy-Prediction-for-US-Businesses-Leveraging-Machine-Learning-for-Financial-Stability

# Bankruptcy Prediction Using Financial Probabilities  

## Overview  
This project focuses on developing a robust bankruptcy prediction system using a dataset of financial probabilities and market indicators. The dataset contains features such as probabilities generated from various prediction models, volatility metrics, and multipliers, enabling detailed analysis and accurate classification of companies at risk of bankruptcy. By leveraging machine learning models and comprehensive data analysis, the project aims to provide actionable insights for businesses, investors, and policymakers.  

---

## Objectives  
1. **Predict Bankruptcy Risk**: Use machine learning classification models to identify companies with a high probability of bankruptcy.  
2. **Feature Analysis**: Understand the relationships between market volatility, financial multipliers, and various predictive probabilities to derive valuable insights.  
3. **Insights for Business Decisions**: Enable stakeholders to make informed decisions by identifying critical trends and risk factors.  

---

## Performance of Machine Learning Models  

### Logistic Regression  
- **Accuracy**: 99.97%  
- **Confusion Matrix**:  
  ```
  [[     0     90]
   [     0 338403]]
  ```
- **Classification Report**:  
  ```
                precision    recall  f1-score   support

            0       0.00      0.00      0.00        90
            1       1.00      1.00      1.00    338403

     accuracy                           1.00    338493
    macro avg       0.50      0.50      0.50    338493
 weighted avg       1.00      1.00      1.00    338493
  ```  

### Random Forest  
- **Accuracy**: 100%  
- **Confusion Matrix**:  
  ```
  [[    90      0]
   [     0 338403]]
  ```
- **Classification Report**:  
  ```
                precision    recall  f1-score   support

            0       1.00      1.00      1.00        90
            1       1.00      1.00      1.00    338403

     accuracy                           1.00    338493
    macro avg       1.00      1.00      1.00    338493
 weighted avg       1.00      1.00      1.00    338493
  ```  

### XGBoost  
- **Accuracy**: 99.99%  
- **Confusion Matrix**:  
  ```
  [[    88      2]
   [     3 338400]]
  ```
- **Classification Report**:  
  ```
                precision    recall  f1-score   support

            0       0.97      0.98      0.97        90
            1       1.00      1.00      1.00    338403

     accuracy                           1.00    338493
    macro avg       0.98      0.99      0.99    338493
 weighted avg       1.00      1.00      1.00    338493
  ```  

---

## Key Features  
- **Dataset**: Includes columns such as probabilities derived from predictive models (`probability_light`, `probability_convolution`, etc.), `volatility`, and `multiplier`.  
- **Exploratory Data Analysis (EDA)**: Detailed analysis of feature distributions, correlations, outliers, and time series trends.  
- **Machine Learning Models**: Applied Logistic Regression, Random Forest, and XGBoost for bankruptcy classification.  
- **Model Comparison**: Evaluated models using performance metrics to determine the most effective approach.  

---

## Business Impacts  
1. **Proactive Risk Management**: By identifying companies with high bankruptcy risks, businesses can mitigate financial losses and improve risk management strategies.  
2. **Investor Confidence**: Providing reliable predictions helps investors make data-driven decisions, enhancing trust and market stability.  
3. **Policy Development**: Insights derived from probability trends and risk factors can assist regulators in formulating policies to safeguard industries from large-scale financial failures.  
4. **Cost Optimization**: Early predictions of bankruptcy allow companies to allocate resources more effectively, reducing the costs associated with late-stage interventions.  
5. **Market Stability**: Predictive insights contribute to maintaining the overall health and stability of financial markets.  

---

## Future Scope  
- **Enhanced Feature Engineering**: Add macroeconomic indicators such as GDP, inflation rates, and interest rates to improve model accuracy.  
- **Deep Learning Models**: Experiment with neural networks for more complex patterns and relationships.  
- **Real-Time Prediction**: Develop a pipeline for real-time bankruptcy predictions using financial APIs.  

---

## Conclusion  
This project demonstrates the power of data-driven decision-making in addressing real-world financial challenges. By predicting bankruptcy risks and analyzing contributing factors, it serves as a valuable tool for businesses and investors, paving the way for smarter, more informed financial strategies.  

---

## Conclusion  
This project demonstrates the power of data-driven decision-making in addressing real-world financial challenges. By predicting bankruptcy risks and analyzing contributing factors, it serves as a valuable tool for businesses and investors, paving the way for smarter, more informed financial strategies.  
