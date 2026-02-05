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
- **Interactive Dashboard:** Built an app/dashboard for real-time temperature visualization, daily change tracking, and efficiency analysis—empowering engineers to explore, review, and monitor remediation progress.  
- **Impact:** Enabled early warnings, optimized resource allocation, reduced operational costs, and improved overall remediation efficiency.

### 2. Cathodic Protection Data Platform
- **Web Scraping:** Authenticated and navigated complex tree structures on katodiskbeskyttelse.dk to download data programmatically.  
- **Data Management:** Organized scraped data into a logical Station/Sub-tree/Sensor folder hierarchy for easy access.  
- **Interactive Plotting App:** Developed an interface for dynamic filtering and time-series visualization of “On”, “Off”, and depolarization values against industry thresholds. 
- **Anomaly Detection App:** Integrated Machine Learning (IsolationForest, LocalOutlierFactor, OneClassSVM, EllipticEnvelope, KNN) to flag unusual readings and provide maintenance teams with an early warning system.  
- **Impact:** Transformed manual processes into an automated, insight-driven workflow—enabling proactive maintenance and extending structural lifespan.

### 3. GeoPlanner: Route Optimization for Field Technicians
- **Clustering:** Applied clustering to group tasks intelligently and ensure efficient assignments.  
- **Vehicle Routing:** Leveraged Google OR-Tools to solve the VRP, factoring in distances, technician schedules, and lodging constraints.  
- **Routing Engine:** Integrated OSRM for accurate travel-time and distance calculations.  
- **Interactive Maps:** Embedded interactive maps and visualizations for planners to fine-tune routes.  
- **Impact:** Delivered significant reductions in travel time and operating costs for field teams through optimized routing.

### 4. Near-Surface Groundwater: Hydrological Model Comparison
- **SQL Integration:** Designed efficient queries to extract and clean time-series groundwater data various databases and put them together in one SQL database.
- **API Integration:** Retrieved modeled groundwater levels via API for spatially specific model outputs.  
- **Data Transformation:** Converted coordinate systems (DVR90 → UTM/WGS84) and harmonized large geospatial time series from multiple sources.  
- **Visualization App:** Built a Streamlit tool allowing users to compare observed vs. modeled levels, upload custom CSVs, and interactively explore spatio-temporal discrepancies.  
- **Statistical Analysis:** Calculated metrics such as RMSE and mean bias to quantify model accuracy. Also created a risk & cost analysis for all municipalities in Denmark based on Envidan calculation methods.
- **Plotly Visuals:** Created dynamic charts to communicate model performance and guide improvement.  
- **Impact:** Enhanced understanding of hydrological model accuracy and delivered a dynamic analysis platform for environmental stakeholders.

---

## Market & Economic Analysis 📈

### 5. Used-Car Price Prediction & Deal Identification
<img width="923" height="880" alt="image" src="https://github.com/user-attachments/assets/e33ae43c-0eb5-4321-933b-6600ab3f44f4" />

- **Web Scraping:** Collected large datasets from different websites covering a broad range of vehicle attributes and prices.
- **Feature Engineering:** Crafted predictive features from raw listings.  
- **Ensemble Modeling:** Built and tuned ensembles for high-accuracy price predictions.  
- **Outlier Detection:** Flagged vehicles with price deviations as potential deals.
- **Visualization App:** Built a tool where you can put car attributes and get a predicted price.
- **Impact:** Created a tool to predict listing prices and highlight undervalued cars for buyers and sellers.

### 6. Danish Housing Market Analysis
<img width="971" height="397" alt="image" src="https://github.com/user-attachments/assets/9b0c455d-b444-4a56-a0c7-8d9dd29c636b" />

- **Data Collection:** Integrated APIs (Danmarks Statistik) and web scraping to gather housing, demographic, and economic data.  
- **Statistical Modeling:** Examined correlations between price/m² and factors like expenses, year built, rooms, and size.  
- **Trend Visualization:** Produced regional and temporal trend charts to reveal market dynamics and forecast developments.  
- **Impact:** Delivered insights into key drivers of Danish real-estate prices and regional variations.  

### 7. Consumer Confidence & Economic Forecasting
<img width="814" height="461" alt="image" src="https://github.com/user-attachments/assets/bdae6ff0-e771-4ff8-b03c-39b851a820cc" />
<img width="709" height="540" alt="image" src="https://github.com/user-attachments/assets/a0e450c7-0266-43a9-8a79-2d334b415f07" />

- **Macro Data Analysis:** Merged consumer confidence indices (DST, Dansk Industri) with historical consumption data.  
- **Time-Series Modeling:** Applied ARIMA and regression techniques to model confidence-driven spending trends.  
- **API Integration:** Pulled comparative data from Eurostat for broader economic context.  
- **Impact:** Improved understanding of how consumer sentiment predicts future economic activity.

### 8. Business Loan Accessibility
<img width="720" height="437" alt="image" src="https://github.com/user-attachments/assets/ef452a04-7d66-4343-a247-679c09075c9b" />
<img width="750" height="204" alt="image" src="https://github.com/user-attachments/assets/ca92e604-75a8-409b-bb23-41fa8c965681" />
<img width="988" height="574" alt="image" src="https://github.com/user-attachments/assets/89eab138-71d8-4841-9d23-0bd7925556a7" />

