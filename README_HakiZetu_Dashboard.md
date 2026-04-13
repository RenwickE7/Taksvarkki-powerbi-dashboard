### Haki Zetu — Daraja la Maisha Mema: Power BI Dashboard

**Client:** Undugu Society of Kenya (USK)  
**Funder:** Taksvärkki ry (Finland)  
**Project Period:** 2026 – 2029  
**Tool:** Microsoft Power BI Desktop (Report Format v3.2)  
**Dashboard File:** `Taksvärkki71.pbix`  
**Last Updated:** April 2026

\---

## Overview

This Power BI dashboard was built for **Undugu Society of Kenya (USK)** to support monitoring and reporting for the **Haki Zetu — Daraja la Maisha Mema** project, a four-year initiative funded by **Taksvärkki ry**, a Finnish development organization. The project works to strengthen the rights and wellbeing of street-connected children and youth across Kenya.

The dashboard provides real-time visibility into programme activities, financial performance, geographic reach, and progress against targets — designed for use by both USK programme teams and Taksvärkki's reporting requirements.

\---

## Dashboard Structure

The report contains **4 pages**:

|Page|Description|
|-|-|
|**Overview**|Programme-level KPIs, beneficiary counts, and high-level outcome indicators|
|**Activity Plan**|Activity tracking against the project logical framework, including completion status and timelines|
|**Financials**|Budget utilization, expenditure tracking, and financial summary by programme component|
|**Regional Map View**|Geographic distribution of project activities across Nairobi, Kisumu, and Eldoret|

\---

## Key Features

### Regional Map Visual

* An **interactive map** visualizes city-level programme reach across Kenya's three main project locations.
* Bubble/marker styling uses USK brand colors to differentiate sites and activity intensity.
* Supports spatial reporting requirements for international donors.

### KPI Cards \& Summaries

* 7 card visuals track headline indicators including beneficiary numbers, activity completion rates, and outcome milestones.
* Designed for quick read-off by programme managers and finance staff.

### Data Visualizations

* **Donut charts (×3)** — proportional breakdowns by category (e.g., gender, programme stream, activity type).
* **Clustered bar chart** — activity-level output comparison across cities or reporting periods.
* **Bar charts (×2)** — performance against planned targets.
* **Pivot table** — detailed cross-tabulation of activities, outputs, and locations.
* **Table visual** — granular data view for audit and verification purposes.
* **Slicers (×4)** — dynamic filtering by city, activity type, reporting period, and outcome area.

### Activity Plan Tracking

* Dedicated page structured around the project's logical framework, allowing programme officers to track planned vs. actual activities.
* Linked to the project's Excel workbook data model for seamless updates as field data is captured.

### Financials Page

* Budget vs. expenditure tracking at component level.
* Designed to align with Taksvärkki's reporting template and Finnish development cooperation standards.

### Branding \& Theme

* Custom Power BI theme using USK brand green (`#1A6B3C`) and Taksvärkki amber (`#E8820A`).
* Background palette: soft off-white (`#F5F7F6`) with green OutSpace (`#E8F5E9`) for visual clarity.
* Dual logo placement: **Taksvärkki ry** and **Undugu Society of Kenya** on all pages.
* Page navigation via **16 action buttons** for a polished, app-style experience.

\---

## Technical Highlights

* **Multi-page architecture** structured around the project's reporting framework (Overview → Activities → Financials → Geography).
* **4 slicers** enable multi-dimensional filtering, allowing users to slice data by location, period, and programme area simultaneously.
* **Map integration** built using Power BI's native map visual, with geographic coordinates sourced from a dedicated `Map Locations` sheet in the underlying Excel workbook.
* **Pivot table** supports cross-analysis of activities and outcomes in a compact, tabular format suited for donor reporting.
* Report built in parallel with the `HakiZetu\_Data\_2026.xlsx` workbook, which structures data across Targets, Activities, Budget, and Field Tracking sheets.

\---

## Data Sources

> \*\*Note:\*\* The underlying data model and source files are not included in this repository for data privacy and confidentiality reasons. The `.pbix` file contains the report layout, visual configuration, and data model structure only.

Primary data sources used during development:

* `HakiZetu\_Data\_2026.xlsx` — master workbook containing:

  * Targets Table (indicator targets by city and year)
  * Known Budget Data (approved budget by component)
  * Known Activities (logical framework activities)
  * Field Tracking Tables (awaiting live data entry)
* Project log frame and work plan documents
* Geographic coordinates for Nairobi, Kisumu, and Eldoret offices

\---

## Skills Demonstrated

* Power BI report design (multi-page, multi-audience)
* Geographic/spatial visualization using Power BI map visuals
* Financial dashboard design aligned to donor reporting requirements
* Activity plan and log frame tracking
* Custom theme creation and brand implementation
* Excel–Power BI data model integration
* NGO M\&E systems and development sector reporting

\---

## About the Developer

This dashboard was developed by **Renwick Etemesi**, a data analyst with specialized experience in Power BI and data visualization for the NGO and development sector. Based in Kenya, with a focus on building monitoring, evaluation, and reporting tools that serve both field teams and international donors.

* **Tools:** Power BI, Excel, DAX, Power Query
* **Sector experience:** Child rights, youth development, international development cooperation (Finland–Kenya)

\---

## Repository Contents

```
├── Taksvärkki71.pbix          # Power BI report file
└── README.md                  # This file
```

\---

*For questions about this project or to discuss data consulting work, feel free to reach out via Linkedin- www.linkedin.com/in/*

*renwick-etemesi.*

