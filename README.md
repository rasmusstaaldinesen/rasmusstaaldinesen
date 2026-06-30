# Hi, I'm Rasmus.

**Data Analyst / Data Scientist working with applied machine learning, dashboards, automation, forecasting and decision-support tools.**

I work best when I can take a messy dataset, an unclear problem or a manual workflow and turn it into something practical: a dashboard, model, app, automation or analytical tool that other people can actually use.

At **Veolia Digital Innovation**, I have led several internal data projects from problem framing and data extraction to modelling, validation, dashboards and usable tools. Most of my work sits close to consulting engineers and domain specialists, where the goal is not just to analyze data, but to make complex environmental, operational and commercial data easier to understand and act on.

---

## What I Work With

* Applied data science and machine learning
* Data analysis, dashboards and decision-support tools
* Forecasting, anomaly detection and model validation
* Environmental, wastewater, groundwater and operational data
* Geospatial analysis and route optimization
* Web scraping, APIs, data cleaning and feature engineering
* Python, SQL, R, Streamlit, Shiny, Plotly, scikit-learn and XGBoost


## Core Technologies

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

## Current Focus: Applied Data Projects at Veolia

At **Veolia Digital Innovation**, I work independently on data projects in collaboration with consulting engineers and domain specialists. I have been lead on several internal projects, often taking them from an unclear problem or manual workflow to a working analytical tool, dashboard or model.

Examples of my work include:

* wastewater forecasting and model validation
* anomaly detection for soil remediation sensor data
* groundwater model comparison using SQL, APIs, Streamlit and Plotly
* cathodic protection monitoring and anomaly detection
* route optimization for field technicians using clustering, OSRM and Google OR-Tools
* dashboards and decision-support tools for environmental and operational data

---
# Selected Projects

## Environmental, Operational & Applied Data Science

### 1. Pretreatment Facility: Wastewater Forecasting & Model Validation

**Context:** Applied machine learning project using wastewater treatment data from Pretreatment Facility.

**Problem:**
Wastewater treatment plants operate under changing load conditions. Forecasting can support better operational awareness, but only if models are evaluated realistically and compared against simple baselines.

**What I did:**

* Built forecasting workflows for next-day total inflow
* Worked with operational wastewater process data and high-load situations
* Compared machine learning models against simple baseline approaches such as persistence
* Built validation workflows for high-load classification and regression tasks
* Used temporal splits / rolling-origin style validation to reduce leakage risk
* Evaluated model performance with a focus on realistic deployment conditions
* Structured outputs into clear metrics and reports for model comparison

**Target examples:**

* next-day total flow forecasting
* high-load classification
* NH4-related regression and process analysis

**Tools:** Python, pandas, scikit-learn, forecasting, regression, classification, temporal validation, model evaluation

**Why it matters:**
This project shows practical data science on real operational process data: forecasting, validation, baseline comparison and the discipline to test whether machine learning actually adds value.

---

### 2. Anomaly Detection & Soil Remediation Optimization

**Context:** Bachelor project and applied environmental data science work.

**Problem:**
Soil remediation processes generate complex sensor data. Unusual temperature patterns can indicate inefficiencies, process issues or optimization opportunities.

**What I did:**

* Cleaned, transformed and engineered features from temperature sensor data
* Compared anomaly detection methods including Isolation Forest, One-Class SVM and Local Outlier Factor
* Used QGIS to map sensor locations and spatial patterns
* Built an interactive dashboard for temperature visualization, daily change tracking and efficiency analysis
* Translated technical model outputs into something engineers could inspect and use

**Tools:** Python, pandas, scikit-learn, Isolation Forest, LOF, One-Class SVM, QGIS, dashboarding

**Why it matters:**
The project shows how machine learning can support environmental engineering by making process deviations easier to detect and investigate.

<details>
  <summary>See more 📸</summary>
  <img width="590" height="858" alt="image" src="https://github.com/user-attachments/assets/266df907-adc7-4126-ba65-db1c5639aa3c" />
  <img width="512" height="327" alt="image" src="https://github.com/user-attachments/assets/10e7c0cc-be98-4a4e-ae6a-f09b308151f4" />
  <img width="568" height="317" alt="image" src="https://github.com/user-attachments/assets/0c0bb8a4-2928-4eff-818a-4e9b21020399" />
  <img width="918" height="607" alt="image" src="https://github.com/user-attachments/assets/04d7c411-169b-4db7-a165-cca170cbcd8b" />
  <img width="504" height="498" alt="image" src="https://github.com/user-attachments/assets/19f2bc70-b1f6-44b9-ab66-1f645a41cc02" />
  <img width="904" height="352" alt="image" src="https://github.com/user-attachments/assets/f87fc280-8d58-47ef-aad0-84b1a3343d3f" />
