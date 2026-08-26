# 🏅 Paralympic Games Performance Analytics — Power BI Dashboard

An interactive **Power BI analytics dashboard** built to explore and analyze Paralympic Games performance from **1960 to 2018**.

The project transforms historical Paralympic Games data into an interactive analytical report covering **medal performance, participating countries, sports, historical trends, and country-level performance**.

---

## 📊 Project Overview

The **Paralympic Games Performance Dashboard** provides a comprehensive view of how countries and sports have performed throughout the history of the Paralympic Games.

The dashboard allows users to interactively explore:

* 🏟️ Games and participation statistics
* 🌍 Country-wise medal performance
* 🥇 Gold, Silver and Bronze medal distribution
* 🏃 Medal contribution by sport
* 📈 Gold-medal trends across different Games
* 🔎 Country and year-level performance analysis
* 🤖 AI-powered Key Influencers analysis
* 🎯 Interactive filtering by country, year and season

The objective of this project is to demonstrate how **Power BI can transform historical sports data into meaningful and interactive insights**.

---

## 🎯 Key Objectives

The project focuses on answering questions such as:

* Which countries have won the most medals?
* How has medal performance changed over the years?
* Which sports contribute the most medals?
* Which countries dominate gold-medal performance?
* How does a country's performance vary across different Paralympic Games?
* What factors are associated with higher or lower medal counts?
* How do Summer and Winter Paralympic Games compare?
* Which sports have the strongest influence on total medal counts?

---

## 📁 Dataset

The project uses a cleaned historical Paralympic Games dataset covering the period:

**1960 – 2018**

The cleaned dataset contains **2,209 records and 18 fields**, including information related to:

| Category      | Fields                                                    |
| ------------- | --------------------------------------------------------- |
| Games         | `games_code`, `games_year`, `games_city`, `games_country` |
| Geography     | `games_continent`                                         |
| Dates         | `games_start`, `games_end`                                |
| Season        | `games_season`                                            |
| Country / NPC | `npc`, `npc_new`, `npc_name`, `npc_rank`                  |
| Ranking       | `rank_type`                                               |
| Medals        | `npc_gold`, `npc_silver`, `npc_bronze`                    |
| Sports        | `sport_code`, `sport`                                     |

### Dataset Preparation

The original dataset was cleaned and prepared before being imported into Power BI.

The preparation process included:

* Data cleaning
* Handling missing values
* Standardizing country/NPC information
* Formatting date and numerical fields
* Preparing medal-related fields
* Structuring the dataset for Power BI analysis

---

# 📈 Dashboard Highlights

## 1. Executive Overview

The main dashboard provides a high-level summary of Paralympic Games performance.

### Key KPIs

The dashboard currently highlights:

* **26 Total Games**
* **73 Participating Countries**
* **35 Sports**
* **4,994 Gold Medals**
* **4,419 Silver Medals**
* **4,280 Bronze Medals**

These KPIs provide an immediate overview of the scale of the dataset and the historical Paralympic Games.

---

## 2. Country-wise Medal Performance

A country ranking visualization highlights the countries with the highest overall medal counts.

The dashboard can be used to compare medal performance across National Paralympic Committees (NPCs).

This makes it easier to identify historically strong Paralympic nations and compare their overall performance.

---

## 3. Medal Distribution by Sport

A donut chart shows the contribution of different sports to the total medal count.

The analysis highlights the relative importance of major sports such as:

* Athletics
* Swimming
* Alpine Skiing
* Cross-Country Skiing
* Table Tennis

This provides an interesting perspective on how medal opportunities are distributed across different Paralympic sports.

---

## 4. Gold Medal Analysis

The dashboard includes a dedicated analysis of **Athletics Gold Medals by Country and Year**.

This allows users to investigate:

* Which countries have historically dominated Athletics
* How gold-medal performance changed over time
* Which Games produced major changes in performance
* Country-level performance across different years

---

## 5. Historical Performance Trends

A multi-series line chart tracks **Gold Medal performance by country across different Games years**.

Users can identify:

* Long-term performance trends
* Periods of rapid growth or decline
* Changes in country dominance
* Exceptional performances during individual Games

---

## 6. AI-Powered Key Influencers

The dashboard also uses Power BI's **Key Influencers** visual to investigate the factors associated with changes in total medal counts.

For example, the analysis can identify sports where the average total medal count is lower or higher than the overall comparison group.

