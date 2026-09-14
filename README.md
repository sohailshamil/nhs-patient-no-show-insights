# nhs-patient-no-show-insights
An end-to-end data analytics project evaluating NHS patient DNA (Did Not Attend) patterns, featuring raw data cleaning pipelines, exploratory data analysis in Excel, an interactive Tableau executive dashboard, and strategic policy recommendations to mitigate missed appointments.

---

## 📋 Project Overview & Objectives
Outpatient non-attendance creates severe clinical backlogs, inefficient resource utilization, and extended waiting lists across the National Health Service (NHS). The primary objectives of this project are:
* **Quantify Non-Attendance:** Establish baseline metrics for overall DNA rates against national benchmarks.
* **Identify High-Risk Segments:** Isolate demographic, temporal, and clinical factors contributing to missed appointments.
* **Evaluate Interventions:** Measure the quantifiable impact of SMS/phone appointment reminders on patient attendance.

---

## 📂 Repository Structure
To maintain a strict audit trail and separate source data from transformed assets, the project is organized into the following directory structure:
```text
nhs-patient-no-show-insights/
│
├── data/
│   ├── raw/
│   │   └── nhs_outpatient_appointments.csv       # Original, unedited source dataset
│   └── processed/
│       └── nhs_outpatient_appointments_cleaned.xlsx # Fully cleaned, transformed, and analyzed workbook
│
├── LICENSE
└── README.md