</details>

---

### 3. Groundwater Model Comparison Tool

**Context:** Environmental analytics and hydrological model comparison.

**Problem:**
Observed groundwater levels and modelled groundwater levels need to be compared across time, location and data sources.

**What I did:**

* Extracted and cleaned time-series groundwater data using SQL
* Retrieved modelled groundwater levels through APIs
* Harmonized geospatial and temporal data from multiple sources
* Converted coordinate systems and prepared data for comparison
* Built a Streamlit tool for comparing observed vs. modelled levels
* Calculated model performance metrics such as RMSE and mean bias
* Created Plotly visualizations to make model differences easier to explore
* Built risk and cost analysis views for municipalities based on domain-specific calculation methods

**Tools:** SQL, Python, APIs, Streamlit, Plotly, geospatial data, coordinate transformation, RMSE, bias

**Why it matters:**
The tool helps domain specialists inspect model performance and understand where groundwater models align or differ from observed data.


<details>
  <summary>See more 📸</summary>
  <img width="1708" height="890" alt="image" src="https://github.com/user-attachments/assets/8802f065-9c2d-485e-a272-d5cc98ddbce7" />
  <img width="1420" height="847" alt="image" src="https://github.com/user-attachments/assets/d5dbe097-1a6b-46b2-be22-673d6563744f" />
  <img width="1438" height="715" alt="image" src="https://github.com/user-attachments/assets/4bf75a78-8e57-4212-a59d-1bc123d518e9" />
  <img width="1710" height="891" alt="image" src="https://github.com/user-attachments/assets/e6d2df2c-041f-4d6a-849b-622520a6c84e" />
</details>

---

### 4. Cathodic Protection Data Platform

**Context:** Operational monitoring and automation project.

**Problem:**
Cathodic protection data was difficult and time-consuming to extract, structure and monitor manually.

**What I did:**

* Automated authenticated data extraction from a complex source
* Structured station, sub-tree and sensor data into a usable hierarchy
* Built interactive time-series visualizations for On, Off and depolarization values
* Added anomaly detection methods to flag unusual readings
* Helped turn manual monitoring into a more structured analytical workflow

**Tools:** Python, web scraping, time-series analysis, anomaly detection, interactive visualization

**Methods:** Isolation Forest, Local Outlier Factor, One-Class SVM, EllipticEnvelope, KNN

**Why it matters:**
The project made technical monitoring data easier to inspect, helping users identify potential issues earlier.

---

### 5. GeoPlanner: Route Optimization for Field Technicians

**Context:** Planning and optimization for field work.

**Problem:**
Field technician tasks need to be planned efficiently while considering distance, travel time, schedules and lodging constraints.

**What I did:**

* Used clustering to group field tasks intelligently
* Integrated OSRM for travel-time and distance calculations
* Used Google OR-Tools to solve route optimization problems
* Built interactive maps and planning views for route inspection
* Designed the tool around real planning constraints rather than only theoretical optimization

**Tools:** Python, clustering, OSRM, Google OR-Tools, geospatial analysis, interactive maps

**Why it matters:**
The project shows how optimization can support operational planning and reduce unnecessary travel

----

## Market, Economic & Product Analytics

### 6. Used-Car Price Prediction & Deal Finder

**Context:** Portfolio project combining scraping, modelling and an interactive app.

**Problem:**
Used-car prices are difficult to compare because listings differ across model, year, mileage, fuel type, equipment and other attributes.

**What I did:**

* Scraped and cleaned used-car listing data
* Engineered features from raw listing attributes
* Built price prediction models to estimate fair listing value
* Used model deviations to flag potentially underpriced cars
* Built an interactive app where users can input vehicle attributes and receive a predicted price

**Tools:** Python, web scraping, pandas, feature engineering, machine learning, outlier detection, Streamlit

