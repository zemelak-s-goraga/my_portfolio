
README: Analysis of Cattle Export Marketing Dataset Using Big Data Tools in Hadoop Ecosystem

1. Project Overview
This project explores the global cattle trade dynamics using historical livestock export data from 1961 to 2013. By leveraging big data technologies in the Hadoop ecosystem, the study provides insights into regional export patterns, identifies key contributors, and builds predictive models for future export trends. The analysis focuses on integrating historical data stored in Hive with real-time streaming data from Kafka to forecast cattle export volumes using PySpark’s RandomForestRegressor model, achieving an R² score of 0.92.

The project emphasizes the potential for data-driven decision-making to optimize marketing strategies in the agricultural sector, ultimately enhancing trade efficiency and sustainability.

2. Methodology
Environment Setup
The project begins with configuring a Docker-based big data environment that includes ZooKeeper, Kafka, HDFS, Hive, and NiFi. This setup ensures consistent configurations and efficient resource management.

Data Ingestion & Storage
NiFi fetches data from GitHub, converts it, and streams it to Kafka.
HDFS stores the dataset for long-term analysis, while Hive tables enable efficient querying.
Data Analysis & Processing
Hive performs exploratory data analysis (EDA) to identify export trends.
PySpark processes data and builds a predictive model using RandomForestRegressor, leveraging both historical data and real-time inputs.
Predictive Modeling
The RandomForestRegressor model was trained using PySpark to forecast export quantities, achieving:

R² Score: 0.92, indicating high accuracy.
RMSE: 438,351 units, showing areas for improvement, especially for volatile markets like Argentina.

3. Key Findings
Trends Over Time: Export quantities peaked in 2010, driven by Western Europe and the Americas.
Top Exporters: Australia, Brazil, and the United States consistently maintained high export volumes.
Volatility: Argentina exhibited fluctuations, indicating the need for more complex features in predictive models.
Predictive Accuracy: The model performed exceptionally well for stable exporters, with potential enhancements for volatile markets.

4. Implications and Applications
The project demonstrates the potential for big data analytics to optimize decision-making in the agricultural sector:

Policy Influence: Identifying how economic policies impact export quantities can guide regulatory changes.
Market Strategies: Reliable forecasts help stakeholders optimize supply chains and pricing strategies.
Real-Time Monitoring: The integration of real-time streaming data enables responsive adjustments to market changes.

5. Ethical Considerations
Data Privacy: All data used was publicly available and anonymized.
Fair Use: The project focuses on objective analysis to support data-driven strategies, not influencing market behaviors for unfair advantages.
Transparency: The findings are presented with the intent of promoting agricultural sustainability.

6. Future Directions
Enhanced Feature Engineering: Incorporate additional variables, such as economic indicators, climate data, and trade policies, to improve model accuracy.
Cloud Integration: Migrate to cloud platforms like AWS or Azure for better scalability and real-time data processing.
Machine Learning Algorithms: Explore deep learning models to capture non-linear patterns in volatile markets like Argentina.


Contact
For further information or collaboration inquiries, please contact the project lead at zemelak.s.goraga@gmail.com.
