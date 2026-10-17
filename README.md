# Maternal Risk Intelligence Dashboard (Power BI)

An interactive Power BI dashboard exploring pregnancy risk drivers, demographics, and geography across **500 simulated patients** in **10 Nigerian states**. Built as a health data analytics portfolio project (August 2026).

> **Note:** all data is simulated. No real patient information was used, and the findings describe this dataset only, not real populations.

![Risk drivers dashboard](images/dashboard-page1.png)

## Purpose
To show how routine antenatal data can be turned into a quick view of who is at highest risk, and where follow-up should be prioritised.

## Dashboard pages
1. **Risk Drivers, Demographics & Geography:** KPI cards, risk distribution, pregnancy outcomes, high-risk share by state, and risk broken down by hypertension, systolic BP, antenatal care (ANC) visits, anaemia, and distance to hospital.
2. **Executive Summary:** a one-page statement of the main findings and a top recommendation.

![Executive summary](images/dashboard-page2.png)

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
- **Geography:** the high-risk share is highest in Borno and Oyo (92% each) and lowest in FCT (71%).
- **Distance to hospital:** the high-risk share stays within a narrow range (about 79% to 85%) across distance bands, so distance does not appear to be a strong driver in this dataset.

**Top recommendation in the dashboard:** prioritise patients with a previous complication or high blood pressure for close monitoring, and follow up the 48% who are missing antenatal visits.

## Data
- **Source:** simulated dataset of 500 patients and 24 variables.
- **Filters available in the report:** pregnancy risk, residence (rural/urban), state, age band, and education level.

## Tools
Power BI Desktop

## Files
- `maternal_risk_dashboard.pbix`: the Power BI report
- `images/`: dashboard screenshots

## Limitations
- The data is simulated, so patterns reflect how the data was generated rather than real-world epidemiology.
- The dashboard is descriptive. It shows associations and does not model or predict risk.

## Author
Rita Orobosa Aiwuyo, PharmD, B.Pharm, R.Ph. | [LinkedIn](https://www.linkedin.com/in/rita-aiwuyo) | [Portfolio](https://rita-portfolio.onrender.com/)
