# Project-Directory
Welcome to my project showcase! This repository serves as a centralized directory for my data analytics projects. Each project showcases a specific set of skills, tools, and techniques I have mastered throughout my learning journey. Click on any project title to view its full details and implementation.

---

## Projects

### [Sales Pipeline ETL & Tableau/Power BI Dashboard: GearQuest Analysis](https://github.com/jastro-dev/gearquest-sales-pipeline-etl-tableau-power-bi-dashboard)
**Description:** A portfolio project that implements a full ETL pipeline to extract, transform, and load Excel data into a `.hyper` Tableau extract file and a PostgreSQL database. This enables seamless integration with both Tableau and Power BI, facilitating interactive business intelligence dashboards for sales pipeline insights.

**Key Features:**
- **End-to-End ETL Pipeline:** Extracts data from multiple Excel files, transforms it using PySpark, and loads it into Tableau Hyper and PostgreSQL.
- **Dual Output for BI Tools:** Generates `.hyper` files for Tableau and structured tables in PostgreSQL for Power BI.
- **Automated Data Transformation:** Cleans and integrates data, merging relevant tables and handling duplicates efficiently.
- **Cloud-Ready Architecture:** Designed for deployment in AWS, GCP, or Azure environments.
- **Reproducible Workflow:** Includes `requirements.txt` and `.env` file for automated setup.
- **Interactive Dashboards:**
  - **Tableau Dashboard:** Utilizes `.hyper` extracts for seamless visualization.
  - **Power BI Dashboard:** Connects directly to PostgreSQL for real-time data updates.

**Tools Used:**
- **Python:** PySpark, tableauhyperapi, psycopg2, pandas (used in initial notebook for prototyping)
- **Databases:** PostgreSQL
- **Visualization:** Tableau, Power BI

---

### [Operational Efficiency & Predictive Analytics: Candy Distribution](https://github.com/jastro-dev/operational-efficiency-benchmarking-candy-distributor)
**Description:** A portfolio project that benchmarks and optimizes the operational efficiency of a candy manufacturing and distribution business. It integrates multiple data sources, implements a full data pipeline, performs exploratory analysis, builds predictive models, and features an interactive Power BI dashboard for continuous monitoring and strategic decision-making.

**Key Features:**
- **Data Pipeline:** Cleans, transforms, and integrates sales, production, and geographic data, storing results in SQLite/MySQL.
- **Exploratory Data Analysis:** Identifies sales trends, production efficiency, and shipping performance.
- **Predictive Modeling:** Implements classification models (Logistic Regression, Decision Trees, Random Forest, XGBoost) to predict late shipments, with feature selection for model optimization.
- **Feature Engineering:** Includes distance calculations, lead time estimation, and geographic mapping using `pgeocode` and the Haversine formula.
- **Interactive Power BI Dashboard:**
  - **Quarterly KPI Performance:** Tracks revenue against division-level targets.
  - **Lead Time vs. Late Probability Analysis:** Visualizes the relationship between lead time and late shipment probability, identifying high-risk products.
  - **Total and Monthly Revenue Trends:** Provides detailed breakdowns by division, factory, product, region, and shipping mode.
  - **Target Gap Analysis:** Highlights shortfalls in sales performance based on 2024 targets.
  - **Data-Driven Decision Support:** Enables continuous monitoring and strategic adjustments.

**Tools Used:**
- **Python:** pandas, scikit-learn, XGBoost, matplotlib, seaborn, pgeocode
- **Databases:** MySQL, SQLite
- **Visualization:** Power BI

---

### [Brazil Flight Trends Analysis for Holiday Season 2024 (CPP Bronco Datathon 2024)](https://github.com/jastro-dev/cpp-bronco-datathon-fall-2024)
**Description:** Analysis of Brazil flight data to identify the best cities to visit during the 2024 holiday season. Secured 3rd place.

**Key Features:** Seasonal pattern analysis, pricing trends, and compelling visualizations aligned with stakeholder priorities for strategic decision-making.

**Tools Used:** Python

**Note:** This project was part of the Cal Poly Pomona Bronco Datathon 2024, where I collaborated with a team to address real-world travel challenges using analytical methods.

---

### [Tableau Dashboard Replication: Real GDP Growth Visualization](https://github.com/jastro-dev/tableau-imf-data-dashboard)  
**Description:** Replicated the IMF's GDP Growth dashboard in Tableau, automating Python pipelines and enhancing dataset completeness through additional data integration.

