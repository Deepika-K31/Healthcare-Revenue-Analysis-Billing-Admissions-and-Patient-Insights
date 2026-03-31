# Healthcare Revenue Analysis — Billing, Admissions and Patient Insights

## Objective
To analyse 54,966 hospital patient records across billing, admissions and patient demographics — using Python and SQL — to identify revenue patterns, operational inefficiencies and patient behaviour insights that support data-driven hospital management decisions.

## Problem Statement
Hospital management needs data-driven insights to understand revenue distribution across insurance providers and medical conditions, identify which patient demographics drive the most admissions, and find operational inefficiencies in length of stay and admission patterns — all to improve resource allocation and financial planning.

## Key Findings
### Revenue Findings
- All 5 insurance providers contribute nearly equal revenue — well-balanced payer mix
- Average billing is approximately $25,000 across all 6 medical conditions — unusually uniform
- Billing uniformity across conditions suggests flat-rate pricing — worth investigating whether it reflects actual treatment complexity

### Patient Findings
- Age group 36–65 accounts for the largest share of admissions
- Obesity and Hypertension peak in the 51+ age group — aligns with real-world health patterns
- Gender split is nearly 50/50 across all conditions — expected in a balanced synthetic dataset

### Operational Findings
- Emergency and Urgent admissions have longer average stays than Elective — as expected clinically
- Monthly admissions are stable with minor seasonal fluctuations
- Emergency stays drive highest resource consumption per patient

## Business Recommendations

**1. Diversified Payer Mix — Negotiate Medicare Rates**
All 5 insurers contribute equally — healthy revenue diversity. However, Medicare (elderly patients with longer stays) should be subject to better reimbursement rate negotiations to protect margins.

**2. Invest in Chronic Disease Management for 36–65 Age Group**
Core patient base is middle-aged to senior. Preventive care programmes for Hypertension, Diabetes and Obesity in this group can reduce repeat emergency admissions and improve outcomes.

**3. Investigate Flat-Rate Billing Anomaly**
Uniform billing (~$25,000) across all conditions is clinically unrealistic. Cancer and chronic conditions should cost significantly more. Recommend a billing audit to ensure pricing reflects actual treatment complexity.

**4. Reduce Emergency Admission Length of Stay**
Emergency cases have longest average stays — highest cost and bed occupancy. Implement better triage protocols and discharge planning from Day 1 to free up capacity.

**5. Use Seasonal Admission Data for Staff Planning**
Monthly admission trends show predictable patterns. Use historical data to plan staffing and resource allocation in advance for high-admission months.

## Visualizations
- Revenue by insurance provider bar chart
- Average billing by medical condition horizontal bar chart
- Patient count by age group and condition grouped bar chart
- Gender split by medical condition stacked bar chart
- Average length of stay by admission type bar chart
- Monthly admission trends line chart
- Combined healthcare analytics dashboard

## Project Limitations
- Dataset is synthetically generated — real hospital data would show more billing variation by condition
- No readmission rate data — a key hospital performance metric not available
- Doctor and Hospital columns not analysed — potential for further performance benchmarking
- Gender split is too uniform (50/50) — real data would show condition-specific gender patterns

## Skills Demonstrated
`Python` `Pandas` `NumPy` `Matplotlib` `Seaborn` `SQL` `pandasql` `Feature Engineering` `Data Cleaning` `Healthcare Analytics` `Business Recommendations` `EDA`

## Dataset Source
Healthcare Dataset — Kaggle

Synthetic dataset modelled on real-world hospital billing and patient records.

Patient privacy maintained — no real patient data used.



