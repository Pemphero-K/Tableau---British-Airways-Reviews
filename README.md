# British Airways Reviews — Tableau Dashboard

An interactive Tableau dashboard analysing **1,351 passenger reviews** of British Airways, covering overall ratings, cabin staff service, entertainment, food & beverages, ground service, seat comfort, and value for money.

> **[View the live dashboard on Tableau Public](https://public.tableau.com/app/profile/pemphero.kenani/viz/BritishAirwaysReviews_17778305467400/Dashboard1)**

---

## Dashboard Preview

<img width="1563" height="851" alt="image" src="https://github.com/user-attachments/assets/f764f06e-f022-42d7-8bef-32c17eea5fff" />




---

## Dataset

**File:** `ba_reviews.csv`  
**Rows:** 1,351 reviews  
**Date range:** March 2016 – October 2023  
**Source:** Scraped British Airways passenger reviews

---

## Key Metrics (All-time averages)

| Metric | Average Score |
|---|---|
| Overall Rating | 4.2 / 10 |
| Cabin Staff Service | 3.3 / 5 |
| Entertainment | 1.4 / 5 |
| Food & Beverages | 2.4 / 5 |
| Ground Service | 3.0 / 5 |
| Seat Comfort | 2.9 / 5 |
| Value for Money | 2.8 / 5 |

---

## Dashboard Features

- **KPI header bar** — snapshot of all 7 average scores at a glance
- **Average Value by Month** — time-series line chart from 2016 to 2024, revealing a sharp post-COVID dip in 2020 and a continued decline through 2023
- **Average Value by Country** — choropleth world map showing how ratings differ by reviewer geography
- **Average Value by Aircraft** — dual horizontal bar chart comparing metric scores and review counts across aircraft types (Boeing 747, 777, 787, A319, A320, A321, A380, and more)

### Interactive Filters

- **Metric selector** — switch between Overall Rating, Cabin Staff Service, Entertainment, Food, Ground Service, Seat Comfort, or Value for Money
- **Month of Date** slider — narrow the time range between March 2016 and October 2023
- **Traveller Type** — All / Business / Couple Leisure / Family Leisure / Solo Leisure
- **Seat Type** — All / Business Class / Economy Class / First Class / Premium Economy
- **Aircraft (group)** dropdown
- **Continent** dropdown

---

## How to Explore

1. Click the **[live dashboard link](https://public.tableau.com/app/profile/pemphero.kenani/viz/BritishAirwaysReviews_17778305467400/Dashboard1)**
2. Use the **metric radio buttons** on the left to switch between service dimensions
3. Adjust the **date slider** to explore specific time periods
4. Filter by **traveller type**, **seat type**, **aircraft**, or **continent** to drill into segments

To explore the raw data locally, download `ba_reviews.csv` from this repository.

---

## Insights

- **Entertainment scores lowest** at 1.4/5 — a consistent pain point across all traveller types
- **Cabin staff scores highest** among the sub-metrics at 3.3/5
- **Post-COVID decline** — average scores dropped sharply in 2020 and never fully recovered
- **Boeing 777-200** edges out other aircraft on value (3.1), while the **Boeing 747** scores lowest (2.3)
- **A320** has the second highest review count (263) but sits near the bottom for value
