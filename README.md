# Predicting_House_Prices

### **Project Summary**

This project focuses on predicting house prices in Melbourne, Australia, using machine learning techniques. The dataset, sourced from Kaggle, includes essential features such as `Suburb`, `Landsize`, `Distance` from the Central Business District (CBD), `Regionname`, and `Price`. The goal was to develop a predictive model that captures the relationships between location-based features and house prices while offering insights into the key factors influencing property values.

Key insights uncovered include the importance of proximity to the CBD, land size, and regional price trends. Properties closer to the CBD generally command higher prices due to better access to amenities, while larger land sizes are significant drivers of value, especially in suburban areas. Engineered features such as `Suburb_Avg_Price` and `Price_per_SquareMetre` further revealed nuanced patterns in pricing.

Trends observed include a strong correlation between regional average prices and property values, as well as non-linear relationships between predictors and the target variable. Random Forest emerged as the best-performing model, with an R² of 0.9794 after hyperparameter tuning, effectively capturing these non-linear patterns.

In conclusion, this project demonstrates the value of advanced machine learning techniques like Random Forests in predicting house prices, highlighting the importance of feature engineering and non-linear modeling for real-world datasets.