This adds an analytical layer beyond simple descriptive charts by helping answer:

> **"What factors are associated with higher or lower medal counts?"**

---

## 7. Interactive Tooltip Analysis

A dedicated tooltip page provides additional contextual information when users interact with dashboard elements.

This improves the user experience by allowing detailed information to appear without overcrowding the main dashboard.

---

# 🎛️ Interactive Features

The dashboard includes interactive slicers for:

* **NPC / Country**
* **Games Year**
* **Games Season**

  * Summer
  * Winter

There is also a **Clear All Slicers** option for quickly resetting the dashboard.

The report is designed so that selections made by the user dynamically update the visualizations and KPIs.

---

# 🛠️ Tools & Technologies

### Power BI

Used for:

* Data modeling
* Data transformation
* DAX calculations
* Interactive visualizations
* Key Influencers analysis
* Tooltip pages
* Dashboard design

### Microsoft Excel

Used as the source format for the cleaned dataset.

### Data Analysis Concepts

The project demonstrates:

* Exploratory Data Analysis (EDA)
* KPI development
* Trend analysis
* Comparative analysis
* Country-level analysis
* Sports-level analysis
* Interactive filtering
* AI-assisted analytics

---

# 🧮 Important Metrics

The dashboard uses medal-related calculations to derive meaningful performance indicators.

A basic total medal calculation can be represented as:

```text
Total Medals =
Gold Medals + Silver Medals + Bronze Medals
```

This metric is then used for country, sport and Games-level comparisons.

---

# 🖼️ Dashboard Pages

The Power BI report contains multiple analytical pages:

### 📌 Report

Main interactive dashboard containing:

* KPI cards
* Country ranking
* Medal distribution
* Gold-medal analysis
* Historical trends
* Automated insights

### 🔍 Key Influencers

Power BI AI-powered analysis identifying factors associated with changes in total medal counts.

### 💡 Tooltip_Medals

A custom tooltip page providing additional medal-related information during interaction with the main report.

---

# 📂 Repository Structure

A recommended repository structure is:

```text
Paralympic-Games-PowerBI-Analytics/
│
├── README.md
│
├── Dataset/
│   └── Paralympics Dataset cleaned.xlsx
│
├── PowerBI/
│   └── Paralympics Games Performance Dashboard.pbix
│
├── Screenshots/
    ├── Report.png
    ├── Key-influencers.png
    └── Tooltip-medals.png

```

---

# 🚀 How to Use

1. Clone or download this repository.
2. Open the `.pbix` file using **Microsoft Power BI Desktop**.
3. If required, update the dataset/file path.
4. Refresh the data.
5. Use the slicers to explore different countries, Games years and seasons.
6. Interact with the charts to perform deeper analysis.

> **Note:** Power BI Desktop is required to open and edit the `.pbix` file.

---

# 💡 Key Insights

Some of the notable observations from the dashboard include:

* The **United States** has the highest overall medal count among the countries displayed in the dashboard.
* Athletics represents one of the largest contributors to the overall medal count.
* Medal performance varies significantly between countries and across different Games years.
* Historical trends show periods of significant changes in country-level gold-medal performance.
* Sports have different relationships with total medal counts, which can be explored through the Key Influencers analysis.

The dashboard is designed to allow users to go beyond these observations and discover additional insights interactively.

---

# 📌 Project Purpose

This project was created as a practical **Power BI portfolio project** to demonstrate the ability to:

> **Transform raw historical data into an interactive, visually compelling and insight-driven analytical dashboard.**

Rather than presenting only static statistics, the project focuses on **exploration, comparison, trend analysis and interactive storytelling**.

---

# 🔮 Future Improvements

Possible future enhancements include:

* Adding athlete-level analysis
* Adding gender-based analysis
* Adding event-level medal analysis
* Creating medal efficiency metrics
* Adding country growth/decline indicators
* Adding advanced DAX measures
* Automating data updates
* Connecting directly to a live or regularly updated data source
* Publishing the dashboard through Power BI Service
* Adding additional predictive or statistical analysis

---

# 👨‍💻 Author

**Santu Samanta**

This project is part of my data analytics and business intelligence portfolio, demonstrating practical experience with **Power BI, data transformation, visualization and analytical storytelling**.

---

## ⭐ If you find this project useful

Feel free to explore the dashboard, analyze the historical trends and use the project as inspiration for your own Power BI analytics projects.

If you like the project, consider giving the repository a ⭐.
