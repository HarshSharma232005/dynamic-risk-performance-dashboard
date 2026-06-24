# Dynamic Risk Monitoring & Project Performance Analytics Dashboard

An interactive, end-to-end Power BI analytics solution engineered to help organizations monitor portfolio risk, analyze team dynamics, benchmark execution performance, and optimize financial efficiency across multiple project domains (IT, Construction, Healthcare, Manufacturing, Marketing, and R&D).

## 📊 Dashboard Pages & Visual Flow

The Power BI report is divided into logical analytical views for granular exploration:

1. **Problem Statement:** Defines core business questions surrounding early performance indicators, methodology impact, and optimal stakeholder configurations.
2. **Project Performance Assessment:** Evaluates portfolio risk distribution, month requirements, and budget allocations by funding source. Features a localized **Risk Heat Map** across project phases.
3. **Project Performance Benchmarking:** Digs into team metrics, correlation between team turnovers, technical familiarity, and project success parameters.
4. **Area-Wise Analysis:** Geographical distribution map coupled with team methodology utilization ratios (Agile, Scrum, Waterfall, Kanban, Hybrid).
5. **Drill-Through Summary:** Granular tabular breakups of metrics across project types, phases, stakeholder availability, and historical incident records.
6. **Insights View:** An executive narrative detailing critical data takeaways and recommendations.

---

## 💡 Key Business Insights Captured

* **Risk & Domain Dominance:** IT and Construction projects dominate portfolio volume and exhibit the highest complexity scores. IT carries the highest concentrated risk incidents, peaking significantly during the **Execution** and **Monitoring** phases.
* **Financial Management:** The portfolio operates at a highly efficient overall **Budget Utilization Rate of 0.95**, with External and Internal funding driving the bulk of a $1.08M utilized budget. 
* **Team Dynamism & Success:** Higher technical familiarity directly correlates with increased project success and lower team turnover rates. Conversely, technology unfamiliarity stands out as a core operational bottleneck.
* **Methodology Trends:** Agile and Scrum frameworks heavily dominate team resource allocation, making up the largest share of overall team sizing.

---

## 🛠️ Tech Stack & Tools Used
* **Business Intelligence:** Microsoft Power BI Desktop
* **Data Visualizations Used:** Risk Heat Maps, Tree Maps, Ribbon/Sankey-style flow charts, Gauge cards, and Custom Map Layers.
* **Data Modeling:** Star Schema design with optimized relationships, cross-filtering, and dedicated drill-through target pathways.

---

## 🚀 How to View the Project

1. Download or clone this repository.
2. Ensure you have the latest version of [Power BI Desktop](https://powerbi.microsoft.com/) installed.
3. Open the `.pbix` file located in the root directory (e.g., `Project_Performance_Dashboard.pbix`).
4. Use the custom navigation panel on the homepage to traverse through the individual dashboard views.

## 📂 Repository Structure
```text
├── Data/                     # Sample datasets used for modeling (if applicable)
├── Screenshots/              # Dashboard page views for quick previewing
├── Project_Performance.pbix  # Core Power BI File
└── README.md                 # Project Documentation
