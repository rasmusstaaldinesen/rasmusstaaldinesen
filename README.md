# Hi there, I'm Rasmus 👋

Welcome to my corner of GitHub! I'm a  **Full Stack Data Scientist** with a professional bachelor's degree in Data Analytics from CPHBusiness. I thrive on transforming raw data into actionable insights and building robust, production-ready solutions that truly make a difference.

My journey at Krüger A/S, within the Digital Innovation department, has been incredibly rewarding. What started as an internship quickly evolved into a role, where I'm constantly challenged to apply data analysis, software development, and optimization techniques, particularly within the environmental and utility sectors. I love diving deep into data to uncover opportunities and then bringing those insights to life through innovative applications.

## My Core Skills:

* **Programming:** Python (pandas, scikit-learn, OR-Tools, Streamlit, SQL, geopy, requests), SQL, Git, R
* **Data Science:** Data Analysis, Machine Learning (Anomaly Detection, Clustering, Predictive Modeling, Ensemble Models), Feature Engineering
* **Geospatial Data:** Geocoding, Route Planning (OSRM), GPS Coordinates, Shapefiles, QGIS Integration
* **Web Technologies:** Web Scraping (BeautifulSoup, Requests), API Integration
* **Visualization & Applications:** Streamlit Apps (Interactive Plotting, Anomaly Detection), Plotly
* **DevOps & Tools:** GitHub, GitHub Actions, Version Control, VS Code, Model Deployment

## Projects I'm Proud Of:

Here’s a glimpse into some of the projects I've tackled, showcasing my approach to solving real-world business challenges and exploring diverse datasets. While the actual code for some client projects remains proprietary, I’ve outlined my role, the technologies I used, and the impact of my work.

---

### **Environmental Data Science & Optimization**

#### **1. Bachelor Thesis: Anomaly Detection and Optimization in Soil Remediation**

My professional bachelor's thesis focused on leveraging data analytics and machine learning to detect anomalies and optimize processes within soil remediation. This project showcased a blend of environmental data science, machine learning, and interactive application development:

* **Problem:** Identifying unusual patterns and inefficiencies in complex soil remediation processes using sensor data.
* **Data Analysis & Preprocessing:** Worked with extensive sensor data, primarily temperature readings from various depths, performing rigorous cleaning, transformation, and feature engineering to prepare the data for modeling.
* **Anomaly Detection:** Implemented and evaluated multiple unsupervised machine learning algorithms (e.g., Isolation Forest, One-Class SVM, Local Outlier Factor) to accurately identify anomalous temperature behaviors indicating potential issues or optimization opportunities in the remediation process.
* **Geospatial Integration:** Integrated analysis with **QGIS** to visualize sensor locations and spatial distribution of anomalies, providing crucial geographical context to the data.
* **Interactive Streamlit Application:** Developed a custom **Streamlit application** that served as an interactive dashboard for visualizing current temperatures, daily temperature changes, and conducting efficiency analyses. The app allowed users to dynamically explore data, review detected anomalies, and assess remediation progress, providing a user-friendly interface for stakeholders.
* **Impact:** The findings and the developed application offered valuable insights for optimizing resource allocation, reducing operational costs, and improving the overall effectiveness of soil remediation efforts by providing early warnings and performance monitoring.

#### **2. Cathodic Protection Data Collection & Analysis Platform**

This project involved building a robust solution for collecting, visualizing, and analyzing critical cathodic protection data from `katodiskbeskyttelse.dk`. This system is vital for monitoring the integrity of structures like bridges. My work encompassed the full pipeline:

* **Advanced Web Scraping:** I developed a sophisticated web scraping script using Python's `requests` and `BeautifulSoup` to log into the portal, navigate complex treeview structures, identify specific stations and sensors, and programmatically download measurement data in Excel format. This ensured reliable and automated data acquisition.
* **Data Management:** The scraped data was organized into a logical directory structure (Station/Subtree/Sensor) for easy access and processing.
* **Interactive Plotting Application:** I built a user-friendly **Streamlit application** that allows users to interactively plot and analyze the collected sensor data. This app includes features for:
    * Dynamic filtering by station, subtree, and sensor.
    * Visualization of time-series data using `Plotly`, enabling detailed exploration of cathodic protection measurements.
    * Displaying relevant data types (e.g., 'On' and 'Off' potentials, DP24 values) and comparing them against industry criteria (-750 mV, -900 mV lines) to quickly identify potential issues.