**Key Features:** Interactive choropleth map for country-wise GDP growth, trend line charts for historical and forecasted GDP trends, sortable country/region lists, and dynamic filters for year and category selection, incorporating calculated fields for GDP categorization and parameters for dynamic year selection (1990–2023).  

**Tools Used:** Tableau Desktop, Python (for data processing), Excel  

---

### [Power BI Dataquest Course Improvement Analysis](https://github.com/jastro-dev/power-bi-dataquest-course-improvement-analysis)
**Description:** A Power BI project focused on identifying underperforming courses at Dataquest using lesson completion rates and Net Promoter Scores (NPS).

**Key Features:** Comprehensive dashboards for lesson completion and NPS trends, actionable insights, and recommendations for course improvements.

**Tools Used:** Power BI

---

### [Stack Exchange Popular Data Science Questions Analysis](https://github.com/jastro-dev/dq-11-stackexchange-popular-questions)
**Description:** A data analysis project exploring popular data science questions from Stack Exchange. Focuses on identifying trending topics and optimal categories for new questions.

**Key Features:** SQL data extraction, tag analysis, time series analysis, and co-occurrence mapping.

**Tools Used:** T-SQL, Python

---

### [Northwind Traders SQL Window Functions Practice](https://github.com/jastro-dev/dq-09-sql-window-functions-northwind-traders)
**Description:** A hands-on practice project using PostgreSQL window functions with the Northwind Traders dataset. Focuses on advanced SQL analytics and reporting.

**Key Features:** Advanced window functions, CTEs, sales analysis, and customer segmentation.

**Tools Used:** PostgreSQL

---

### [Customers and Products Analysis](https://github.com/jastro-dev/dq-08-sql-customers-and-products-analysis)
**Description:** Analysis of product performance and customer profitability using SQL. Highlights include lifetime value (LTV) calculations and targeted marketing recommendations.

**Key Features:** Product restocking recommendations, VIP customer segmentation, and revenue analysis.

**Tools Used:** SQLite

---

### [Twitter Sentiment Analysis Project](https://github.com/jastro-dev/twitter-sentiment-analysis)
**Description:** Sentiment analysis of tweets using natural language processing (NLP) techniques and machine learning models.

**Key Features:** Text preprocessing, multiple model implementations (Logistic Regression, Random Forest, BERT), and GPU-accelerated training.

**Tools Used:** Python

---

### [Heart Disease Classification using Logistic Regression](https://github.com/jastro-dev/dq-ds-05-heart-disease-classification)  
**Description:** Built a logistic regression model to predict the presence of heart disease using patient health indicators from the **UCI Heart Disease dataset**. Followed a structured **machine learning pipeline**, including data preprocessing, feature selection, model training, and evaluation.  

**Key Features:** Data cleaning and imputation, correlation analysis for feature selection, logistic regression modeling, and performance evaluation using accuracy, sensitivity, and specificity.  

**Tools Used:** Python (pandas, scikit-learn, matplotlib, seaborn)  

---

### [Employee Productivity Prediction using Tree-based Algorithms](https://github.com/jastro-dev/dq-ds-06-employee-productivity-prediction-tree-models)
**Description:** Machine learning project analyzing garment worker productivity to predict employee performance based on key workplace factors.

**Key Features:** Data cleaning, feature engineering, binary classification of productive vs. unproductive employees, model comparison (Decision Trees, Random Forest, XGBoost), class balancing, and model evaluation using accuracy scores, confusion matrices, and feature importance analysis.

**Tools Used:** Python (pandas, scikit-learn, XGBoost, matplotlib, seaborn)

**Note:** This project focuses on the importance of exploratory data analysis, data preprocessing, and model evaluation in predictive analytics.

---

### [New York City Schools Data Analysis](https://github.com/jastro-dev/dq-06-nyc-high-school-analysis)
**Description:** Analysis of NYC school performance, demographics, and safety scores to uncover meaningful correlations.

**Key Features:** Correlation analysis, demographic insights, and SAT performance visualizations.

**Tools Used:** Python

---

### [Employee Exit Survey Analysis](https://github.com/jastro-dev/dq-05-clean-analyze-employee-exit-surveys)
**Description:** Analysis of exit surveys from two educational institutions, focusing on dissatisfaction trends by service length and age.

**Key Features:** Service length analysis, age group dissatisfaction patterns, and targeted retention recommendations.

**Tools Used:** Python

---

## About Me
Feel free to connect with me on [LinkedIn](https://www.linkedin.com/in/jeremy-r-castro/) or explore more of my work on [GitHub](https://github.com/jastro-dev).

Thank you for visiting my projects!
