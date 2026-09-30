# 📊 Looker Studio Recruitment Analytics Dashboard

[![Google Looker Studio](https://img.shields.io/badge/Google%20Looker%20Studio-4285F4?style=for-the-badge&logo=google&logoColor=white)](https://lookerstudio.google.com/)
[![Google Data Studio](https://img.shields.io/badge/Google%20Data%20Studio-FFC107?style=for-the-badge&logo=googleanalytics&logoColor=black)](https://lookerstudio.google.com/)
[![Business Intelligence](https://img.shields.io/badge/Business%20Intelligence-2C3E50?style=for-the-badge&logo=chartdotjs&logoColor=white)](#)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](LICENSE)

An interactive recruitment and talent analytics dashboard designed in Google Data Studio (now Looker Studio). It provides talent acquisition teams and HR leadership with comprehensive visibility into applicant funnels, role compensation benchmarks, recruiter workloads, and geographic sourcing trends.

---

## 🚀 Key Features

- **Executive KPI Scorecards**: Immediate visibility into overall applicant volume (1,500+ records) and open requisitions (26 roles).
- **Role & Compensation Analysis**: Detailed tabular breakdown detailing applicant volume alongside average, median, minimum, and maximum salary expectations per position.
- **Role Distribution**: Breakdown of applicant share by position (e.g., Data Analyst, Full-Stack Engineer, Front-End Developer, Product Manager).
- **Recruiter Workload Tracking**: Allocation breakdown monitoring candidate distribution across hiring team members.
- **Geographic Talent Mapping**: Choropleth map and ranking charts displaying global talent origins across countries (Poland, Ukraine, Singapore, France, Brazil, etc.).
- **Time-Series Application Trends**: Timeline chart tracking daily candidate volume over annual hiring periods.
- **Multi-Dimensional Filtering**: Dynamic slicing by date range, country, and recruiter.
- **Modern Dark UI**: High-contrast, clean visual design optimized for executive presentation and screen readability.

---

## 📁 Project Structure

```
google-data-studio-dashboard/
├── datastudio_dashboard.pdf   # Exported report of the Looker Studio recruitment dashboard
├── LICENSE                    # MIT License
└── README.md                  # Project documentation and guide
```

---

## 🛠️ Tech Stack

- **Platform**: Google Data Studio / Google Looker Studio
- **Data Visualizations**: Geo Choropleth Map, Time-Series Area/Line Chart, Donut/Pie Charts, Metric Scorecards, Scatter Plots, Data Tables with Heatmap Indicators
- **Format**: PDF Report Export (`datastudio_dashboard.pdf`)

---

## 📖 Getting Started & Usage

### Viewing the Export
Open [datastudio_dashboard.pdf](datastudio_dashboard.pdf) with any standard PDF viewer or web browser to inspect the complete dashboard design and layout.

### Recreating or Adapting in Looker Studio
To build or customize a similar dashboard for your organization:
1. Open [Google Looker Studio](https://lookerstudio.google.com/).
2. Create a **Blank Report** and connect your data source (e.g., Google Sheets, BigQuery, PostgreSQL, or CSV).
3. Ensure your dataset includes the following dimensions and metrics:
   - **Dimensions**: `Date`, `Position`, `Country`, `Recruiter` (Owner), `User ID`
   - **Metrics**: `Applicant Counts` (Record Count), `Salary Expectations` (Min, Max, Avg, Median)
4. Add scorecard controls, tables, time-series charts, and drop-down list filters corresponding to the layout shown in `datastudio_dashboard.pdf`.
5. Apply a dark canvas theme (background: `#1E2327` / `#222B35`) with high-contrast accent palettes.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE) - see the LICENSE file for details.