* **Anomaly Detection Application:** Alongside the plotting tool, I developed a **Streamlit application** for automated anomaly detection on the sensor data. This app integrates multiple machine learning algorithms (`IsolationForest`, `LocalOutlierFactor`, `OneClassSVM`, `EllipticEnvelope`, `KNN`) to flag unusual readings, providing an early warning system for maintenance teams.
* **Impact:** This platform significantly streamlined the process of data collection and analysis, transforming manual efforts into an automated, insightful workflow, leading to more proactive maintenance and improved structural longevity.

#### **3. GeoPlanner: Route Optimization Application for Field Technicians**

This was a comprehensive project where I spearheaded the development of a **Streamlit application** designed to optimize routes for field technicians. The solution delivered significant reductions in travel time and operational costs by leveraging:

* **Clustering algorithms** for intelligent grouping of tasks, ensuring efficient assignment.
* **Google OR-Tools** for advanced vehicle routing problem (VRP) solving, integrating geographical distances, technician working days, and overnight stay logistics.
* **OSRM (Open Source Routing Machine)** for accurate travel time and distance calculations.
* **Interactive maps and data visualizations** within the Streamlit app, providing planners with intuitive control and clear insights.

My role spanned the entire development lifecycle, from initial data ingestion and sophisticated model development to front-end application design and contributing to deployment strategies. It was immensely satisfying to see a complex logistical challenge transformed into a tangible, value-adding tool.

#### **4. Near-Surface Groundwater: Analysis and Comparison of Hydrological Models**

A fascinating project within the environmental and utility sector, this involved a deep dive into comparing actual groundwater measurements from GEUS (Geological Survey of Denmark and Greenland) with modeled groundwater levels from the HIP hydrological model. This project truly highlights my **full-stack data science capabilities**:

* **SQL Integration:** I designed and implemented efficient data retrieval and aggregation from a SQL Server database (using `pyodbc`), writing complex queries to filter and clean time-series data directly at the source. This ensures only relevant, high-quality data enters the analytical pipeline.
* **API Integration:** I integrated with an external API (Dataforsyningen.dk) using `requests` to fetch geographically specific time-series data from their hydrological model. This demonstrated my ability to connect disparate data sources for comprehensive analysis.
* **Data Handling & Transformation:** A significant part of the work involved converting coordinate systems (e.g., DVR90 to UTM/WGS84), managing large geospatial time-series datasets, and ensuring data consistency across varied inputs (SQL, API, local CSVs). This was crucial for accurate comparisons.
* **Application Development:** I built an interactive **Streamlit application** for visualizing and comparing the observed and modeled groundwater levels. The app allows users to upload their own CSV files for additional model data and interactively explore discrepancies over time and space, providing a dynamic analysis tool.
* **Statistical Analysis:** I performed rigorous statistical comparisons, calculating key metrics like average deviation and RMSE, to quantitatively assess the model's accuracy and identify areas for potential improvement.
* **Visualization:** Using **Plotly**, I created dynamic and informative graphs that effectively communicate complex environmental data and highlight model performance, making technical insights accessible.

---

### **Market & Economic Analysis**

#### **5. Bilbasen: Used Car Price Prediction & Undervalued Car Detection**

This project focused on building a machine learning model to predict the price of used cars listed on Bilbasen.dk, with an added aim to identify potentially undervalued vehicles in the market. Key aspects of my contribution included:

* **Robust web scraping** of a vast dataset from Bilbasen.dk, capturing a wide array of car attributes.
* Extensive **feature engineering**, where I creatively transformed raw data into highly predictive features, such as binary indicators for specific car equipment (e.g., heated seats, navigation).
* Development of **ensemble models** (including XGBoost) to achieve high predictive accuracy and enhance the robustness of price forecasts.
* **Anomaly detection techniques** to flag cars whose actual prices significantly deviated from the model's predictions, pinpointing potential "bargains."

This project honed my skills in handling unstructured web data, building powerful predictive models, and extracting actionable insights for both buyers and sellers in a dynamic market.

#### **6. Housing Market Analysis (Boligbasen)**

In this project, I analyzed trends in the Danish housing market using data from Danmarks Statistik (DST) and other relevant sources.

