# Exploring Trends in the Automotive Industry — Tableau

**Dataset:** 8,148 used car listings · India · 1983–2023  
**Tools:** Tableau · CSV · Calculated Fields · Data Modeling

![Dashboard Preview](./dashboard_preview.png)

🔗 **[Live Dashboard — Tableau Public](#)** *(add your link here)*

---

## About the Project

Used car pricing in India is all over the place — fuel type, transmission, who's selling, how many km on the clock. This dashboard breaks down 8,148 listings to find what actually drives resale value and where the market has moved over the past 40 years.

---

## Dashboard Visuals

| Chart | Type | What it shows |
|-------|------|---------------|
| Selling Price by Fuel Type | Bar chart | Avg price per fuel — Electric ₹26.5L, Diesel ₹7.9L, Petrol ₹4.6L, CNG ₹3L, LPG ₹2L |
| Selling Price by Year & Seller Type | Area chart | Total market value 1983–2023, split by Dealer / Individual / Trustmark — peaks in 2019 |
| Avg Km Driven by Fuel & Transmission | Grouped bar | LPG highest avg km (89,174) · Diesel (83,595) · Petrol lowest (52,682) |
| Automatic vs Manual — Count | Pie chart | Manual: 7,091 (87%) · Automatic: 1,057 (13%) |
| Automatic vs Manual — Avg Price | Bar chart | Automatic avg ₹18.7L vs Manual avg ₹4.5L |

**Filters:** Seller Type · Fuel · Transmission · Seats

---

## Key Numbers

| Metric | Value |
|--------|-------|
| Total listings | 8,148 |
| Year range | 1983 – 2023 |
| Overall avg selling price | ₹6.4L |
| Most listed fuel type | Diesel (4,407 listings) |
| Peak market year | 2019 |
| First owner listings | 5,306 (65%) |
| 5-seater share | 6,274 (77%) |

---

## What the Data Says

- Automatic cars average **₹18.7L vs ₹4.5L for manual** — a 4x gap. Transmission is the single strongest predictor of price in this dataset.
- Electric vehicles have just **1 listing** at ₹26.5L — too small a sample to draw conclusions, but reflects the early-stage EV market in India at the time of this dataset.
- **2019 was the peak year** for total market value. Listings drop sharply after 2020, likely reflecting COVID's impact on used car transactions.
- **Individual sellers dominate** — 6,780 out of 8,148 listings (83%). Dealer and Trustmark combined account for just 17%.
- Diesel cars are the most listed fuel type (4,407) and log the second highest avg km driven (83,595 km) — pointing toward high-usage buyers.

---

## Files

| File | Description |
|------|-------------|
| `Exploring Trends in the Automotive Industry.twbx` | Tableau packaged workbook |
| `Exploring_Trends_in_the_Automotive_Industry.csv` | Raw dataset (8,148 rows) |

---

*Skills: Tableau · Dashboard Development · Data Modeling · Calculated Fields · Exploratory Data Analysis · Business Analytics · KPI Reporting*
