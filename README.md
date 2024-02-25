# Instacart Market Basket Analysis

Whether you shop from meticulously planned grocery lists or let whimsy guide your grazing, our unique food rituals define who we are. Instacart, a grocery ordering and delivery app, aims to make it easy to fill your refrigerator and pantry with your personal favorites and staples when you need them. After selecting products through the Instacart app, personal shoppers review your order and do the in-store shopping and delivery for you.

This project used data on customer orders over time to predict which previously purchased products will be in a user’s next order.

# Dataset: 
[Kaggle](https://www.kaggle.com/c/instacart-market-basket-analysis/overview)

# Environment Setup:
Please see the `requirements.txt` file for the required packages and versions.

# Code:
Please run the files in the following order:

1. [`Master Dataset.ipynb`](https://github.com/McGill-MMA-EnterpriseAnalytics/Instacart-Market-Basket-Analysis/blob/97eff2766134c82d9b487b5096ca2028dde923a6/Master%20Dataset.ipynb)
Tranforms the Kaggle dataset into the master dataset that.
2. [`EDA.ipynb`](https://github.com/McGill-MMA-EnterpriseAnalytics/Instacart-Market-Basket-Analysis/blob/97eff2766134c82d9b487b5096ca2028dde923a6/EDA.ipynb)
The exploratory data analysis contains some uni-variate, bi-variate analysis and some advanced visualizations. The train-test split is also done in this notebook.
3. [`Feature Engineering.ipynb`](https://github.com/McGill-MMA-EnterpriseAnalytics/Instacart-Market-Basket-Analysis/blob/97eff2766134c82d9b487b5096ca2028dde923a6/Feature_Engineering.ipynb)
Adds new features, imputes missing values and encodes the categorical variables.
4. [`Updated feature selection.ipynb`](https://github.com/McGill-MMA-EnterpriseAnalytics/Instacart-Market-Basket-Analysis/blob/97eff2766134c82d9b487b5096ca2028dde923a6/Updated%20feature%20selection.ipynb)
Fixes the distribution shift and handles imbalances. The information leakage analysis is also done in this notebook, along with the final feature selection.
5[`Modeling.ipynb`](https://github.com/McGill-MMA-EnterpriseAnalytics/Instacart-Market-Basket-Analysis/blob/97eff2766134c82d9b487b5096ca2028dde923a6/Modelling.ipynb)
The classification models are trained and evaluated in this notebook. Their results are interpreted and the best performing model is fine tuned and saved as a pickle file.
# Streamlit App:
To view the streamlit app, please click [here](https://predicting-appucts-reordered-by-customer-7852zyrzsf2axkrqwx8l8.streamlit.app/​).
