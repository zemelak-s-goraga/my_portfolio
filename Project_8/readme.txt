
README: Predictive Analysis of SpaceX Falcon 9 Rocket Launch Success

1. Project Overview
This project focuses on predicting the success of SpaceX Falcon 9 rocket landings by analyzing historical launch data. By leveraging data science techniques such as exploratory data analysis (EDA), interactive visual analytics, and machine learning models, the objective was to understand the factors influencing successful landings and optimize future launches. The project utilized data collected from the SpaceX API and web scraping, followed by data wrangling, visualization, and predictive analytics to forecast landing outcomes. The results provide actionable insights to help SpaceX reduce launch costs and increase efficiency.

2. Methodology
Data Collection & Wrangling
Data Sources: Data was gathered using the SpaceX API and web scraping from Wikipedia.
Data Cleaning: Missing values were handled, particularly in the LandingPad and PayloadMass columns.
Feature Engineering: One-hot encoding was applied to categorical variables like BoosterVersion.
Exploratory Data Analysis (EDA)
Visualized relationships between flight number, launch site, orbit type, and payload mass.
Conducted SQL queries to analyze mission outcomes, payload mass, and launch success trends.
Interactive Visual Analytics
Folium Maps: Created interactive maps to visualize launch sites and their success rates.
Plotly Dash: Built dashboards with filters for payload ranges, launch sites, and outcomes.
Predictive Modeling
Applied machine learning algorithms, including:
Decision Tree
Support Vector Machine (SVM)
Random Forest
K-Nearest Neighbors (KNN)
Models were trained and tuned to improve prediction accuracy, with DecisionTree performing the best (accuracy: 87.3%).

3. Key Findings
Launch Site Success: KSC LC-39A had the highest success rate among all launch sites.
Orbit Success Rates: Orbits like ES-L1, GEO, HEO, and SSO had the highest success rates.
Payload Influence: Higher payload mass generally led to more successful landings, particularly in low Earth orbits.
Yearly Trends: Launch success rates improved significantly from 2013 onwards, peaking in 2019.

4. Implications and Applications
The insights from this project can help optimize SpaceX's operations:

Target Launch Sites: Focus on high-performing sites like KSC LC-39A to maximize success rates.
Payload Optimization: Fine-tune payload mass for improved landing success, especially for orbits like LEO and ISS.
Predictive Insights: Leverage the DecisionTree model to inform decision-making for future launches, reducing costs and improving reliability.

5. Ethical Considerations
Data Privacy: The analysis was conducted using publicly available datasets, ensuring compliance with privacy standards.
Transparency: Models and findings were documented clearly to maintain transparency.
Bias Mitigation: Efforts were made to avoid model bias and ensure fair and accurate predictions.

6. Future Directions
Real-Time Data Integration: Incorporate real-time launch data to continuously update models.
Advanced Feature Engineering: Include additional features like weather conditions and wind speed for improved accuracy.
Expand Analysis: Apply the methodology to other rocket types, such as Falcon Heavy, to broaden insights.

7. Contact
For further information or collaboration inquiries, please contact the project lead at zemelak.s.goraga@gmail.com.
