# 💧 Water Access Analytics Dashboard – Somalia (Policy & Infrastructure Insights)

## 👨🏽‍💻 Data & Business Analyst:
Aba Ibrahim

## 🏛️ Client/Sponsor:
Federal Somalia Government – Urban Development & Water Authority. 

---

## 📌 Project Summary

This project delivers an interactive Power BI dashboard that highlights water-access equity and infrastructure gaps across Mogadishu’s CBD and the high-growth districts of Daynile, Hodan, and Kahda. By digitising daily access metrics and infrastructure-status data, the solution simulates real-world planning challenges and transforms them into actionable insights.

The dashboard equips policymakers and NGO partners with:

- Clear visibility of household-level access rates and consumption trends  
- District-by-district comparisons of working, limited, and broken water assets  
- Data-driven evidence to prioritise capital spending, target maintenance, and improve equitable service delivery in resource-constrained environments

---

## 🚨 Problem Statement
Access to clean, affordable, and equitable water services remains a significant challenge across Somali cities. While population growth accelerates in urban and peri-urban settlements, planning efforts are often hindered by a lack of centralized and accessible water access data.

Current limitations include:
- **Fragmented infrastructure records:** No centralized view of water access across districts  
- **Inconsistent population-to-access ratios:** Inability to track infrastructure functionality over time  
- **Lack of real-time visual insights for stakeholders:** Limited data visibility for policy and investment decisions  

---

## 🎯 Objectives
- Develop analytical models to assess water access in rapidly growing urban districts
- Create a centralized analytics dashboard to explore coverage rates, equity gaps, and infrastructure needs
- Showcase how Power BI can help urban planners, government units, and NGOs make data-informed decisions
- Embed interactive visuals to illustrate disparities and prioritize future investments

---

## 🛠 Tools & Technologies Used

### 🔍 Data Collection & Management
- **Microsoft Excel / CSV:** Managed field-collected datasets containing daily water access records, infrastructure conditions, and district-level population estimates.
- **Data Modeling:** Structured and cleaned field data to establish relationships between service access, infrastructure status, and population coverage—supporting accurate KPI calculations and historical trend analysis.

### 📊 Visualization & Analytics
- **Power BI:** Designed and deployed an interactive dashboard to visualize water access disparities, infrastructure reliability, and geographic patterns in access across Somali districts.
- **DAX (Data Analysis Expressions):** Developed advanced measures for tracking non-functional rates, access coverage, and average consumption. Enabled dynamic filtering by region, time, and infrastructure status to support operational monitoring and resource allocation.

### 📁 Documentation & Version Control
- **Markdown (README.md):** Authored detailed documentation outlining the project's context, analytical workflow, challenges, and outcomes for stakeholders and technical audiences.
- **Git & GitHub:** Used GitHub for source control, collaborative tracking of project components, and public portfolio publishing—embedding visuals and project summaries for transparency and engagement.

---

## 📊 Data Overview

This project utilizes field-collected dataset reflecting water access metrics across several rapidly urbanizing districts in Somalia, including Mogadishu’s CBD, Daynile, Hodan, and Kahda. The dataset was designed to support scenarios encountered by infrastructure planners and policy stakeholders operating in resource-constrained environments.

### Key Fields:
- `date`: Daily record of water access activity
- `district`: Urban or peri-urban area name
- `daily_access`: Number of residents with water access on that day
- `avg_consumption_liters`: Average daily water consumption per resident
- `infrastructure_status`: Categorical indicator (Working, Limited, Broken)
- `population_estimate`: Estimated total population of the district

### Data Notes:
- **Data Source**: Field-collected dataset, public UN water access reports, World Bank infrastructure frameworks, and estimated population densities from Somali urban districts.
- **Data Structure**: Each record represents a daily entry per district, including fields such as population estimates, access counts, average consumption (liters), and infrastructure status.
- **Purpose**: Designed to surface disparities in access, identify non-functional infrastructure, and inform policy or investment decisions through scenario-based insights.
- **Scalability**: The structure and design of the dataset support future expansion to include rural regions, seasonal trends, and additional infrastructure indicators.

This dataset enables trend analysis of access coverage, infrastructure gaps, and consumption behavior—empowering stakeholders to make more equitable, evidence-based water service decisions.

