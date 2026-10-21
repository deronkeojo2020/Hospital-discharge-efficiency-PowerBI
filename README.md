# Hospital Discharge Efficiency and Patient Flow Optimization

## Project Overview

This Power BI portfolio project analyzes hospital discharge efficiency, patient flow, length of stay, discharge delays, and inpatient bed utilization using synthetic healthcare data.

The project demonstrates data preparation, data modelling, DAX calculations, interactive dashboard development, KPI validation, and translating analytical findings into operational recommendations.

**Data disclaimer:** This project uses synthetic data for portfolio and learning purposes. It does not contain actual Mass General Brigham patient records or verified hospital performance data.

## Business Objectives

- Evaluate admission and discharge volumes.
- Measure average length of stay and prolonged stays.
- Assess discharge turnaround times and delayed discharge rates.
- Compare discharge performance across departments, patient groups, and destinations.
- Examine inpatient bed utilization over time.
- Identify areas for further operational investigation.

## Tools and Technologies

- Microsoft Power BI
- Power Query
- DAX
- Data cleaning and transformation
- Relational data modelling
- KPI validation and exploratory analysis
- Interactive dashboards and slicers

## Data Sources

The project uses five synthetic datasets:

- Patients
- Admissions
- Departments
- Discharges
- Bed Capacity

Data preparation included checking identifiers, duplicate records, missing values, data types, and relationships; standardizing discharge destination categories; and creating fields for length of stay, discharge turnaround time, and patient-flow analysis.

## Dashboard Pages

1. **KPI Analysis** — Summary indicators and interactive filters.
2. **Exploratory Analysis** — Admission and discharge trends, length of stay, prolonged stays, departmental comparisons, and bed utilization.
3. **Discharge Delay Analysis** — Delay rates by department, recorded delay reason, discharge destination, patient group, and time period.
4. **Findings Summary** — Major findings, operational considerations, and recommendations.

## Key Findings

Results calculated from the synthetic dataset:

| Metric | Result |
|---|---:|
| Admission records | 30,000 |
| Discharge records | 30,000 |
| Records with a recorded discharge timestamp | 28,768 |
| Records without a recorded discharge timestamp | 1,232 |
| Average length of stay | 5.46 days |
| Prolonged stays | 4,645 |
| Prolonged-stay rate among completed discharges | 16.15% |
| Delayed discharges | 18,469 |
| Delayed discharge rate among eligible turnaround records | 64.20% |
| Bed utilization rate | 81.58% |

Rehabilitation had an observed delayed discharge rate of 89.06%, compared with 44.52% for Emergency Medicine.

These results describe the synthetic dataset and do not establish causes of delays or represent verified performance at a real hospital.

## KPI Definitions

- **Length of stay:** Time between admission and recorded discharge.
- **Delayed discharge:** A completed discharge occurring more than four hours after recorded discharge readiness.
- **Prolonged stay:** A completed stay exceeding seven days.
- **Bed utilization:** Total occupied bed-days divided by total available bed-days across the selected department-date records.

Records with missing discharge timestamps are reported separately and are not assumed to represent confirmed active inpatient encounters.

## Recommendations

- Investigate departmental differences in discharge turnaround times.
- Review recorded transport and post-acute placement delays.
- Monitor bed utilization alongside discharge performance.
- Investigate prolonged stays and missing discharge timestamps.
- Review trends using eligible-record counts and appropriate sample-size context.

## Limitations

The dataset is synthetic and cannot establish real-world hospital performance. Recorded delay reasons are descriptive rather than proof of causation. Missing timestamps and KPI definitions affect interpretation.

## Skills Demonstrated

Power BI, Power Query, DAX, data cleaning, data validation, data modelling, KPI development, healthcare operations analytics, dashboard design, and data-driven communication.