**Live app:** [rasmusdinesen.dk](https://rasmusdinesen.dk)

**Why it matters:**
The project shows the full workflow from data collection to model development and a usable product.


<details>
  <summary>See more 📸</summary>
  <img width="923" height="880" alt="image" src="https://github.com/user-attachments/assets/e33ae43c-0eb5-4321-933b-6600ab3f44f4" />
  <img width="1020" height="356" alt="image" src="https://github.com/user-attachments/assets/c0b13e17-b4af-4b3a-a824-1c0a6dcd6123" />
  <img width="818" height="581" alt="image" src="https://github.com/user-attachments/assets/4b8982bd-b866-4ca1-a5d8-f39b9f357317" />
  <img width="879" height="784" alt="image" src="https://github.com/user-attachments/assets/55dba5c0-cf7e-4e88-b8ef-d2fd80a955e9" />
  <img width="639" height="335" alt="image" src="https://github.com/user-attachments/assets/1b420a54-3107-47bf-88be-ffe9b7b119b0" />
  <img width="1001" height="350" alt="image" src="https://github.com/user-attachments/assets/2ad59ce8-70bb-4196-aa03-76cf5139f26b" />
  <img width="1001" height="423" alt="image" src="https://github.com/user-attachments/assets/a9f852e4-6781-410d-afa2-691027c7615d" />
  <img width="685" height="546" alt="image" src="https://github.com/user-attachments/assets/52d58a73-d64d-404b-b4d9-e9c380c627f7" />
</details>

---

### 7. Consumer Confidence & Economic Forecasting

**Context:** Academic/economic analysis project.

**Problem:**
Consumer confidence may contain signals about future private consumption, but the relationship needs to be tested statistically.

**What I did:**

* Combined Danish consumer confidence data with historical private consumption data
* Worked with data from sources such as Danmarks Statistik, Dansk Industri and Eurostat
* Applied regression, PCR and time-series methods
* Evaluated relationships between sentiment and spending
* Communicated findings through visualizations and statistical interpretation

**Tools:** R, regression, ARIMA, PCR, economic data, forecasting, visualization

**Why it matters:**
The project shows my ability to work with economic indicators, uncertainty and statistical modelling.

<details>
  <summary>See more 📸</summary>
  <img width="814" height="461" alt="image" src="https://github.com/user-attachments/assets/bdae6ff0-e771-4ff8-b03c-39b851a820cc" />
  <img width="709" height="540" alt="image" src="https://github.com/user-attachments/assets/a0e450c7-0266-43a9-8a79-2d334b415f07" />
</details>

---

### 8. Danish Housing Market Analysis

**Context:** Market analysis and data collection project.

**Problem:**
Housing prices vary by geography, property characteristics and market conditions, and the drivers need to be explored with data.

**What I did:**

* Collected housing and demographic data through APIs and scraping
* Cleaned and structured data for analysis
* Analyzed relationships between price per square meter and variables such as size, rooms, year built and expenses
* Created visualizations of regional and temporal patterns

**Tools:** R, Python, APIs, web scraping, regression, visualization

**Why it matters:**
The project shows my ability to combine multiple data sources and turn market data into interpretable insights.

<details>
  <summary>See more 📸</summary>
  <img width="971" height="397" alt="image" src="https://github.com/user-attachments/assets/9b0c455d-b444-4a56-a0c7-8d9dd29c636b" />
</details>

---

### 9. Business Loan Accessibility

**Context:** Statistical analysis of business lending.

**Problem:**
Access to business loans depends on financial and organizational factors, but the important predictors need to be identified.

**What I did:**

* Combined financial statements, headcount data and survey responses
* Applied regression methods to identify relevant predictors
* Interpreted factors such as solvency ratios, balance sheet size and staff count
* Communicated findings in a business-oriented way

**Tools:** R, regression, statistical analysis, financial data

**Why it matters:**
The project shows my ability to connect statistical analysis with business questions.

<details>
  <summary>See more 📸</summary>
  <img width="720" height="437" alt="image" src="https://github.com/user-attachments/assets/ef452a04-7d66-4343-a247-679c09075c9b" />
  <img width="750" height="204" alt="image" src="https://github.com/user-attachments/assets/ca92e604-75a8-409b-bb23-41fa8c965681" />
  <img width="988" height="574" alt="image" src="https://github.com/user-attachments/assets/89eab138-71d8-4841-9d23-0bd7925556a7" />
</details>

### 9.1 GDP Time-Series Forecasting
- **Modeling:** Tested ARIMA, exponential smoothing, and other methods on Denmark’s historical GDP data.  
- **Evaluation:** Benchmarked forecast accuracy using relevant metrics.  
- **Forecasting:** Projected future GDP trajectories to support economic planning.  
- **Impact:** Generated forward-looking GDP estimates to inform policy and strategy.

<details>
  <summary>See more 📸</summary>
  <img width="652" height="634" alt="image" src="https://github.com/user-attachments/assets/f2f50c14-470e-40a0-a2b7-73752cf3af14" />
  <img width="630" height="115" alt="image" src="https://github.com/user-attachments/assets/4a09764d-91c9-45ff-9603-f631fe6c18a3" />
  <img width="631" height="278" alt="image" src="https://github.com/user-attachments/assets/0a111383-6948-4fc7-99ef-debd3b2e8a59" />
</details>

---

## Sports Analytics ⚽

## Sports Analytics

### 10. Football Performance Analysis

**Context:** Sports analytics and event-data modelling.

**Problem:**
Football performance is complex, and event data can be used to model shot quality, match dynamics and tactical patterns.

**What I did:**

* Processed event data such as shots, passes, duels and player actions
* Built xG-style models using variables such as distance, angle, shot type and game context
* Visualized shot maps, xG flow and performance trends
* Reflected on how data interpretation changes depending on assumptions and context

**Tools:** R, Python, MongoDB, event data, logistic regression, visualization

**Why it matters:**
The project shows my interest in modelling real-world behavior where data is useful, but never tells the whole story alone.

<details>
  <summary>See more 📸</summary>
  <img width="610" height="661" alt="image" src="https://github.com/user-attachments/assets/ff75e47b-4c09-4e69-b80c-bf995671e6a2" />
  <img width="360" height="281" alt="image" src="https://github.com/user-attachments/assets/5e83c148-f934-426a-bc4b-c502d5f43511" />
  <img width="565" height="348" alt="image" src="https://github.com/user-attachments/assets/52b360b1-d4c9-4e7f-8261-502e8a602503" />
  <img width="356" height="240" alt="image" src="https://github.com/user-attachments/assets/ad7705d9-e87b-451f-b0d4-fefbd1a0a4a5" />
  <img width="488" height="408" alt="image" src="https://github.com/user-attachments/assets/e030cc4b-c815-4976-bb23-49900d5cdaf" />
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
</details>

### 11. Football Manager Scouting & Analysis Platform

**Context:** Personal analytics tool built around Football Manager data.

**Problem:**
Football Manager exports contain useful player data, but static tables are difficult to search, compare and interpret.

**What I did:**

* Scraped player attributes from Football Manager HTML exports
* Cleaned and standardized values such as salaries and transfer values
* Built an interactive scouting app with filters for age, skills, salary and custom attributes
* Analyzed attribute patterns and correlations by position

**Tools:** Python, web scraping, pandas, Streamlit, correlation analysis

**Why it matters:**
The project shows how I turn static data into an interactive tool that supports better decisions.

<details>
  <summary>See more 📸</summary>
  <img width="1047" height="705" alt="image" src="https://github.com/user-attachments/assets/bfe0c9ac-dc42-4fa1-a8ed-4652da025fc8" />
  <img width="1704" height="783" alt="image" src="https://github.com/user-attachments/assets/06a3308f-e056-442f-8e30-0c46ccdc4293" />
  <img width="1700" height="832" alt="image" src="https://github.com/user-attachments/assets/5ee36b92-924e-4d74-8de2-8a750ca044ba" />
  <img width="1404" height="625" alt="image" src="https://github.com/user-attachments/assets/f1bff9c5-aecd-4127-9723-304244793a8d" />
  <img width="1380" height="510" alt="image" src="https://github.com/user-attachments/assets/e4dba7ac-35b7-4ed7-945c-1e7c60ca945c" />
  <img width="986" height="652" alt="image" src="https://github.com/user-attachments/assets/d33648b1-88d6-4400-ba0f-ad3e9d96d6d2" />
</details>

---

# How I Work

I usually work across the full data workflow:

1. Understand the problem and the people who need the result
2. Find, extract and clean the relevant data
3. Build the analysis, model, dashboard or automation
4. Validate whether the output is useful and reliable
5. Turn it into a dashboard, app, report or tool
6. Communicate the result clearly to technical and non-technical users

I care a lot about the last part. A model or analysis is only useful if someone can understand it, trust it and use it.

---

# Education

**MSc in Digital Design & Interactive Technologies**
IT University of Copenhagen
Focus on data-driven systems, AI, interactive technologies, usability and applied machine learning.

**BSc in Data Analysis**
Copenhagen Business Academy
Specialization in machine learning and data optimization. Bachelor project on ML-based soil remediation optimization.

**AP Degree in Marketing Management**
Business Academy SouthWest
Background in marketing, digital analysis, performance marketing, customer growth and branding.

---

# Certifications, Languages & Additional Experience

**Certifications:** Google Success Online - Digital Marketing; R for Data Science: Analysis and Visualization; Statistics Foundations.

**Languages:** Danish native, English fluent, German beginner.

**Additional experience:** Digital marketing, fitness instruction, service roles, special education assistance and football coaching. These roles strengthened my communication, planning and stakeholder-facing work.

---

# Contact

* GitHub: [github.com/rasmusstaaldinesen](https://github.com/rasmusstaaldinesen)
* LinkedIn: [linkedin.com/in/rasmusstaaldinesen](https://www.linkedin.com/in/rasmusstaaldinesen/)
* Email: [rasmusstaal@yahoo.dk](mailto:rasmusstaal@yahoo.dk)