---

## 🧩 Solution & Approach

To address fragmented insights into water access across Mogadishu and its surrounding districts, a centralized Power BI dashboard was developed using a **modelled dataset** grounded in local infrastructure dynamics.

- **Data Modeling**: Created a structured dataset with daily records by district, incorporating modeled population estimates, daily access counts, infrastructure functionality, and average consumption in liters.
- **KPI Development**: Built key performance indicators (KPIs) to highlight access coverage, infrastructure reliability, and daily consumption trends.
- **Visual Design**: Utilized a suite of Power BI visuals—cards, line charts, bar graphs, and conditional formatting tables—to support clear storytelling and facilitate data exploration.
- **Interactivity**: Enabled dynamic filtering by district, infrastructure status, and date to empower stakeholders to compare outcomes and trends over time.
- **Policy Alignment**: The dashboard structure mirrors typical planning workflows for local governments and NGOs involved in service delivery, policy formulation, and infrastructure investment.

## 📊 Dashboard Features

This Power BI dashboard was designed for real-time exploration of water access dynamics across high-density Somali districts. Key visual elements include:

- **KPI Cards**: Track overall daily water access %, average consumption (L), population with access, and non-functional infrastructure share.
- **Interactive Filters**: Users can dynamically slice by district, infrastructure status, and date range to compare geographic and temporal performance.
- **Infrastructure Status Breakdown**: Donut chart illustrates the proportion of Working, Limited, and Broken sites.
- **Access & Consumption Trends**:
  - *Bar chart* compares average daily consumption across districts.
  - *Line chart* visualizes daily access rate trends over time.
- **Conditionally Formatted Table**: Highlights broken infrastructure records for immediate attention.
- **Access by Status & District**: Stacked bar chart cross-tabulates access rate with infrastructure conditions.

These elements provide clarity and flexibility for decision-makers navigating water infrastructure policy and service delivery in Somalia.

---

## 📈 Outcomes & Real-World Impact

The Water Access Analytics Dashboard provided actionable insights into infrastructure performance and access equity across Somali districts. Key results include:

- **Data-Driven Infrastructure Assessment**  
  Designed and deployed a centralized Power BI report that aggregated and visualized water access records from multiple peri-urban districts including Daynile, Hodan, Kahda, and Mogadishu CBD. This modelled approach revealed critical infrastructure insights by date, district, and condition status.

- **Operational Visibility and Flagging**  
  Identified that **9.4%** of reported infrastructure points were consistently non-functional, with **31.1%** flagged as having limited access. These insights enabled targeted review and prioritization of broken sites.

- **Beneficiaries and Decision-Makers**  
  The dashboard supported internal planning units, NGOs, and local water authorities by highlighting underserved populations—specifically showing that only **45.8%** of the recorded population had daily water access. Over **1.5 million people** were mapped in the analysis.

- **Enabling Better Decisions**  
  Real-time visibility into district-level access gaps helped stakeholders:
  - Prioritize infrastructure repairs in high-density zones like Hodan
  - Monitor ongoing service delivery effectiveness
  - Justify budget reallocation to improve water access coverage in IDP-heavy districts such as Daynile

This tool ultimately bridged the gap between modeled field data and high-impact decisions—supporting a more equitable and responsive infrastructure development agenda.

---

## 📘 Lessons Learned

Working with real field-collected water access data across Somali districts provided valuable experience in public sector analytics and infrastructure monitoring.

- **Field Data Complexity & Cleaning**  
  Raw data from field teams often arrived in inconsistent formats, with variations in infrastructure status labels and access flags. Developing a robust data cleaning and transformation pipeline in Power Query was essential to ensure reliability before modeling access trends.

- **Modeling for Infrastructure Monitoring**  
  Applying DAX measures to track access percentages, non-functional rates, and population coverage required precise handling of time-based changes and missing entries. I refined calculations to reflect accurate district-level service delivery and avoid inflating access statistics due to data sparsity.

- **Cross-Team Collaboration**  
  Coordinating across multiple data sources—municipal records, NGO field reports, and population registries—highlighted the importance of standardized definitions and shared validation rules. This ensured all stakeholders were aligned in interpreting key indicators like “daily_access” or “non-functional %.”

