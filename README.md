# 🌦️ Weather Data ETL Pipeline

### AnalystLab Africa — Data Analytics Internship | Week 7

**Project Executed By:** Egbetola Olanrewaju Emmanuel

---

## 📌 Project Overview

This project was completed as part of the **Data Analytics Internship with AnalystLab Africa**.

The project demonstrates the development of a basic **ETL (Extract, Transform, Load) pipeline** using real-time weather data obtained from the **OpenWeather API**.

Weather data was collected for **Leiria, Lisbon, and Porto**, transformed using Python and Pandas, stored in CSV and Excel formats, and analyzed to generate basic insights.

---

## 🎯 Project Objective

The objective of this project is to demonstrate how data can be:

- Extracted from an external API
- Cleaned and transformed into an analysis-ready format
- Stored for future use
- Analyzed to generate meaningful insights
- Processed through a reusable ETL pipeline script

---

## 🌐 Data Source

**OpenWeather API**

The OpenWeather API was used to collect real-time weather information for:

- Leiria
- Lisbon
- Porto

Relevant fields collected included:

- City
- Temperature
- Feels-like temperature
- Humidity
- Weather condition
- Weather description
- Wind speed
- Atmospheric pressure
- Date and time

---

## 🔄 ETL Process

### Extract

Python's `Requests` library was used to connect to the OpenWeather API and retrieve real-time weather data for the selected cities.

### Transform

The extracted data was processed using **Pandas**. The transformation included:

- Organizing the data into a structured DataFrame
- Renaming and standardizing columns
- Converting data types
- Standardizing weather descriptions
- Removing duplicate records
- Preparing a clean dataset for analysis

### Load

The processed data was saved in:

- `raw_weather_data.csv`
- `Cleaned_weather_data.csv`
- `Weather_ETL_Data.xlsx`

A reusable Python ETL pipeline script was also created to automate the Extract, Transform, and Load workflow.

---

## 📊 Key Findings

The weather data collected showed:

- 🌡️ **Lisbon recorded the highest temperature:** 22.68°C
- 💧 **Porto recorded the highest humidity:** 88%
- 💨 **Lisbon recorded the highest wind speed:** 13.38 m/s

These findings represent weather conditions at the specific time the data was collected and are not intended to represent long-term climate patterns.

---

## 🛠️ Tools & Technologies

- Python
- Pandas
- Requests
- Matplotlib
- Jupyter Notebook
- OpenWeather API
- Microsoft Excel

---

## 🔐 API Security

The OpenWeather API key was **not hard-coded** into the project files.

An environment variable was used to securely access the API key, preventing sensitive credentials from being exposed in the GitHub repository.

---

```markdown
## 🎥 Demo Video

A short demonstration of the project covering data extraction, transformation, loading, analysis, and ETL automation.

[▶️ Watch the Week 7 ETL Pipeline Demo](https://drive.google.com/file/d/1-u4PZorR_iHoQ51yc82NCquCIBm-nXbZ/view?usp=sharing)

---

## 💡 Key Learning

This project strengthened my understanding of how ETL pipelines can transform raw data from external sources into clean, structured, and analysis-ready information.

It also provided practical experience with API integration, data transformation using Pandas, data storage, visualization, automation, and API credential security.

---

## 👤 Author

**Egbetola Olanrewaju Emmanuel**

Data Analytics Intern | AnalystLab Africa

---

## 🔗 Project Links

- **🎥 Demo Video:** [Watch Demo](https://drive.google.com/file/d/1-u4PZorR_iHoQ51yc82NCquCIBm-nXbZ/view?usp=sharing)
- **💼 LinkedIn:** www.linkedin.com/in/egbetolaolanrewaju

---

## 📁 Project Structure

```text
Week7/
│
├── raw_weather_data.csv
├── Cleaned_weather_data.csv
├── Weather_ETL_Data.xlsx
├── README.md
│
├── ETL Pipeline Script/
│   └── weather_etl_pipeline.py
│
└── Week7_Weather_ETL.ipynb
