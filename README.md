# Capstone Two: Restaurant Rating Prediction & Business Insights

## Project Overview
This capstone project analyzes a global restaurant dataset to identify the key factors that influence restaurant ratings and to build a predictive machine learning model. The goal is to generate **actionable business insights** that restaurant owners and stakeholders can use to improve customer satisfaction and competitive positioning.

The project follows the full **data science lifecycle**, including data wrangling, exploratory data analysis (EDA), preprocessing, modeling, evaluation, and storytelling.

---

## Business Problem
Restaurant ratings strongly impact customer decisions, revenue, and long-term success. However, it is often unclear which factors most strongly influence ratings.

**Key Questions:**
- What restaurant attributes most influence ratings?
- Can ratings be accurately predicted using structured data?
- How can restaurants use these insights to improve performance?

---

## Dataset
The dataset includes top-rated restaurants worldwide and contains features related to:
- Price range
- Cuisine type
- Location
- Dining and service characteristics
- Review-related attributes

The dataset was cleaned, encoded, and split into training and testing sets prior to modeling.

---

## Data Wrangling & Preprocessing
Key preprocessing steps:
- Handled missing values
- Encoded categorical variables
- Scaled numeric features where appropriate
- Created preprocessed training and testing datasets

## Exploratory Data Analysis (EDA)
Exploratory analysis revealed:
- Higher price ranges are generally associated with higher ratings
- Certain cuisines consistently receive stronger ratings
- Service-related features have a meaningful impact
- Ratings are moderately skewed toward higher values

## Modeling Approach
Multiple regression and ensemble models were evaluated. Models were compared using:
- RMSE
- MAE
- R² score

The final model was selected based on **generalization performance** and **business interpretability**.

## Final Model Performance
**Final Selected Model:** Gradient Boosting Regressor

### Test Set Metrics
- **RMSE:** 0.0891  
- **MAE:** 0.0743  
- **R²:** 0.0550  

The Gradient Boosting model outperformed baseline and Random Forest models in overall predictive stability.

## Key Insights
- **Price range** is the strongest predictor of restaurant rating
- **Cuisine type** significantly influences customer perception
- **Service quality indicators** play a major role in rating outcomes
- Location contributes but is less influential than pricing and service

---

## Business Recommendations
Restaurants can use these findings to:
1. **Align pricing with perceived value** to improve customer satisfaction
2. **Invest in service quality**, which strongly correlates with higher ratings
3. **Differentiate cuisine offerings** to stand out in competitive markets

---

## Future Improvements
- Incorporate sentiment analysis from customer reviews
- Explore time-based trends in ratings
- Test advanced models (XGBoost, LightGBM)
- Expand dataset to include lower-rated restaurants

---

## Technologies Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Jupyter Notebook
