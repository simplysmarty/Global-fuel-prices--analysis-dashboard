# ⛽ Global Fuel Analysis 2020–2026
### A 3-Page Interactive Power BI Dashboard

> **What really drives the price you pay at the pump?** This project analyses 27,468 weekly fuel price records across 84 countries and 7 regions from January 2020 to April 2026 — revealing that government subsidy and tax policy, not global crude oil prices, are the dominant forces shaping what citizens pay for energy worldwide.

<br>

📍 **Analyst:** Fasanya Segun &nbsp;|&nbsp; 🔗 [LinkedIn](https://www.linkedin.com/in/segun-fasanya-879a943b1) &nbsp;|&nbsp; 💻 [Portfolio](https://github.com/simplysmarty/data-analysis-portfolio) &nbsp;|&nbsp; 📊 Power BI · Python · Excel · SQL

---

## 📌 Table of Contents

- [Problem Statement](#-problem-statement)
- [Insight Questions](#-insight-questions)
- [Dashboard Preview](#-dashboard-preview)
- [Key Findings & Insights](#-key-findings--insights)
- [Recommendations](#-recommendations)
- [Dashboard Page](#-dashboard-page)
- [Data Overview](#-data-overview)
- [Tools & Skills](#-tools--skills)
- [Data Source](#-data-source)
- [Conclusion](#-conclusion)

---

## 🎯 Problem Statement

Global fuel prices remain a critical economic force shaping outcomes for governments, businesses, and households worldwide. Between 2020 and 2026, the global energy market experienced significant volatility driven by pandemic-induced demand shocks, post-pandemic recovery surges, geopolitical disruptions, and shifts in subsidy and taxation policies. These factors have led to substantial disparities in fuel prices across 84 countries.

This analysis explores the global fuel pricing landscape to identify regions and countries bearing the highest fuel cost burden, while examining the extent to which government policies — particularly taxes and subsidies — influence consumer prices beyond underlying crude oil market trends. It also evaluates how fuel prices have evolved over a six-year period marked by unprecedented global disruption.

**The objective is to equip decision-makers with actionable insights into the structural drivers of fuel price variations and to highlight the economies most vulnerable to rising energy costs.**

---

## ❓ Insight Questions

These are the six analytical questions this dashboard is built to answer:

| # | Question | 
|---|----------|
| 1 | Which regions and countries carry the highest and lowest fuel prices — and what do they have in common? 
| 2 | Does a higher crude oil price actually translate to higher pump prices for consumers? 
| 3 | How does government subsidy policy affect what citizens pay across different income levels?
| 4 | Is tax rate or subsidy level the stronger driver of fuel price variation globally? 
| 5 | How have global petrol, diesel and LPG prices evolved from 2020 to 2026 — and did prices ever return to pre-COVID levels? 
| 6 | Why do some low-income countries pay more for fuel than high-income countries — and what does this reveal about policy choices? 

---

## 📊 Dashboard Preview

### Page 1 — Dashboard
*KPI cards · Top 5 most expensive vs cheapest countries · Regional fuel prices · Subsidy level vs fuel prices · Tax rate scatter · Global trend*

![Page 1 — Dashboard](screenshots/page1_dashboard.png)

---

## 🔍 Key Findings & Insights

**1. Europe is the most expensive region for fuel at $3.70/L**
Europe averages $3.70/litre for petrol, driven by tax rates averaging 34.6%. The Middle East is the cheapest at $1.23/litre, where government oil revenues fund heavy subsidies that shield citizens from global price volatility. The same crude oil, the same global market — but a $2.47 gap per litre driven entirely by policy choices on opposite sides of the spectrum.

**2. Government subsidy policy creates a 23× price difference**
Countries with Very High subsidies pay as little as $0.11–$0.15/litre while countries with Low subsidies pay $3.45/litre on average — a 23× gap. Brent crude oil correlates with pump prices at only r = 0.26, while tax rate correlates at r = 0.52. This confirms that what citizens pay at the pump is determined more by government decisions than by the global oil market.

**3. Tax rate is the strongest single driver of fuel prices**
Countries with higher tax rates consistently pay more at the pump regardless of global oil market movements. Rwanda's 63.7% tax rate contributes directly to its $3.06/L petrol price. The correlation between tax rate and pump price (r = 0.52) is twice as strong as the Brent crude correlation (r = 0.26).

**4. Hong Kong is the world's most expensive country for petrol at $5.54/L**
A High income, Low subsidy nation with a 37% tax rate. Venezuela is the cheapest at just $0.02/litre due to extreme government subsidies. The $5.52 gap between these two countries represents the full picture of how policy shapes what citizens pay for energy — regardless of their country's wealth.

**5. Global fuel prices collapsed in 2020 and have never returned to pre-COVID levels**
Prices collapsed during COVID when Brent Crude fell to $47.97/barrel. They surged 54.1% in 2021 as demand recovered, spiked further in 2022 due to the Russia-Ukraine war (Brent peaked at $130.00/barrel), and have continued rising to $2.65/litre in 2026. The world has never returned to pre-COVID price levels — the 2023 dip to $2.23/L was temporary.

---

## 💡 Recommendations

Based on the findings, the following recommendations are directed at the three key stakeholder groups this analysis serves:

### For Policymakers in Low-Income, Low-Subsidy Countries

> *Eight African countries — Rwanda ($3.06/L), Zimbabwe ($3.15/L), Zambia ($3.05/L), Uganda ($2.84/L), Mozambique ($2.99/L), Kenya ($2.74/L), Tanzania ($2.60/L) and Ghana ($2.49/L) — are Low income nations paying above the global average for fuel with no subsidy protection.*

**Recommendation 1 — Introduce targeted fuel subsidies for the most vulnerable households**
Low-income countries carrying some of the highest pump prices represent a compounding economic burden — citizens with the lowest incomes are spending the highest proportion of earnings on fuel. Governments in this category should explore targeted, means-tested fuel support mechanisms that protect the poorest without creating the fiscal risks associated with universal subsidy regimes like Venezuela or Nigeria.

**Recommendation 2 — Review tax structures on essential fuels, particularly LPG**
Rwanda's 63.7% tax rate and Kenya's 45.4% rate are among the highest in Africa — applied to a population that cannot absorb price increases the way European consumers can. Differentiating tax rates between vehicle fuel (higher tax acceptable) and LPG used for household cooking (lower tax) would protect household energy affordability without abandoning fiscal revenue goals.

---

### For High-Subsidy, Oil-Producing Governments

> *Venezuela, Libya, Iran, Algeria, Egypt, Iraq, Kuwait, Nigeria and Saudi Arabia all maintain Very High subsidies — keeping domestic pump prices between $0.04 and $0.31/L. In every one of these countries, Brent crude price movements had virtually zero effect on domestic pump prices (price std dev < $0.05/L over 6 years).*

**Recommendation 3 — Design phased, inflation-protected subsidy reform pathways**
Universal fuel subsidies are among the most fiscally costly and economically distortive policies a government can maintain. Nigeria's 2023 subsidy removal — which resulted in pump prices jumping from ₦185/L to over ₦600/L overnight — demonstrates the social risk of abrupt removal. A phased approach tied to inflation indices and social safety net expansion would reduce fiscal strain while managing the distributional impact on citizens.

**Recommendation 4 — Redirect subsidy savings toward productive infrastructure**
The fiscal cost of maintaining $0.26/L petrol in Nigeria while the market rate is above $2.00/L represents billions in annual government expenditure. Redirecting even a portion of these savings toward transport infrastructure, healthcare or education would generate longer-term economic returns that universal fuel subsidies cannot deliver.

---

### For Energy Analysts and International Organisations

**Recommendation 5 — Use subsidy level as the primary segmentation variable in fuel affordability analysis**
The data confirms that subsidy level — not region, income level or Brent crude price — is the strongest predictor of what consumers pay. Any analytical framework or cross-country comparison of fuel affordability that does not control for subsidy regime will produce misleading conclusions. Subsidy classification should be the first filter applied in any policy comparison.

**Recommendation 6 — Monitor the 2023–2026 price floor as the new global baseline**
The 2023 dip to $2.23/L was widely interpreted as a return toward pre-COVID pricing. This analysis shows it was a temporary correction — prices resumed climbing to $2.65/L by 2026. International energy organisations and national budget planners should adopt the $2.40–$2.70/L range as the structural baseline for global petrol pricing in forecasting models, rather than reverting to pre-2020 assumptions.

---

## 📋 Dashboard Page

### Dashboard

**Slicers:** Income Level · Region

| Visual | Key Numbers | Insight |
|--------|------------|---------|
| KPI — Avg Petrol Price | **$2.28/L** | Global average across all years and countries |
| KPI — Avg Diesel Price | **$2.13/L** | Diesel consistently cheaper than petrol globally |
| KPI — Avg LPG Price | **$1.71/L** | LPG the most affordable fuel type in every region |
| KPI — Avg Tax Rate | **26.77%** | Over a quarter of pump price is tax on average |
| KPI — Avg Crude Price | **$106.69** | Brent crude USD/barrel average across 6 years |
| Grouped bar — Most Expensive | HK $5.10 · IE $4.55 · NO $4.43 | All Low subsidy, High tax nations |
| Grouped bar — Cheapest | IQ $0.14 · DZ $0.12 · LY $0.05 | All Very High subsidy, oil-producing states |
| Table — Regional Prices | Europe $3.70 · Middle East $1.23 | $2.47 regional gap driven entirely by policy |
| Bar — Subsidy vs Price | Low $3.45 · VH $0.15 | 23× gap — the single most powerful chart |
| Scatter — Tax vs Price | Positive correlation r = 0.52 | Tax is twice as predictive as crude oil price |
| Area — Price Trend | $1.48 (2020) → $2.65 (2026) | 79% rise — no return to pre-COVID levels |

---

## 📁 Data Overview

| Property | Detail |
|----------|--------|
| **Dataset** | Global Fuel Prices 2020–2026 |
| **Challenge** | April Data Analysis Challenge |
| **Total records** | 27,468 weekly observations |
| **Countries** | 84 countries |
| **Regions** | 7 regions |
| **Date range** | January 2020 – April 2026 |
| **Missing values** | None — clean dataset |
| **Columns** | date · country · region · income_level · subsidy_level · petrol_usd_liter · diesel_usd_liter · lpg_usd_liter · brent_crude_usd · tax_percentage |

### Regional fuel prices (all years average)

| Region | Avg Diesel | Avg LPG | Avg Petrol |
|--------|-----------|---------|-----------|
| Europe | $3.52 | $2.78 | **$3.70** |
| Oceania | $3.47 | $2.74 | **$3.66** |
| Asia | $1.98 | $1.61 | **$2.14** |
| North America | $1.89 | $1.55 | **$2.06** |
| Africa | $1.43 | $1.16 | **$1.55** |
| South America | $1.29 | $1.07 | **$1.43** |
| Middle East | $1.14 | $0.92 | **$1.23** |
| **Global Total** | **$2.13** | **$1.71** | **$2.28** |

### Fuel price by subsidy level

| Subsidy Level | Avg Petrol | Example Countries |
|---------------|-----------|-------------------|
| Low | **$3.45/L** | Europe · Hong Kong · Kenya · Rwanda |
| Medium | **$1.66/L** | Morocco · Ghana · India |
| High | **$0.71/L** | Angola · Sudan · Algeria |
| Very High | **$0.15/L** | Venezuela · Libya · Iran · Nigeria |

### Price trend 2020–2026

| Year | Avg Petrol | Avg LPG | Avg Diesel | Key event |
|------|-----------|---------|-----------|-----------|
| 2020 | $1.48 | $1.11 | $1.39 | COVID demand collapse · Brent avg $69.44 |
| 2021 | $2.28 | $1.71 | $2.13 | Post-pandemic recovery surge (+54%) |
| 2022 | $2.51 | $1.88 | $2.34 | Russia-Ukraine war · Brent peaked $130 |
| 2023 | $2.23 | $1.68 | $2.09 | Brief correction — not a reversal |
| 2024 | $2.55 | $1.91 | $2.38 | New floor established |
| 2025 | $2.54 | $1.90 | $2.37 | Prices hold above $2.50 |
| 2026 | **$2.65** | **$1.99** | **$2.47** | New six-year high |

---

## 🛠 Tools & Skills

| Tool / Skill | How I used it |
|---|---|
| **Power BI Desktop** | 3-page dashboard · KPI cards · scatter plots · area charts · tables · slicers · navigation buttons |
| **DAX** | Custom measures for filtered averages by subsidy level, region and income category |
| **Python (pandas · numpy)** | Exploratory data analysis · date parsing · Pearson correlation · segmentation across 27,468 rows |
| **Excel** | Initial data inspection and date origin conversion |
| **Data Storytelling** | Insight-first chart titles · problem statement page · numbered findings page — all written for decision-maker audiences |
| **Statistical Analysis** | Pearson correlation: Brent crude r = 0.26 · Tax rate r = 0.52 vs pump prices |

---

## 📄 Data Source

| Property | Detail |
|----------|--------|
| **Dataset** | Global Fuel Prices 2020–2026 · April Data Analysis Challenge |
| **Records** | 27,468 weekly observations · 84 countries · 10 features |
| **Missing values** | None |
| **Price unit** | USD per litre — petrol, diesel and LPG |
| **Crude oil** | Brent crude USD per barrel |

---

## 🏆 Conclusion

This analysis of 27,468 weekly fuel price observations across 84 countries delivers one overarching conclusion:

> **What you pay for fuel is primarily a reflection of what your government decides — not what the global oil market does.**

Brent crude oil correlates with pump prices at only r = 0.26 — explaining less than 7% of price variation. Tax rate explains a further 27%, and subsidy policy alone creates a 23× price gap between the most and least subsidised nations. The 2020–2026 period adds a second, equally important conclusion: the post-COVID price surge is structural and permanent. Global petrol prices rose 79% from $1.48/L to $2.65/L and have not returned to pre-pandemic levels despite a brief 2023 dip.

The most urgent policy implication is for low-income nations — particularly in sub-Saharan Africa — where citizens with the least purchasing power are paying the highest proportion of their income on fuel with no subsidy protection. Rwanda ($3.06/L, 63.7% tax), Zimbabwe ($3.15/L) and Zambia ($3.05/L) represent a compounding vulnerability that international energy policy has largely failed to address.

**Fuel price reform is a governance challenge first, and a market challenge second.**

---

## 👤 About the Analyst

**Fasanya Segun** — Data Analyst, Lagos Nigeria

Building a public portfolio of real-world data analytics projects as part of a **120 Days of Building in Public** challenge — documented openly on LinkedIn.

- 🔗 [LinkedIn](https://www.linkedin.com/in/segun-fasanya-879a943b1)
- 💻 [GitHub Portfolio](https://github.com/simplysmarty/data-analysis-portfolio)

*Open to remote roles — Data Analyst · BI Analyst · Digital Content & Data Visualisation*

---

*Built by Fasanya Segun · April 2026 · Power BI · Python · Excel · Data Storytelling*
