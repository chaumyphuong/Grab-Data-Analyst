# Grab-Data-Analyst

# About Company
Grab Vietnam operates in a fast-paced, highly dynamic market. As the super-app landscape evolves, our Country Analytics team plays a critical role in navigating a complex competitive environment. We leverage large-scale data to optimize market share, drive growth strategies across key metropolitan areas, and ensure our Mobility and Delivery verticals remain the top choice for our users.

# Situation
In key urban centers, the mobility and delivery sectors are experiencing heightened competition from emerging players. In response, the Vietnam Growth team launched a Super-Combo Voucher — discounting GrabFood orders and GrabBike rides together — piloted exclusively in HCMC for 6 weeks.
At the end of the pilot, the Country Head sees a significant GMV jump in HCMC and wants to immediately roll out the voucher to Hanoi to replicate the result and pressure the competitor.
Encouraged by the GMV growth and aiming to quickly counter competitors, the Country Head is prepared to immediately roll out the Super-Combo Voucher in Hanoi, expecting to replicate the same success.

# Purpose Of The Report
This report aims to analyze the business performance of Grab in Ho Chi Minh City (HCMC) before and during the implementation of the Super-Combo Voucher program. It will evaluate key metrics such as GMV, transaction volume, customer behavior, and service-type performance to assess the true impact of the program.
Based on these insights, the report will provide data-driven recommendations on whether the Country Head should proceed with rolling out the Super-Combo Voucher in Hanoi, and under what conditions to ensure effectiveness and sustainability.

## Dataset

**File:** `grab_vn_case.db` (SQLite)
**Schema reference:** [data_dictionary.md](data_dictionary.md)

| Table | Description |
|---|---|
| `transactions` | 182,000+ individual transactions across all cities and services |
| `users` | User profiles — city, payment preference, behavioural segment |
| `weather_daily` | Daily rainfall per city in mm |
| `daily_gmv_summary` | Pre-aggregated view for quick trend queries |

Figures are in **VND thousands**. Divide by 1,000 to get millions.

# Report
[Excetive Brief](Excetive_Brief)

# Visualization
1.  Jupyter Notebook: [grab_test.ipynb](grab_test.ipynb)
2.  PowerBI: [grab.pbix](grab.pbix)
<img width="2767" height="1600" alt="grab-1" src="https://github.com/user-attachments/assets/a1d1e925-8364-44c8-bcb6-758537f4a0eb" />