* **Data Acquisition & Integration:** Utilized various methods including API integration with DST and web scraping to gather comprehensive housing, population, and economic data.
* **Statistical Modeling:** Applied statistical analysis to identify correlations between housing prices, population growth, and economic indicators.
* **Trend Analysis & Visualization:** Developed visualizations to illustrate key trends, regional differences, and potential future developments in the housing market, providing insights into market dynamics.

#### **7. Consumer Confidence & Economic Forecasting**

This project explored the relationship between consumer confidence indicators and future economic growth, particularly household consumption expenditures.

* **Macroeconomic Data Analysis:** Collected and analyzed consumer confidence indicators from various sources (e.g., DST, DI - Dansk Industri) and correlated them with historical consumption data.
* **Predictive Modeling:** Employed statistical and time series techniques to understand and model the predictive power of consumer confidence on future economic trends.
* **API Integration:** Leveraged APIs (including Eurostat) to acquire international economic data for comparative analysis and broader economic context.

#### **8. Corporate Lending Opportunities**

This project involved analyzing factors influencing companies' opportunities to obtain loans, based on various financial and operational metrics.

* **Data Aggregation:** Compiled and cleaned datasets containing financial statements, employee numbers, and survey responses related to lending perceptions.
* **Linear Regression Modeling:** Developed linear regression models to identify significant predictors of loan accessibility, such as solvency ratios, balance sheet size, and number of employees.
* **Statistical Interpretation:** Interpreted model coefficients and statistical significance to provide insights into which factors most positively or negatively impact lending opportunities for businesses.

#### **9. GDP Time Series Forecasting**

A time series analysis project focused on predicting Denmark's Gross Domestic Product (GDP).

* **Time Series Analysis:** Applied various time series models (e.g., ARIMA, exponential smoothing) to historical GDP data.
* **Model Evaluation:** Evaluated model performance using appropriate metrics and techniques for time series forecasting.
* **Forecasting:** Generated future GDP forecasts, providing insights into potential economic trajectories.

---

### **Sports Analytics**

#### **10. Football Performance Analysis (Fodbolddata)**

This project involved analyzing football (soccer) match data to identify patterns and predict outcomes.

* **Data Collection & Cleaning:** Gathered raw match data, including scores, team statistics, and player performance metrics.
* **Statistical Analysis:** Performed statistical analyses to identify key performance indicators (KPIs) and their correlation with match results.
* **Predictive Modeling:** Explored simple predictive models to estimate match outcomes or team performance, drawing insights from historical data.
* **Visualization:** Created visualizations to present team strengths, weaknesses, and head-to-head comparisons.

---

#### **11. Football Manager Scouting & Analytics Platform**

This project focused on building a comprehensive data solution to enhance scouting and analytical capabilities within the popular game, Football Manager. It demonstrates my ability to tackle specific, complex data challenges and create intuitive user interfaces:

* **Automated Data Acquisition:** Developed Python scripts to **web scrape** detailed player data directly from Football Manager's HTML export files. This involved robust data extraction and initial structuring of raw game statistics.
* **Extensive Data Cleaning & Transformation:** Implemented thorough data cleaning pipelines to handle various data types, inconsistencies, and formats (e.g., converting text-based attributes like 'Wage' and 'Transfer Value' into usable numeric formats, handling missing values). This ensured the data was ready for reliable analysis.
* **Interactive Scouting Application:** Created a user-friendly **Streamlit application** designed for interactive player scouting. The application allows users to:
    * Dynamically filter player data across a wide range of attributes (e.g., age, attributes, wage, transfer value).
    * Set custom minimum and maximum values for any numeric attribute, enabling highly specific search queries.
    * Explore and visualize player statistics in an intuitive interface, making it easy to identify suitable talents based on specific criteria.
* **Performance Attribute Analysis:** Conducted detailed statistical analysis to identify key performance attributes for players across different positions. This involved calculating correlations between player attributes and overall performance metrics, providing insights into what truly makes a player effective in a given role. This analytical work was performed using Jupyter Notebooks for exploratory data analysis and statistical modeling.
* **Impact:** This platform transforms static game data into a dynamic and powerful analytical tool, enabling more informed decision-making for virtual football managers, significantly streamlining the scouting process and providing a competitive edge.

---

## Let's Connect!

I'm always keen to discuss new opportunities, exciting projects, or just share insights on data science and technological innovation. Feel free to reach out!

* **LinkedIn:** https://www.linkedin.com/in/rasmusstaaldinesen/
* **Email:** rasmusstaal@yahoo.dk





