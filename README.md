# Hello, I’m Rasmus 👋

Welcome to my corner of GitHub! I am a **Full Stack Data Scientist** with a Professional Bachelor’s degree in Data Analytics from CPHBusiness. I thrive on transforming raw data into actionable insights and building robust, production-ready solutions that truly make a difference.

My journey at Krüger A/S in the Digital Innovation department has been incredibly rewarding. What began as an internship—where I was the first and only team member—rapidly evolved into a role that constantly challenges me to apply data analysis, software development, and optimization techniques, especially within the environmental and utilities sectors. I love diving deep into data to uncover opportunities and then bringing those insights to life through innovative applications.

---

## Core Skills 🛠️

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-239120?style=for-the-badge&logo=plotly&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2671E6?style=for-the-badge&logo=githubactions&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)
![OR-Tools](https://img.shields.io/badge/OR--Tools-FF6700?style=for-the-badge&logo=googleg4g&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white)
![BeautifulSoup](https://img.shields.io/badge/BeautifulSoup-1A1A1A?style=for-the-badge&logo=beautifulsoup&logoColor=white)
![Requests](https://img.shields.io/badge/Requests-1A1A1A?style=for-the-badge&logo=python&logoColor=white)
![Geopy](https://img.shields.io/badge/Geopy-1A1A1A?style=for-the-badge&logo=python&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-1A1A1A?style=for-the-badge&logo=xgboost&logoColor=white)

---

## Projects

Below is a selection of projects that showcase my approach to tackling challenges and exploring diverse datasets. While some client projects remain confidential, I’ve highlighted my role, the technologies I used, and the impact of my work.

---

## Environmental Data Science & Optimization 🌿

### 1. Bachelor Project: Anomaly Detection & Soil Remediation Optimization
- **Problem:** Detect unusual patterns and inefficiencies in complex soil remediation processes using sensor data.  
- **Data Processing:** Cleaned, transformed, and engineered features from temperature sensors at various depths.  
- **Anomaly Detection:** Implemented and compared Isolation Forest, One-Class SVM, and Local Outlier Factor to accurately flag deviations indicating potential issues or optimization opportunities.  
- **Geospatial Visualization:** Used QGIS to map sensor locations and spatial distribution of anomalies, providing vital geographic context.  
- **Interactive Dashboard:** Built a Streamlit app for real-time temperature visualization, daily change tracking, and efficiency analysis—empowering engineers to explore, review, and monitor remediation progress.  
- **✨ Impact:** Enabled early warnings, optimized resource allocation, reduced operational costs, and improved overall remediation efficiency.

### 2. Cathodic Protection Data Platform
- **Web Scraping:** Authenticated and navigated complex tree structures on katodiskbeskyttelse.dk to download Excel data programmatically.  
- **Data Management:** Organized scraped data into a logical Station/Sub-tree/Sensor folder hierarchy for easy access.  
- **Interactive Plotting App:** Developed a Streamlit interface for dynamic filtering and time-series visualization of “On”, “Off”, and DP24 (depolarization) values against industry thresholds (-750 mV, -900 mV).  
- **Anomaly Detection App:** Integrated multiple ML algorithms (IsolationForest, LocalOutlierFactor, OneClassSVM, EllipticEnvelope, KNN) in Streamlit to flag unusual readings and provide maintenance teams with an early warning system.  
- **✨ Impact:** Transformed manual processes into an automated, insight-driven workflow—enabling proactive maintenance and extending structural lifespan.

### 3. GeoPlanner: Route Optimization for Field Technicians
- **Clustering:** Applied clustering to group tasks intelligently and ensure efficient assignments.  
- **Vehicle Routing:** Leveraged Google OR-Tools to solve the VRP, factoring in distances, technician schedules, and lodging constraints.  
- **Routing Engine:** Integrated OSRM for accurate travel-time and distance calculations.  
- **Interactive Maps:** Embedded interactive maps and visualizations in Streamlit for planners to fine-tune routes.  
- **✨ Impact:** Delivered significant reductions in travel time and operating costs for field teams through optimized routing.

### 4. Near-Surface Groundwater: Hydrological Model Comparison
- **SQL Integration:** Designed efficient queries to extract and clean time-series groundwater data from a SQL Server database.  
- **API Integration:** Retrieved modeled groundwater levels via Dataforsyningen.dk’s API for spatially specific model outputs.  
- **Data Transformation:** Converted coordinate systems (DVR90 → UTM/WGS84) and harmonized large geospatial time series from multiple sources.  
- **Visualization App:** Built a Streamlit tool allowing users to compare observed vs. modeled levels, upload custom CSVs, and interactively explore spatio-temporal discrepancies.  
- **Statistical Analysis:** Calculated metrics such as RMSE and mean bias to quantify model accuracy.  
- **Plotly Visuals:** Created dynamic charts to communicate model performance and guide improvement.  
- **✨ Impact:** Enhanced understanding of hydrological model accuracy and delivered a dynamic analysis platform for environmental stakeholders.

---

## Market & Economic Analysis 📈

### 5. Used-Car Price Prediction & Deal Identification
- **Web Scraping:** Collected large datasets from Bilbasen.dk covering a broad range of vehicle attributes.  
- **Feature Engineering:** Crafted predictive features (e.g., heated seats, navigation) from raw listings.  
- **Ensemble Modeling:** Built and tuned XGBoost ensembles for high-accuracy price predictions.  
- **Outlier Detection:** Flagged vehicles with price deviations as potential deals.  
- **✨ Impact:** Created a tool to predict listing prices and highlight undervalued cars for buyers and sellers.

### 6. Danish Housing Market Analysis
- **Data Collection:** Integrated APIs (Danmarks Statistik) and web scraping to gather housing, demographic, and economic data.  
- **Statistical Modeling:** Examined correlations between price/m² and factors like expenses, year built, rooms, and size.  
- **Trend Visualization:** Produced regional and temporal trend charts to reveal market dynamics and forecast developments.  
- **✨ Impact:** Delivered insights into key drivers of Danish real-estate prices and regional variations.  

### 7. Consumer Confidence & Economic Forecasting
- **Macro Data Analysis:** Merged consumer confidence indices (DST, Dansk Industri) with historical consumption data.  
- **Time-Series Modeling:** Applied ARIMA and regression techniques to model confidence-driven spending trends.  
- **API Integration:** Pulled comparative data from Eurostat for broader economic context.  
- **✨ Impact:** Improved understanding of how consumer sentiment predicts future economic activity.

### 8. Business Loan Accessibility
- **Data Aggregation:** Combined financial statements, headcount, and survey data on lending experiences.  
- **Linear Regression:** Identified predictors of successful loan applications (e.g., solvency ratios, balance sheet size, staff count).  
- **Statistical Interpretation:** Highlighted key factors influencing small-business loan access.  
- **✨ Impact:** Provided actionable insights on what drives business creditworthiness.

### 9. GDP Time-Series Forecasting
- **Modeling:** Tested ARIMA, exponential smoothing, and other methods on Denmark’s historical GDP data.  
- **Evaluation:** Benchmarked forecast accuracy using relevant metrics.  
- **Forecasting:** Projected future GDP trajectories to support economic planning.  
- **✨ Impact:** Generated forward-looking GDP estimates to inform policy and strategy.

---

## Sports Analytics ⚽

### 10. Football Performance Analysis
- **Data:** Processed raw tracking and event data (shot locations, pass networks, player movements).  
- **xG Model:** Built a logistic regression to predict shot success probability based on distance, angle, shot type, game situation, and defensive pressure.  
- **xP Model:** Predicted match outcomes (win/draw/loss) using xG and factors like opponent strength and home advantage.  
- **Visualization:** Charted xG flow and model results to make insights accessible.  
- **Theory:** Reflected on epistemological considerations (logical positivism vs. social constructivism) in sports data interpretation.  
- **✨ Impact:** Delivered a data-driven framework for tactical analysis, player development, and recruitment.

### 11. Football Manager 2024 Scouting & Analysis Platform
- **Automated Data Extraction:** Scraped player attributes from Football Manager HTML exports using Python.  
- **Data Cleaning:** Standardized numeric values (salaries, transfer values), handled missing data, and resolved inconsistencies.  
- **Interactive Scouting App:** Developed a Streamlit interface enabling dynamic filtering by age, skills, salary, and custom attribute ranges.  
- **Attribute Analysis:** Conducted correlation studies to uncover key performance indicators for each position.  
- **✨ Impact:** Transformed static game data into a powerful tool for informed scouting decisions in Football Manager.

---

# Let’s Connect! 🤝

I’m always excited to discuss new opportunities, share insights, or collaborate on innovative data science projects.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/rasmusstaaldinesen/)  
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:rasmusstaal@yahoo.dk)
