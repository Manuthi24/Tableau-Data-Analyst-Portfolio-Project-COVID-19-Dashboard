# 🌐 COVID-19 Dashboard Project (Tableau)

<p align="center">
  <a href="https://public.tableau.com/app/profile/manuthi.magedaragama/viz/CovidDashboard_17680552730320/Dashboard1">
    <img src="assests/Covid 19 Dashboard.png" width="800"/>
  </a>
</p>

<p align="center">
  <a href="https://public.tableau.com/app/profile/manuthi.magedaragama/viz/AirBnBFullProject_17682484493670/Dashboard1">
    👉 View Live Dashboard
  </a>
</p>

## 📌 Project Overview
This project is the **second part of a Data Analyst portfolio series**. Building on an initial SQL data exploration project, this stage focuses on transforming queried data into a **professional and interactive dashboard using Tableau**. The aim is to provide a **beginner-friendly roadmap** for creating visualisations that can be showcased on a **resume or LinkedIn**.

---

## 🛠 Data Sources & Tools
- **Data Source:** COVID-19 dataset (previously processed using SQL)
- **SQL:** Used to write and tweak queries for extracting specific data for visualisations
- **Excel:** Used as a staging area for saving query results (Tableau Public cannot connect directly to SQL databases)
- **Tableau Public:** Used to create and host the final dashboard online

---

## 🧹 Data Preparation Steps
1. **Run SQL Queries:** Four specific queries generated the necessary data tables.
2. **Export to Excel:** Data was copied from SQL Server (including headers) and saved into separate Excel files (Tableau Table 1 through 4).
3. **Data Cleaning:**
   - **Handling Nulls:** In tables 3 and 4, null values were replaced with zeros to ensure Tableau assigned the correct numeric data types.
   - **Formatting:** Date columns were formatted to "Short Date" for chronological consistency.
4. **Import to Tableau:** Each Excel file was added as a new data source within Tableau.

---

## 📊 Dashboard Components
The final dashboard consists of **four primary visualisations**:

1. **Global Numbers (Text Table):**  
   Displays **Total Cases**, **Total Deaths**, and **Death Percentage** (formatted to two decimal places for accuracy).

2. **Deaths by Continent (Bar Chart):**  
   Descending bar graph showing **Total Death Count** across Africa, Asia, Europe, North America, Oceania, and South America.

3. **Infection Rate by Country (Map):**  
   Geographic heat map showing **Percent of Population Infected per country**.  
   - Map Background: *Outdoors*  
   - Colour Palette: *Red-Gold*

4. **Infection Timeline (Time Series):**  
   Line graph showing the progression of **Percent Population Infected** over time for countries like **United States, United Kingdom, and India**, including a **predictive forecast** for future trends.

---

## 🔗 How to View
The completed dashboard is published on **Tableau Public**. Explore the interactive version and use the filters to analyze the data:

[View Dashboard on Tableau Public](https://public.tableau.com/app/profile/manuthi.magedaragama/vizzes)

---

## 📝 Key Learnings
- Learned to **connect SQL-extracted data to Tableau via Excel**.
- Practiced **data cleaning and formatting** for dashboard readiness.
- Gained experience in **visual storytelling** through interactive charts and maps.
- Learned how to create **predictive forecasts** and display trends over time.

---

## ⚡ Future Improvements
- Connect Tableau directly to a live SQL database for **real-time updates**.
- Add **more interactivity**, such as drop-down filters for continents and countries.
- Incorporate additional datasets, such as **vaccination rates** and **hospitalization data**.

---

## 👨‍💻 Author
**Manuthi Magedaragama**  
Data Science Enthusiast | Exploring the World of Data & Analytics  

---

<p align="center">
  <em>Interactive dashboards are powerful tools for data storytelling and informed decision-making.</em>
</p>
