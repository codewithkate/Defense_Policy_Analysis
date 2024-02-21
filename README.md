# Excess Defense Article Analysis

## Table of Contents

- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools](#tools)
- [Data Preparation](#data-preparation)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Analysis](#data-analysis)
- [Findings](#findings)
- [Limitations](#limitations)
- [References](#references)

### Project Overview
---
This data analysis project aims to provide insights into excess defense article transfers over the past decade. By analyzing various aspects of EDA transfers, we can identify trends in military sales and grant transfers, make better decisions about EDA eligible countries, and gain a deeper understanding of how small arms and light weapons impact countries.

### Data Sources
---
Transfer Data: The primary dataset used for this analysis is the "eda_data.csv" file, containing detailed information about each transfer request made by a U.S. partner nation between 2010 and 2020. [Original dataset](https://www.dsca.mil/programs/excess-defense-articles-eda)

### Tools
---
- Excel - Data Cleaning
- Python - Data Analysis
- Tableau - Creating dashboard

### Data Preparation
---
In the initial data preparation phase, I performed the following tasks:
1. Data loading and inspection.
2. Handling missing and null values.
3. Identifying outliers.
4. Data cleaning and formatting.
5. Pivoting and joining tables.

### Exploratory Data Analysis
---
EDA involved exploring the sales and transfer data to answer key questions, such as:

**EDA Transfer Costs & Trends**
- What are the dollar values of excess defense articles?
- Which items are most frequently requested?
- *Can we identify patterns or shifts in the volume of transfers based on geopolitical conflicts and events?
- Can we segment countries based on their requests?

**EDA Process Overview**
- What are the peak transfer periods?
- How efficient is the process of granting surplus transfers?
- *What proportion of surplus transfers sold thought the Foreign Military Sales (FMS) program, and how does this impact cost-effectiveness?
- *Are there patterns or outliers in the admin fees paid by customers? How does this relate to Packaging, Crating & Handling (PC&H) fees?

**Risk Assessment & Impact Analysis**
- *How can we quantify the level of risk associated with dispersing military equipment?
- How often are requests delivered to a country with a higher likelihood of diversion to bad actors or misuse?
- Is there a correlation between military equipment transfers and human rights violations?

*AI-assisted questions based on human-generated notes about cited sources.

### Data Analysis
---
[View the final visualization](https://public.tableau.com/app/discover)

### Findings
---
The analysis results are summarized as follows:
1. Description of costs and trends
2. Description the EDA process
3. Description of risk and impact

### Recommendations
---
Based on the analysis, I recommend the following actions:
- List item
- List item
- List item

### Limitations
---
TBD

### References
---
- The Defense Security Operation Agency's [Excess Defense Article Database Tool](https://www.dsca.mil/programs/excess-defense-articles-eda) (Accessed on Feb 16, 2024)
- The U.S. Navy's [Excess Defense Articles page](https://www.secnav.navy.mil/nipo/Pages/About/Security%20Assitance/Excess-Defense-Articles.aspx#:~:text=Defense%20articles%20and%20military%20equipment,vehicles%2C%20aircraft%2C%20and%20ships.) (Accessed on Feb 17, 2024)
- Defense Logistics Agency's [Foreign Military Sales page](https://www.dla.mil/Disposition-Services/Offers/FMS/) (Accessed on Feb 20, 2024)
- [Cleaning out the garage](https://www.army.mil/article/226448/cleaning_out_the_garage) by Marcus Mackey, U.S. Army Security Assistance Command (2019)
- [Deadly Garage Sales](https://jqas.org/wp-content/uploads/2022/07/Jarocki-Analysis.pdf) by Andrew Jarocki, Marcellus Policy Analysis (2022)
- [2021 Arms Sales Risk Index](https://www.cato.org/study/2021-arms-sales-risk-index) by A. Trevor Thrall and Jordan Cohen (2022)
- [Security Assistance Monitor](https://securityassistance.org/) by the Center for International Policy (CIP)
- [Fragility States Index](https://fragilestatesindex.org/excel/) by the Fund For Peace (Accessed on Feb 20, 2024)
