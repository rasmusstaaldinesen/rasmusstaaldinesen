[English version here :)](#hello-im-rasmus-)


# Hejsa, jeg er Rasmus 👋

Velkommen til mit hjørne af GitHub! Jeg er en **Full Stack Data Scientist** med en professionsbachelor i Data Analytics fra CPHBusiness. Jeg trives med at omdanne rå data til brugbar indsigt og bygge robuste, produktionsklare løsninger, der virkelig gør en forskel.

Min rejse hos Krüger A/S har været utroligt givende. Hvad der startede som en praktikplads, hvor jeg var den første og eneste medarbedjer i afdelingen for Digital Innovation, udviklede sig hurtigt til en rolle, hvor jeg konstant bliver udfordret til at anvende dataanalyse, softwareudvikling og optimeringsteknikker, især inden for miljø- og forsyningssektorerne. Jeg elsker at dykke dybt ned i data for at afdække muligheder og derefter bringe disse indsigter til live gennem innovative applikationer.

---

## Kernekompetencer: 🛠️
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

## Projekter

Her er et indblik i nogle af de projekter, jeg har arbejdet med, som viser min tilgang til at løse udfordringer og udforske forskellige datasæt. Selvom den faktiske kode for nogle klientprojekter forbliver fortrolig, har jeg skitseret min rolle, de teknologier, jeg brugte, og effekten af mit arbejde.

---

## **Miljødatavidenskab & Optimering** 🌿

### **1. Bachelorprojekt: Anomalier og optimering af jordoprensning**

Mit professionsbachelorprojekt fokuserede på at udnytte dataanalyse og maskinlæring til at detektere afvigelser og optimere processer inden for jordoprensning. Dette projekt viste en blanding af miljødatavidenskab, maskinlæring og udvikling af interaktive applikationer:

* **Problem:** Identifikation af usædvanlige mønstre og ineffektivitet i komplekse jordoprensningsprocesser ved hjælp af sensordata.
* **Dataanalyse og Forbehandling:** Arbejdede med omfattende sensordata, primært temperaturmålinger fra forskellige dybder, og udførte grundig rensning, transformation og feature engineering for at forberede data til modellering.
* **Afvigelsesdetektion:** Implementerede og evaluerede flere uovervågede maskinlæringsalgoritmer (bl.a. Isolation Forest, One-Class SVM, Local Outlier Factor) til nøjagtigt at identificere unormale temperaturadfærds, der indikerer potentielle problemer eller optimeringsmuligheder i renseprocessen.
* **Geospatial Integration:** Integrerede analyse med **QGIS** for at visualisere sensorplaceringer og rumlig fordeling af afvigelser, hvilket gav afgørende geografisk kontekst til dataene.
* **Interaktiv Streamlit-applikation:** Udviklede en skræddersyet **Streamlit-applikation**, der fungerede som et interaktivt dashboard til visualisering af aktuelle temperaturer, daglige temperaturændringer og udførelse af effektivitetsanalyser. Appen gjorde det muligt for ingeniører at udforske data dynamisk, gennemgå detekterede afvigelser og vurdere rensningsfremskridt, hvilket gav en brugervenlig grænseflade for interessenter.
* **✨ Effekt:** Resultaterne og den udviklede applikation tilbød værdifuld indsigt til optimering af ressourceallokering, reduktion af driftsomkostninger og forbedring af den samlede effektivitet af jordrensningsindsatsen ved at give tidlige advarsler og ydeevneovervågning.

### **2. Platform for Indsamling og Analyse af Katodisk Beskyttelsesdata**

Dette projekt omfattede opbygning af en robust løsning til indsamling, visualisering og analyse af kritiske katodiske beskyttelsesdata fra `katodiskbeskyttelse.dk`. Dette system er vigtigt for overvågning af integriteten af strukturer som broer. Mit arbejde omfattede hele pipelinen:

* **Avanceret Web Scraping:** Jeg udviklede et web scraping-script til at logge ind på portalen, navigere i komplekse træstruktur, identificere specifikke stationer og sensorer og programmatisk downloade måledata i Excel-format.
* **Data Management:** De scrapede data blev organiseret i en logisk mappestruktur (Station/Subtree/Sensor) for nem adgang og behandling.
* **Interaktiv Plotting Applikation:** Jeg byggede en brugervenlig **Streamlit-applikation**, der giver brugerne mulighed for interaktivt at plotte og analysere de indsamlede sensordata. Denne app inkluderer funktioner til:
    * Dynamisk filtrering efter station, undertræ og sensor.
    * Visualisering af tidsseriedata, hvilket muliggør detaljeret udforskning af katodiske beskyttelsesmålinger.
    * Visning af relevante datatyper (f.eks. 'On' og 'Off' potentialer, DP24-værdier (depolariseringsværdier) og sammenligning af dem med industrikriterier (-750 mV, -900 mV linjer) for hurtigt at identificere potentielle problemer.
* **Anomalidetektion Applikation:** Sammen med plottingværktøjet udviklede jeg en **Streamlit-applikation** til automatiseret afvigelsesdetektion på sensordata. Denne app integrerer flere maskinlæringsalgoritmer (`IsolationForest`, `LocalOutlierFactor`, `OneClassSVM`, `EllipticEnvelope`, `KNN`) til at markere usædvanlige aflæsninger, hvilket giver et tidligt advarselssystem for vedligeholdelsesteamet.
* **✨ Effekt:** Denne platform strømlinede dataindsamlings- og analyseprocessen betydeligt, omdannede manuelt arbejde til en automatiseret, indsigtfuld arbejdsgang, hvilket førte til mere proaktiv vedligeholdelse og forbedret strukturel levetid.

### **3. GeoPlanner: Ruteoptimeringsapplikation til feltteknikere**

Dette var et omfattende projekt, hvor jeg var drivkraften bag udviklingen af en **Streamlit-applikation** designet til at optimere ruter for feltteknikere. Løsningen leverede betydelige reduktioner i rejsetid og driftsomkostninger ved at udnytte:

* **Klyngedannelse (clustering)** til intelligent gruppering af opgaver, hvilket sikrer effektiv tildeling.
* **Google OR-Tools** til avanceret løsning af Vehicle Routing Problem (VRP), der integrerer geografiske afstande, teknikeres arbejdsdage og logistik for overnatning.
* **OSRM (Open Source Routing Machine)** til nøjagtige rejsetids- og afstandsberegninger.
* **Interaktive kort og datavisualiseringer** inden for Streamlit-appen, hvilket giver planlæggere intuitiv kontrol og klar indsigt.

Min rolle spændte over hele udviklingscyklussen, fra indledende dataindsamling og sofistikeret modeludvikling til front-end applikationsdesign og bidrag til implementeringsstrategier. Det var enormt tilfredsstillende at se en kompleks logistisk udfordring omdannet til et håndgribeligt, værdiskabende værktøj.

* **✨ Effekt:** Leverede betydelige reduktioner i rejsetid og driftsomkostninger for feltteknikere gennem optimeret ruteplanlægning.

### **4. Terrænnært Grundvand: Analyse og sammenligning af hydrologiske modeller**

Et fascinerende projekt inden for miljø- og forsyningssektoren, som involverede et dybtgående studie af sammenligning af faktiske grundvandsmålinger fra GEUS (De Nationale Geologiske Undersøgelser for Danmark og Grønland) med modellerede grundvandsniveauer fra den hydrologiske model HIP. Et projekt, der bliver investeret omkring 60 milliarder kr. i:

* **SQL-integration:** Jeg designede og implementerede effektiv dataindsamling og -aggregering fra en SQL Server-database, og skrev forespørgsler til filtrering og rensning af tidsseriedata direkte ved kilden. Dette sikrer, at kun relevante data af høj kvalitet kommer ind i den analytiske pipeline.
* **API-integration:** Jeg integrerede med en ekstern API (Dataforsyningen.dk) for at hente geografisk specifikke tidsseriedata fra deres hydrologiske model. Dette demonstrerede min evne til at forbinde forskellige datakilder til omfattende analyse.
* **Datahåndtering og -transformation:** En betydelig del af arbejdet involverede konvertering af koordinatsystemer (f.eks. DVR90 til UTM/WGS84), håndtering af store geospatiale tidsseriedatasæt og sikring af datakonsistens på tværs af forskellige input (SQL, API, lokale CSV'er), hvilket var vigtigt for nøjagtige sammenligninger.
* **Applikationsudvikling:** Jeg byggede en interaktiv **Streamlit-applikation** til visualisering og sammenligning af de observerede og modellerede grundvandsniveauer. Appen giver brugere mulighed for at uploade deres egne CSV-filer for yderligere modeldata og interaktivt udforske uoverensstemmelser over tid og rum, hvilket giver et dynamisk analyseværktøj.
* **Statistisk Analyse:** Jeg udførte stringent statistisk sammenligning, beregnede nøgletal som gennemsnitlig afvigelse og RMSE for kvantitativt at vurdere modellens nøjagtighed og identificere områder for potentiel forbedring.
* **Visualisering:** Ved hjælp af **Plotly** oprettede jeg dynamiske og informative grafer, der effektivt kommunikerer komplekse miljødata og fremhæver modelpræstation, hvilket gør teknisk indsigt tilgængelig.
* **✨ Effekt:** Forbedrede forståelsen af hydrologisk modelnøjagtighed og leverede et dynamisk værktøj til miljødataanalyse.

---

## **Markeds- og Økonomisk Analyse** 📈

### **5. Brugtvognsforhandleren: Prisforudsigelse for brugte biler og identifikation af undervurderede biler**

Dette projekt fokuserede på at bygge en maskinlæringsmodel til at forudsige prisen på brugte biler, der er annonceret på Bilbasen.dk, med et yderligere mål om at identificere potentielt undervurderede køretøjer på markedet. Projektet er privat og stadig under udvikling og efter min vurdering er modellerne ikke gode nok endnu. Indtil videre er det kun mig, der har udviklet på projektet.
Nøgleaspekter inkluderede:

* **Robust web scraping** af et stort datasæt fra brugtvognsforhandlere, der fangede en bred vifte af bilattributter.
* Omfattende **feature engineering**, hvor jeg kreativt omdannede rå data til yderst prædiktive features, såsom binære indikatorer for specifikt biludstyr (f.eks. varme i sæderne, navigation).
* Udvikling af **ensemblemodeller** (inklusive XGBoost) for at opnå høj prædiktiv nøjagtighed og forbedre robustheden af prisforudsigelser.
* **Afvigelsesdetektionsteknikker** til at markere biler, hvis faktiske priser afveg markant fra modellens forudsigelser, hvilket pegede på potentielle "kup".

Dette projekt forfinede mine færdigheder i håndtering af ustrukturerede webdata, opbygning af kraftfulde prædiktive modeller og udtrækning af brugbar indsigt for både købere og sælgere på et dynamisk marked.

* **✨ Effekt:** Udviklede et værktøj til at forudsige bilpriser og identificere potentielle "kup" på markedet for brugte biler.

### **6. Boligmarkedsanalyse (Boligbasen)**

I dette projekt analyserede jeg tendenser på det danske boligmarked ved hjælp af data fra Danmarks Statistik (DST) og andre relevante kilder.

* **Dataindsamling og Integration:** Anvendte forskellige metoder, herunder API-integration med DST og web scraping, til at indsamle omfattende bolig-, befolknings- og økonomiske data.
* **Statistisk Modellering:** Anvendte statistisk analyse til at identificere korrelationer mellem boligpriser, befolkningsvækst og økonomiske indikatorer.
* **Trendanalyse og Visualisering:** Udviklede visualiseringer til at illustrere nøgletrends, regionale forskelle og potentielle fremtidige udviklinger på boligmarkedet, hvilket gav indsigt i markedsdynamikken.
* **✨ Effekt:** Leverede værdifuld indsigt i det danske boligmarkeds dynamik og tendenser.
* **Resultat:** De 5 variable, der bedst forklarer pris pr. m2 er: Mdl. udgift, Pris, År opført, Værelser og Størrelse (m2).

### **7. Forbrugertillid og Økonomisk Prognose**

Dette projekt udforskede forholdet mellem forbrugertillidsindikatorer og fremtidig økonomisk vækst, især husholdningernes forbrugsudgifter.

* **Makroøkonomisk Dataanalyse:** Indsamlede og analyserede forbrugertillidsindikatorer fra forskellige kilder (f.eks. DST, DI - Dansk Industri) og korrelerede dem med historiske forbrugsdata.
* **Prædiktiv Modellering:** Anvendte statistiske og tidsserieteknikker til at forstå og modellere forbrugertillidens prædiktive kraft på fremtidige økonomiske tendenser.
* **API-integration:** Udnyttede API'er (inklusive Eurostat) til at hente internationale økonomiske data til sammenlignende analyse og bredere økonomisk kontekst.
* **✨ Effekt:** Forbedret forståelse af forbrugertillidens prædiktive kraft på økonomiske tendenser.

### **8. Erhvervslånsmuligheder**

Dette projekt involverede analyse af faktorer, der påvirker virksomheders muligheder for at opnå lån, baseret på forskellige finansielle og operationelle målinger.

* **Dataaggregering:** Samlede og rensede datasæt indeholdende regnskaber, antal medarbejdere og svar fra spørgeskemaer relateret til låneopfattelser.
* **Lineær regressionsmodellering:** Udviklede lineære regressionsmodeller til at identificere signifikante forudsigere af låneadgang, såsom solvensnøgletal, balance størrelse og antal medarbejdere.
* **Statistisk Fortolkning:** Fortolkede modelkoefficienter og statistisk signifikans for at give indsigt i, hvilke faktorer der mest positivt eller negativt påvirker lånemuligheder for virksomheder.
* **✨ Effekt:** Gav indsigt i faktorer, der påvirker erhvervslånemuligheder.

### **9. BNP Tidsserieprognose**

Et tidsserieanalyseprojekt med fokus på at forudsige Danmarks Bruttonationalprodukt (BNP).

* **Tidsserieanalyse:** Anvendte forskellige tidsseriemodeller (f.eks. ARIMA, eksponentiel udglatning) på historiske BNP-data.
* **Modelvurdering:** Evaluerede modelpræstation ved hjælp af passende metrikker og teknikker for tidsserieprognose.
* **Prognose:** Genererede fremtidige BNP-prognoser, hvilket gav indsigt i potentielle økonomiske baner.
* **✨ Effekt:** Genererede fremtidige BNP-prognoser, der gav indsigt i potentielle økonomiske baner.

---

## **Sportsanalyse** ⚽

### **10. Fodboldpræstationsanalyse (Fodbolddata)**

Dette projekt involverede analyse af fodboldkampdata for at identificere mønstre og forudsige udfald. Projektet er udarbejdet i et team af 4.

* * **Datagrundlag:** Arbejdede med rå trackingdata og eventdata fra fodboldkampe, herunder bl.a. skudplaceringer, afleveringsnetværk og spillerbevægelser.
* **xG Modeludvikling:** Designet og implementeret en logistisk regressionsmodel til at forudsige sandsynligheden for, at et skud resulterer i et mål (xG), baseret på en række forklaringsvariable som skudafstand, vinkel til mål, skudtype (f.eks. hovedstød, frispark), spiltype (f.eks. åbent spil, kontraangreb) og tilstedeværelse af forsvarsspillere.
* **xP Modeludvikling:** Udviklede en model til at forudsige den forventede pointuddeling (sejr, uafgjort, tabt) for et hold i en given kamp baseret på kampens xG-værdi og andre relevante faktorer, som f.eks. modstanderens styrke og hjemmebanefordel.
* **Visualisering og Fortolkning:** Visualisering af modelresultater og xG-flow over tid, hvilket gjorde analyserne analyser tilgængelige. Jeg udførte statistisk analyse for at fortolke modellernes koefficienter og vurdere deres prædiktive kraft.
* **Teoretisk Fundament:** Projektet inkluderede en refleksion over epistemologiske perspektiver som logisk positivisme og socialkonstruktivisme i konteksten af sportsdataanalyse, der adresserede udfordringerne ved at koble rå data til kompleks virkelighed og betydningen af fortolkning.
* **Rolle:** Som en del af et team bidrog jeg væsentligt til dataforbehandling, modeludvikling, statistisk analyse og den teoretiske diskussion.
* **✨ Effekt:** Leverede et robust rammeværk for data-drevet beslutningstagning for fodboldklubber, der forbedrer både taktisk analyse, spillerudvikling og rekruttering ved at give en mere nuanceret forståelse af præstationer end traditionelle målscore.


### **11. Football Manager 2024 Scouting & Analyseplatform**

Dette projekt fokuserede på at bygge en omfattende dataløsning til at forbedre scouting- og analysefunktioner inden for det populære spil, Football Manager. Det demonstrerer min evne til at tackle specifikke, komplekse dataudfordringer og skabe intuitive brugergrænseflader:

* **Automatiseret dataindsamling:** Udviklede Python-scripts til **web scraping** af detaljerede spillerdata direkte fra Football Managers HTML-eksportfiler. Dette involverede robust dataekstraktion og indledende strukturering af rå spilstatistikker.
* **Omfattende datarensning og transformation:** Implementerede grundige datarensningspipelines til at håndtere forskellige datatyper, uoverensstemmelser og formater (f.eks. konvertering af tekstbaserede attributter som 'Løn' og 'Transferværdi' til brugbare numeriske formater, håndtering af manglende værdier). Dette sikrede, at dataene var klar til pålidelig analyse.
* **Interaktiv scouting-applikation:** Oprettede en brugervenlig **Streamlit-applikation** designet til interaktiv spillerscouting. Applikationen giver brugere mulighed for at:
    * Dynamisk filtrere spillerdata på tværs af en bred vifte af attributter (f.eks. alder, attributter, løn, transferværdi).
    * Indstille brugerdefinerede minimum- og maksimumværdier for enhver numerisk attribut, hvilket muliggør meget specifikke søgeforespørgsler.
    * Udforske og visualisere spillerstatistikker i en intuitiv grænseflade, hvilket gør det nemt at identificere egnede talenter baseret på specifikke kriterier.
* **Analyse af præstationsattributter:** Udførte detaljeret statistisk analyse for at identificere nøglepræstationsattributter for spillere på forskellige positioner. Dette involverede beregning af korrelationer mellem spillerattributter og samlede præstationsmålinger, hvilket gav indsigt i, hvad der virkelig gør en spiller effektiv i en given rolle. Dette analytiske arbejde blev udført ved hjælp af Jupyter Notebooks til eksplorativ dataanalyse og statistisk modellering.
* **✨ Effekt:** Denne platform omdanner statiske spildata til et dynamisk og kraftfuldt analyseværktøj, der muliggør mere informeret beslutningstagning for virtuelle fodboldmanagere, hvilket markant strømliner scoutingprocessen og giver en konkurrencemæssig fordel.


### Lad os connect'e! 🤝

Jeg er altid frisk på at diskutere nye muligheder, spændende projekter eller dele indsigt inden for datavidenskab og teknologisk innovation. Du er velkommen til at række ud!

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/rasmusstaaldinesen/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:rasmusstaal@yahoo.dk)






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