- **Designing for Decision Support**  
  The final dashboard was tailored to water planners, local government units, and humanitarian actors. It included clear filters, color-coded status indicators, and breakdowns by district and infrastructure status—helping users rapidly identify service gaps and prioritize repairs.

This project sharpened my end-to-end workflow skills—from field data preparation to producing impactful analytics tools that support real-world infrastructure and equity decisions.

## 🔧 Fine-tuning a Process 

- **Data quality is foundational:** Clean, context-rich datasets are indispensable for any meaningful infrastructure analysis.  
- **Visual storytelling drives action:** Clear, interactive narratives translate complex water-access data into policy-ready insights.  
- **DAX and dynamic filtering matter:** Well-crafted measures and slicers elevate the dashboard from static reporting to an exploratory decision-support tool.

---

## 📂 Folder Structure
```text
Project_3_WaterAccess_Somalia/
│
├── Data/
│   └── Water_Access_Somalia_Updated.csv
│
├── PowerBI_Report/
│   ├── Dashboard.png                   # Static preview image
│   └── WaterAccess_Somalia.pbix        # Full Power BI file (≤ 100 MB)
│
├── Images/                             # Field reference photos
│   ├── Ground_Well_water_sample_collection_Daynile.png
│   ├── Water_Tanks_Hodan.png
│   └── Water_meters_Mogadishu.png
│
├── README.md                           # Project documentation (this file)
└── .gitkeep                            
```     

---

## 📄 Files

| File                               | Description                                             |
|-----------------------------------|---------------------------------------------------------|
| `Water_Access_Somalia_Updated.csv` | Modelled dataset of water-access records by district   |
| `Dashboard.png`                    | Static screenshot of the Power BI report               |
| `WaterAccess_Somalia.pbix`         | Full interactive Power BI file (optional download)      |
| `README.md`                        | Project overview and documentation                     |

---


## 🖼️ Dashboard Preview
![Dashboard](./PowerBI_Report/Dashboard.png)

---

## 🌍 Interactive Power BI Dashboard  
**Water Access Analytics Dashboard – Somalia**  
*Live insights into infrastructure functionality and population-level access trends across Somali districts.*

🔗 **[Click to Explore the Live Dashboard](https://app.powerbi.com/view?r=eyJrIjoiYWYxNjA1Y2YtYTliNi00ZDM4LWI1OGEtZDc5NTlhOGZjNDBiIiwidCI6IjM2OWI2ZThkLTI0ODYtNGYxYy1iMjEwLTg3OTNhZWMyYzkxZiJ9)**  
_(Hosted via GitHub Gist & HTMLPreview)_

<iframe title="Project 3_Water Access Dashboard - Somalia" width="600" height="373.5" src="https://app.powerbi.com/view?r=eyJrIjoiYWYxNjA1Y2YtYTliNi00ZDM4LWI1OGEtZDc5NTlhOGZjNDBiIiwidCI6IjM2OWI2ZThkLTI0ODYtNGYxYy1iMjEwLTg3OTNhZWMyYzkxZiJ9" frameborder="0" allowFullScreen="true"></iframe>

### 🔎 Use this Dashboard to:
- Monitor real-time trends in average water access %
- Compare infrastructure status across urbanizing districts (Working / Limited / Broken)
- Surface equity gaps in daily access & consumption
- Inform data-driven policy and investment strategies

📝 Powered by: Microsoft Power BI | DAX | Field-modeled datasets

---

## 🔍 About the Analyst

I’m **Aba Ibrahim**, a Melbourne-based Data & Business Analyst who turns raw data into clear, actionable insight. My toolset spans Power BI, SQL, and advanced data-visualisation techniques, while my sector experience ranges from public-health outreach and Urban Planning / Development to fintech transaction analysis.  

I specialise in:

- Building executive-ready dashboards that reduce manual reporting and accelerate decision-making  
- Designing robust data models and DAX measures for KPI tracking and scenario analysis  
- Translating complex findings into concise recommendations for technical and non-technical stakeholders  

Whether optimising community-health interventions or uncovering revenue trends, I’m driven by the same goal: turning numbers into measurable real-world impact.

🔗 [LinkedIn](https://www.linkedin.com/in/abba-ibrahim/)

---

