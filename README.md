# Maternal Risk Intelligence Dashboard (Power BI)

An interactive Power BI dashboard exploring pregnancy risk drivers, demographics, and geography across **500 simulated patients** in **10 Nigerian states**. Built as a health data analytics portfolio project (August 2026).

> **Note:** All data is simulated, including the risk classification column. No real patient information was used, and findings describe this dataset only, not real populations.

![Risk drivers dashboard](images/dashboard-page1.png)

## Purpose
To show how routine antenatal data can be turned into a quick view of who is at highest risk, and where follow-up should be prioritised.

## Dashboard pages
1. **Dashboard (Risk Drivers, Demographics & Geography):** KPI cards, risk distribution, pregnancy outcomes, high-risk share by state, and risk broken down by hypertension, systolic BP, antenatal care (ANC) visits, anaemia, and distance to hospital.
2. **Executive Insights:** a one-page statement of the main findings, key-stat cards, and a top recommendation.

![Executive insights](images/dashboard-page2.png)

## Key metrics
| Metric | Value |
|---|---|
| Total patients | 500 |
| High-risk pregnancies | 81% |
| Anaemic (Hb < 11 g/dl) | 55% |
| Fewer than 4 ANC visits | 48% |
| Hypertensive | 39% |

## What the dashboard shows
- **Prior complications:** every patient with a prior complication in this dataset is classed as high risk (100%).
- **Blood pressure:** average systolic BP is highest in the high-risk group (136) versus moderate (125) and low (123). Among hypertensive patients, 92.9% are high risk, compared with 73.9% of non-hypertensive patients.
- **Antenatal attendance:** patients with no ANC visits are all high risk, and the high-risk share falls among those with 4 to 7 visits.
- **Anaemia:** 55% of patients are anaemic; the high-risk share is modestly higher among anaemic patients (84%) than non-anaemic (78%).
- **Geography:** the high-risk share is highest in Borno and Oyo (92% each) and lowest in FCT (71%).
- **Distance to hospital:** the high-risk share stays within a narrow range (about 79% to 85%) across distance bands, so distance does not appear to be a strong driver in this dataset.

**Top recommendation in the dashboard:** prioritise patients with a previous complication or high blood pressure for close monitoring, and follow up with the 48% of patients missing antenatal visits.

## Data
- **Source:** a simulated dataset of 500 patients and 24 variables, spanning 10 Nigerian states, built for this capstone/portfolio project.
- **Risk level:** `Pregnancy_Risk` (Low / Moderate / High) was part of the simulated data, not derived or calculated by me. This dashboard's diagnostic analysis identifies which variables most strongly associate with that existing label.
- **Filters available in the report:** pregnancy risk, residence (rural/urban), state, age band, and education level.

## Tools
Power BI Desktop, including:
- **Power Query** - data cleaning and calculated columns (anaemia flag, ANC visit bands, distance bands, age bands, custom risk sort order)
- **DAX** - custom measures powering every KPI card and chart
- **Custom report theme** - a colour-blind-accessible theme built from scratch and applied across both pages

## Files
- `maternal_risk_dashboard.pbix`: the Power BI report
- `images/`: dashboard screenshots

## Limitations
- The data is simulated, so patterns reflect how the data was generated rather than real-world epidemiology.
- `Pregnancy_Outcome` maps closely onto `Pregnancy_Risk` (e.g. every Low-risk case is a Normal Delivery), so the risk–outcome relationship reflects how the dataset was built, not a real clinical pattern.
- The dashboard is descriptive and diagnostic. It shows associations in the data and does not model or predict risk.

## Author
Rita Orobosa Aiwuyo, PharmD, B.Pharm, R.Ph.
