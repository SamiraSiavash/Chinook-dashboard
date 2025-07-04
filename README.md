![Power BI](https://img.shields.io/badge/built%20with-Power%20BI-yellow?style=flat&logo=powerbi)

# 🎵 Chinook Analytics Dashboard – Power BI

Interactive Power BI report built on the classic **Chinook** sample database.\
The dashboard explores sales, customers, albums, artists, tracks, and genres across multiple pages.

> **Repository structure**
>
> ```
> Chinook-dashboard/
> ├── Chinook.pbix              # full Power BI report
> ├── Data/
> │   ├── Chinook.bak          # SQL Server backup (main data source)
> │   └── Chinook.xlsx         # optional Excel export for quick demo
> ├── Images/                   # dashboard screenshots
> │   ├── 1.Overview.png
> │   ├── 2.Sales by Country.png
> │   ├── 3.Customers.png
> │   ├── 4.Genres.png
> │   ├── 5.Albums.png
> │   └── 6.Tracks.png
> └── README.md
> ```

---

## 📊 Dashboard pages & key insights

| Page                 | Highlights                                                                |
| -------------------- | ------------------------------------------------------------------------- |
| **Overview**         | ‑ Total revenue & orders‑ KPI cards for customers, tracks, invoices       |
| **Sales**            | ‑ Revenue & invoices by billing country‑ Trend line of monthly sales      |
| **Customers**        | ‑ Top spenders‑ Customer count by country & city‑ Avg. spend per customer |
| **Sales Experts**    | ‑ Top sales agents ranked by revenue‑ Sales & invoice count per agent‑ Customer location breakdown‑ Revenue trends by agent |
| **Genres & Artists** | ‑ Revenue by genre‑ Top-earning artists and albums                        |

---

## 📅 Data sources

| Source                         | Description                                                                          | Location            |
| ------------------------------ | ------------------------------------------------------------------------------------ | ------------------- |
| **SQL Server backup** | Primary data source used in the PBIX file; restore on any SQL Server 2019+ instance. | `Data/Chinook.bak`  |
| **Excel export**      | Lightweight snapshot of core tables for quick exploration without SQL Server.        | `Data/Chinook.xlsx` |

---

## 🛠 Tools & techniques

- **Power BI Desktop**
- **SQL Server** (restore the `.bak` to re-use live database)
- **Power Query (M)** for extraction & transformation
- **Star-schema modelling** of Chinook tables

---

## 🚀 How to run locally

1. **With SQL Server**
   1. Restore `Data/Chinook.bak` on a local SQL Server 2019+ instance.
   2. Update the **Data Source Settings** in `Chinook.pbix` to point to your server.
   3. Refresh—enjoy the full relational model.
2. **Quick demo (no SQL Server)**
   1. Open `Chinook.pbix`, ignore missing SQL source.
   2. Switch the queries to `Data/Chinook.xlsx` (already included) and refresh.

---

## 📦 Downloads

The full `.pbix` file is included in the repo and does not require a separate download.

---

## 👩‍💻 Author

**Samira Siavash**\
[LinkedIn](https://linkedin.com/in/samira-siavash) • [GitHub](https://github.com/SamiraSiavash)

---

## 📜 License

Distributed under the **MIT License**. See the `LICENSE` file for details.

