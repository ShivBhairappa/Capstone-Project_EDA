### Project Title

**Author**

#### Executive summary
This project investigates key customer behaviors and trends within an e-commerce platform, analyzing demographics, engagement, and purchasing patterns. Through exploratory data analysis (EDA) and a baseline machine learning model, the study identifies influential factors driving premium membership and overall customer value.

#### Rationale
Understanding which attributes influence customer retention and premium subscriptions can help businesses enhance marketing strategies, optimize product offerings, and increase revenue. This analysis provides insights into how different demographic and behavioral features correlate with customer lifetime value and membership.

#### Research Question
What customer characteristics and engagement metrics most strongly influence premium membership and total spending?

#### Data Sources
The data used is from an anonymized e-commerce customer dataset, containing information on demographics, transaction history, engagement metrics, and customer satisfaction.

#### Methodology
- Cleaned missing values for `Age`, `Gender`, and `IncomeLevel`.
- Engineered a new variable `TotalSpend` as the product of `TotalPurchases` and `AverageOrderValue`.
- Conducted EDA using histograms, boxplots, bar charts, and heatmaps to explore feature relationships.
- Trained a logistic regression model to predict premium membership status based on selected features.

#### Results

Our exploratory data analysis revealed several key insights:

- **Customer Segments**: High-spending customers are typically aged 30–45 and belong to higher income brackets.
- **Average Order Value**: Significantly higher among customers with "Very High" income levels.
- **Engagement Patterns**: Premium and repeat customers show greater email/social media engagement. Engagement correlates moderately with lifetime value.
- **Gender Trends**: Males and females display different spending patterns, with males slightly outspending on average.
- **Baseline Model**: A logistic regression classifier was built to predict `PremiumMember` status using purchase behavior and engagement metrics. 
  - The model showed reasonable accuracy and serves as a strong baseline for further improvement in Module 24.

#### Next steps
- Test alternative models (e.g., Random Forest, Gradient Boosting, XGBoost).
- Incorporate additional features like `CustomerSatisfactionScore` and session-level engagement.
- Perform hyperparameter tuning to optimize classification accuracy.
- Finalize visualizations and summaries for both technical and business stakeholders.

#### Outline of project

- [Link to notebook 1](E_commerce_cus_analyze.ipynb)
- [Link to notebook 2]()
- [Link to notebook 3]()

##### Contact and Further Information