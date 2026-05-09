# Warehouse & Retail Sales Dashboard

A multi-page interactive **Power BI dashboard** for analyzing warehouse operations, retail transfers, supplier performance, and product movement trends across beverage distribution categories.

---

## Dashboard Overview

| Page | Title | Description |
|------|-------|-------------|
| 1 | **Sales Overview** | High-level KPIs, item type distribution, and top supplier rankings |
| 2 | **Movement Analysis** | Product-level movement, monthly trends by item type, and supplier timeline |
| 3 | **Insights & Recommendations** | Narrative summary of findings and strategic recommendations |

---

## Key Metrics

| Metric | Value |
|--------|-------|
| Total Sales | **2.15M** |
| Total Warehouse Sales | **7.80M** |
| Total Retail Transfers | **2.13M** |
| Total Movement | **12.09M** |

---

## File Structure

```
warehouse-retail-dashboard/
├── Warehouse_and_Retail_Dashboard.pbix   # Main Power BI file
├── README.md                             # Project documentation
└── screenshots/
    ├── page1_sales_overview.png
    ├── page2_movement_analysis.png
    └── page3_insights.png
```

---

## Data Categories (Item Types)

- **Beer** — highest movement and sales contribution
- **Wine** — second largest category
- **Liquor** — strong performance across retail and warehouse
- **Non-Alcohol** — minor contribution
- **Kegs, Ref, Dunnage, STR_Supplies** — lower-performing, monitored for stock optimization

---

## Top Suppliers by Total Sales

1. E & J Gallo Winery — 186K
2. Diageo North America Inc — 145K
3. Constellation Brands — 132K
4. Anheuser Busch Inc — 110K
5. Jim Beam Brands Co — 98K

---

## Top Products by Movement

- Corona Extra Loose (0.35M)
- Corona Extra 2/12 (0.27M)
- Heineken Loose NR (0.21M)
- Heineken 2/12 NR (0.17M)
- Miller Lite 30PK CAN (0.16M)

---

## Requirements

- **Tool:** Microsoft Power BI Desktop
- **Version:** Power BI Desktop (latest recommended)
- **Data Source:** Internal warehouse and retail transaction dataset (2017–2020)

---

## Getting Started

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/warehouse-retail-dashboard.git
   ```
2. Open `Warehouse_and_Retail_Dashboard.pbix` in Power BI Desktop.
3. Refresh the data source if connected to a live database.
4. Use the **Item Type** filter panel (right side) to slice by category.
5. Navigate between **Page 1**, **Page 2**, and **Page 3** using the bottom tabs.

---

## Key Insights

- Beer dominates both warehouse and retail movement, making it the highest-priority category for inventory planning.
- Warehouse sales (7.80M) significantly outpace retail transfers (2.13M), indicating a wholesale-heavy distribution model.
- E & J Gallo Winery and Diageo North America are the anchor suppliers — relationship stability with these two is critical.
- Categories like Kegs, Ref, and Dunnage show low movement and may benefit from stock reduction to free up warehouse capacity.
- Movement declined from mid-2017 peaks (~593K) toward 2019–2020 (~390K), warranting investigation into demand drivers.

---

## Recommendations

- Prioritize inventory for **Beer, Wine, and Liquor** to prevent stockouts.
- Strengthen supplier contracts with **E & J Gallo Winery** and **Diageo North America**.
- Apply **demand forecasting models** to improve warehouse-to-retail allocation efficiency.
- Monitor and reduce holding costs for low-performing SKUs (Kegs, Dunnage, Ref).
- Track monthly and yearly sales trends to support seasonal planning.

---

## Pages

### Page 1 — Sales Overview

### Page 2 — Movement Analysis

### Page 3 — Insights & Recommendations

---

## License

This project is licensed under the [MIT License](LICENSE).

---

## Author

**Your Name** FATIMA LIAQAT
- LinkedIn: https://www.linkedin.com/in/fatima-liaqat-dataanalyst

---

> *Dashboard built with Microsoft Power BI | Data covers beverage distribution from 2017–2020*
