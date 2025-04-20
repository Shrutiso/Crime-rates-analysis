# 📊 Crime Data Analysis in Los Angeles (2020–Present)

This project presents a comprehensive **data analysis of crime incidents** reported in **Los Angeles** from **2020 to the present**. Using government-sourced open data and Python-based tools, the analysis aims to reveal crime trends, hotspots, victim demographics, and other key insights to support public safety and policy-making.

---

## 👩‍💻 Submitted By

- **Name**: Shruti Somvanshi  
- **Registration No.**: 12310394  
- **Programme**: B.Tech CSE  
- **Section**: K23EH  
- **Course Code**: INT375  
- **Guide**: Dr. Madhu Bala  
- **University**: Lovely Professional University, Punjab

---

## 📁 Dataset Source

- 📌 [Los Angeles Open Crime Data Portal](https://catalog.data.gov/dataset/crime-data-from-2020-to-present)

The dataset includes:
- Date & time of crime occurrence and report
- Area name and geographic coordinates
- Crime description and classification
- Case status (e.g., Adult Arrest, Investigation Continued)

---

## 🧠 Objectives

- Identify **crime hotspots** using latitude/longitude
- Use **boxplots** to detect outliers
- Analyze **crime trends by hour/day/year**
- Compare **crime type frequencies**
- Use **heatmaps & scatter plots** to visualize crime zones

---

## 🔧 Tools & Technologies

- Python (Jupyter Notebook)
- Pandas, NumPy
- Matplotlib, Seaborn
- Geopandas (for advanced spatial mapping)

---

## 📊 Exploratory Data Analysis (EDA)

### ✅ Key Steps:
- Loaded dataset into Pandas
- Cleaned missing values & dropped irrelevant columns
- Combined date and time fields into a single datetime
- Detected and removed outliers using IQR
- Conducted feature selection for relevant columns:
  - `Crime_Description`, `Victim_Age`, `Weapon_Used`, `Latitude`, `Longitude`, `Area_Name`, `Datetime_Occurred`

---

## 📈 Key Insights

### 🔥 Crime Trends:
- Spike in total crimes in **2022**, followed by decline.
- **Vehicle Theft** and **Simple Assault** are top reported crimes.
- Evening hours (5 PM – 7 PM) show the highest crime rate.

### 🧍‍♂️ Victim Demographics:
- Most victims are aged **20–35**
- **Male victims** are more frequent than female
- Infants and young adults also show notable victim counts

### 🗺️ Geographical Patterns:
- **Central LA** reported the highest number of incidents.
- High-crime areas: Central, 77th Street, Pacific
- Low-crime areas: Van Nuys, Topanga

### 📌 Seriousness Levels:
- **60%** crimes fall under **Level 1 (less serious)**
- **40%** under **Level 2 (more serious)**

---

## 📸 Visualizations

The following visualizations were created:
- Yearly crime trends
- Top 5 crime types bar chart
- Heatmaps by area
- Victim age distribution (histogram)
- Crime time distribution
- Gender-based victim stats
- Scatter plot: Victim age vs time of crime

> 📷 *Screenshots & graphs can be found in the repository’s `/visualizations` folder.*

---

## 🚀 Future Scope

- Predictive modeling (ARIMA, LSTM)
- Real-time dashboards using IoT/sensors
- Advanced GIS-based interactive maps
- Correlate demographics (income, education, etc.)
- Sentiment and text analysis on case descriptions

---

## 📂 GitHub Repository

🔗 [Crime Data Analysis Repo](https://github.com/Shrutiso/Crime-rates-analysis_1)

---

## 🔗 LinkedIn Post

🌐 [LinkedIn Post on Project](https://www.linkedin.com/feed/update/urn:li:activity:7316308965481422849)

---

## 📃 References

- [Pandas Documentation](https://pandas.pydata.org/docs/)
- [Seaborn Documentation](https://seaborn.pydata.org/)
- [Matplotlib](https://matplotlib.org/)
- [NumPy](https://numpy.org/)
- [Data Source – LA Crime Data](https://catalog.data.gov/dataset/crime-data-from-2020-to-present)

---

## 🙏 Acknowledgments

Special thanks to:
- **Dr. Madhu Bala** for constant guidance.
- All peers and mentors who encouraged and reviewed this project.

---

