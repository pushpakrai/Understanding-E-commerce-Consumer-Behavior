# E-commerce Shopper Behavior Analysis  

This project focuses on analyzing and predicting customer shopping behavior for an e-commerce client using user session data collected over a year. The objective is to identify patterns influencing purchases and build a predictive model for the `Made_Purchase` column.  

---

## Dataset Overview  

The dataset consists of the following files:  

- **`train.csv`**: Training data with user attributes and purchase indicators.  
- **`test.csv`**: Test data for predictions.  
- **`sample_submission.csv`**: Example submission format.  

### Key Features  

1. **Page Metrics**  
   - Visit counts and durations for `HomePage`, `LandingPage`, and `ProductDescriptionPage`.  

2. **Google Metrics**  
   - `Bounce Rate`, `Exit Rate`, and `Page Value` provide insights into user engagement and exit behavior.  

3. **Seasonal Indicators**  
   - `SeasonalPurchase` and `Month_SeasonalPurchase` capture purchase trends during seasonal events.  

4. **Demographics and Contextual Attributes**  
   - Includes `OS`, `Search Engine`, `Zone`, `Type of Traffic`, `Customer Type`, `Gender`, and more.  

---

## Approach  

1. **Preprocessing**: Cleaning and handling inaccuracies in user data.  
2. **EDA**: Identifying patterns and relationships between features.  
3. **Feature Engineering**: Enhancing predictive capabilities through derived metrics.  
4. **Modeling**: Training machine learning models to predict purchase behavior.  
5. **Evaluation**: Optimizing results based on F1-Score, focusing on precision and recall balance.  

---

## Tools and Dependencies  

- **Scikit-learn**: Model development and evaluation.  
- **Pandas, NumPy**: Data handling and preprocessing.  
- **XGBoost**: Advanced gradient boosting for predictions.  
- **Matplotlib, Seaborn**: Data visualization.  
- **Imbalanced-learn**: Addressing class imbalances.  

---

## Business Impact  

- **Improved Engagement**: Insights into bounce and exit rates for better user retention.  
- **Targeted Marketing**: Seasonal purchase patterns for campaign optimization.  
- **Enhanced Conversions**: Data-driven strategies to boost sales performance.  
