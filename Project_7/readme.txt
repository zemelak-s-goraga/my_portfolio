
README: Predictive Analysis of Live Sheep Marketing Dataset to Develop Optimization Strategies

1. Project Overview
This project focuses on the predictive analysis of the global sheep trade, using historical data from 1961 to 2013 to forecast trends in sheep exports. The study aims to optimize market strategies by identifying patterns, comparing country performances, and understanding the relationship between export quantities and values. Leveraging FAOSTAT data, the project utilizes advanced machine learning models to develop actionable insights, helping stakeholders make data-driven decisions to enhance agricultural trade efficiency and sustainability.

The project integrates various techniques, including data preprocessing, exploratory data analysis (EDA), and predictive modeling with algorithms like Linear Regression, Random Forest, K-Nearest Neighbors (KNN), and Support Vector Regression (SVR).

2. Methodology
Data Importation & Preprocessing
Data Cleaning: Handled missing values and outliers to ensure data integrity.
Feature Engineering: Created new time-based features and performed one-hot encoding for categorical variables.
Data Transformation: Converted categorical data (e.g., country names) to numerical formats.
Exploratory Data Analysis (EDA)
Trend Analysis: Identified export trends over time using time series plots.
Country Comparison: Analyzed top exporters and their performance.
Correlation Analysis: Used scatter plots and correlation coefficients to examine the relationship between export quantities and values.
Predictive Modeling
Model Selection: Evaluated models like Linear Regression, Random Forest, KNN, and SVR.
Model Training & Tuning: Split the data into training and testing sets, followed by hyperparameter optimization using GridSearchCV.
Model Evaluation: Metrics used included Mean Squared Error (MSE), Mean Absolute Error (MAE), R-squared (R²), Explained Variance Score (EVS), and Mean Absolute Percentage Error (MAPE).
Visualization
Generated visualizations using matplotlib and seaborn for better interpretation of results, including time series plots, bar charts, and feature importance graphs.

3. Key Findings
Export Trends: The analysis revealed a significant fluctuation in sheep export quantities, peaking at nearly 99.9 million heads in 2013.
Top Exporters: Australia, Europe, and Africa consistently ranked among the leading exporters.
Strong Correlation: A positive correlation (r = 0.93) was found between export quantities and values, indicating that higher export volumes correspond to increased revenues.
Model Performance
Linear Regression: Achieved an R² of 1.0 for both export quantities and values, suggesting a near-perfect fit.
Random Forest: Performed better for predicting export values with an R² of 0.86.
K-Nearest Neighbors: Showed moderate performance with an R² of 0.83 for export values.
Support Vector Regression: Struggled to generalize, with poor performance metrics in both categories.

4. Implications and Applications
Market Strategy Optimization: Insights can help stakeholders optimize supply chains, set pricing strategies, and adapt to market fluctuations.
Policy Development: Findings can guide policymakers in creating effective trade policies, especially in volatile markets.
Sustainable Agriculture: The project supports sustainable agricultural practices by providing data-driven insights into market dynamics.

5. Ethical Considerations
Data Privacy: All data was sourced from publicly available datasets and anonymized to ensure compliance with privacy standards.
Bias Mitigation: The analysis focused on reducing model bias to provide fair and accurate predictions.
Transparency: Emphasized clear documentation of methodologies and results to build trust in the findings.

6. Future Directions
Feature Enhancements: Integrate additional factors like economic indicators, climate data, and trade policies for better accuracy.
Cloud Integration: Utilize cloud platforms for scalable data processing and storage.
Advanced Algorithms: Explore deep learning models to improve predictions, especially for volatile markets.

7. Contact
For further information or collaboration inquiries, please contact the project lead at zemelak.s.goraga@gmail.com.