- **Data Aggregation:** Combined financial statements, headcount, and survey data on lending experiences.  
- **Linear Regression:** Identified predictors of successful loan applications (e.g., solvency ratios, balance sheet size, staff count).  
- **Statistical Interpretation:** Highlighted key factors influencing small-business loan access.  
- **Impact:** Provided actionable insights on what drives business creditworthiness.

### 9. GDP Time-Series Forecasting
<img width="652" height="634" alt="image" src="https://github.com/user-attachments/assets/f2f50c14-470e-40a0-a2b7-73752cf3af14" />
<img width="630" height="115" alt="image" src="https://github.com/user-attachments/assets/4a09764d-91c9-45ff-9603-f631fe6c18a3" />
<img width="631" height="278" alt="image" src="https://github.com/user-attachments/assets/0a111383-6948-4fc7-99ef-debd3b2e8a59" />

- **Modeling:** Tested ARIMA, exponential smoothing, and other methods on Denmark’s historical GDP data.  
- **Evaluation:** Benchmarked forecast accuracy using relevant metrics.  
- **Forecasting:** Projected future GDP trajectories to support economic planning.  
- **Impact:** Generated forward-looking GDP estimates to inform policy and strategy.

---

## Sports Analytics ⚽

### 10. Football Performance Analysis
<img width="610" height="661" alt="image" src="https://github.com/user-attachments/assets/ff75e47b-4c09-4e69-b80c-bf995671e6a2" />
<img width="360" height="281" alt="image" src="https://github.com/user-attachments/assets/5e83c148-f934-426a-bc4b-c502d5f43511" />
<img width="565" height="348" alt="image" src="https://github.com/user-attachments/assets/52b360b1-d4c9-4e7f-8261-502e8a602503" />
<img width="356" height="240" alt="image" src="https://github.com/user-attachments/assets/ad7705d9-e87b-451f-b0d4-fefbd1a0a4a5" />
<img width="488" height="408" alt="image" src="https://github.com/user-attachments/assets/e030cc4b-c815-4976-bb23-479900d5cdaf" />
<img width="579" height="412" alt="image" src="https://github.com/user-attachments/assets/010fe630-c022-4eb2-83a1-ebcae0a311d0" />
<img width="553" height="451" alt="image" src="https://github.com/user-attachments/assets/a25f5380-0b37-4b2a-9ee4-52770d0904cd" />
<img width="467" height="344" alt="image" src="https://github.com/user-attachments/assets/fe08e166-5e83-4c51-89db-87612689d22f" />
<img width="544" height="399" alt="image" src="https://github.com/user-attachments/assets/7fb86277-0248-4501-825d-18e51156dad7" />
<img width="584" height="415" alt="image" src="https://github.com/user-attachments/assets/c8d41d09-cd24-47d5-9dc2-cd725f7f0153" />
<img width="535" height="380" alt="image" src="https://github.com/user-attachments/assets/ef5a6519-e610-4c27-a4a7-57cea308c2f3" />
<img width="611" height="323" alt="image" src="https://github.com/user-attachments/assets/d74392d7-7501-484c-970b-441bea9c6190" />
<img width="611" height="330" alt="image" src="https://github.com/user-attachments/assets/cc812dc4-6f61-4ff2-9a17-a6f3653ca0d9" />
<img width="612" height="322" alt="image" src="https://github.com/user-attachments/assets/b56b897d-e501-415f-baa6-cd95eae4b592" />
<img width="612" height="322" alt="image" src="https://github.com/user-attachments/assets/d375b741-f803-477d-85a4-36c7c6b70edd" />
<img width="611" height="320" alt="image" src="https://github.com/user-attachments/assets/b8fc3002-02db-43f1-b685-f8d98920ec33" />


- **Data:** Processed raw tracking and event data (shot locations, pass networks, player movements).  
- **xG Model:** Built a logistic regression to predict shot success probability based on distance, angle, shot type, game situation, and defensive pressure.  
- **xP Model:** Predicted match outcomes (win/draw/loss) using xG and factors like opponent strength and home advantage.  
- **Visualization:** Charted xG flow and model results to make insights accessible.  
- **Theory:** Reflected on epistemological considerations (logical positivism vs. social constructivism) in sports data interpretation.  
- **Impact:** Delivered a data-driven framework for tactical analysis, player development, and recruitment.

### 11. Football Manager 2024 Scouting & Analysis Platform
<img width="1047" height="705" alt="image" src="https://github.com/user-attachments/assets/bfe0c9ac-dc42-4fa1-a8ed-4652da025fc8" />

- **Automated Data Extraction:** Scraped player attributes from Football Manager HTML exports using Python.  
- **Data Cleaning:** Standardized numeric values (salaries, transfer values), handled missing data, and resolved inconsistencies.  
- **Interactive Scouting App:** Developed a Streamlit interface enabling dynamic filtering by age, skills, salary, and custom attribute ranges.  
- **Attribute Analysis:** Conducted correlation studies to uncover key performance indicators for each position.  
- **Impact:** Transformed static game data into a powerful tool for informed scouting decisions in Football Manager.

---

# Let’s Connect! 🤝

I’m always excited to discuss new opportunities, share insights, or collaborate on innovative data science projects.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/rasmusstaaldinesen/)  
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:rasmusstaal@yahoo.dk)
