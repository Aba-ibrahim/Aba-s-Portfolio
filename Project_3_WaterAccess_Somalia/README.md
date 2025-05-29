# 💧 Water Access Analytics Dashboard – Somalia (Policy & Infrastructure Insights)

## 👨🏽‍💻 Chemical Engineer & Data Analyst:
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
- Simulate water access data for high-growth urban districts
- Create a centralized analytics dashboard to explore coverage rates, equity gaps, and infrastructure needs
- Showcase how Power BI can help urban planners, government units, and NGOs make data-informed decisions
- Embed interactive visuals to illustrate disparities and prioritize future investments

---

## 🛠 Tools & Technologies Used

### 🔍 Data Simulation & Management
- **Microsoft Excel / CSV:** Created and managed a mock dataset simulating daily water access data across Somali districts.
- **Data Modeling:** Defined relationships between population estimates, access rates, and infrastructure status to support KPIs and trend analysis.

### 📊 Visualization & Analytics
- **Power BI:** Developed interactive dashboards to visualize water access trends, infrastructure health, and service equity across regions.
- **DAX (Data Analysis Expressions):** Built custom measures and conditional formatting rules to enable dynamic filtering, trend detection, and anomaly highlighting.

### 📁 Documentation & Version Control
- **Markdown (README.md):** Documented project context, problem statement, approach, and outcomes in a professional format.
- **Git & GitHub:** Version-controlled the project structure, shared code and visuals, and embedded static dashboard previews for portfolio presentation.

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
| `Water_Access_Somalia_Updated.csv` | Simulated dataset of water-access records by district   |
| `Dashboard.png`                    | Static screenshot of the Power BI report               |
| `WaterAccess_Somalia.pbix`         | Full interactive Power BI file (optional download)      |
| `README.md`                        | Project overview and documentation                     |

---


---

## 🛠 Tools & Technologies Used

- **Power BI** – dashboard design, storytelling
- **Excel/CSV** – simulated dataset management
- **Markdown** – project documentation
- **GitHub** – portfolio showcase

---

## 🖼️ Dashboard Preview
![Dashboard](./PowerBI_Report/Dashboard.png)


---

## 📘 Lessons Learned

- **Data quality is foundational:** Clean, context-rich datasets are indispensable for any meaningful infrastructure analysis.  
- **Visual storytelling drives action:** Clear, interactive narratives translate complex water-access data into policy-ready insights.  
- **Local simulation builds empathy:** Replicating on-the-ground infrastructure challenges helps stakeholders understand urgency and prioritize resources.  
- **DAX and dynamic filtering matter:** Well-crafted measures and slicers elevate the dashboard from static reporting to an exploratory decision-support tool.


---

