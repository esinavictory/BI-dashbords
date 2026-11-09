# BI-dashbords
# Hotel Performance Analysis in Power BI

Business intelligence project: an analytical dashboard for a hotel chain, built in Power BI on CRM data, with management recommendations for improving profitability.


## Overview

The goal of the project is to evaluate the operational and financial performance of a hotel chain and to identify where profitability can be improved. The report is built on CRM data and lets a manager explore results by season, room type, and client country.

**Questions the dashboard answers**

- How do bookings and revenue change across seasons? 
- Which room types and services contribute the most to revenue?
- Which client countries generate the most bookings and the highest revenue?

## Data

The data comes from the hotel chain's CRM system and covers four areas:

| Table | Content |
|---|---|
| Bookings | Reservation dates, length of stay, price, status |
| Clients | Client profile, country of origin |
| Rooms | Room type, capacity, rate |
| Services | Additional services purchased by guests |


## Data model

![Data model](data-model.png)

## Dashboard pages

### Page 1: Overview
![Overview](images/dashboard-overview.png)

### Page 2: [название]
![Page 2](images/dashboard-page-2.png)

### Page 3: [название]
![Page 3](images/dashboard-page-3.png)

### Page 4: [название]
![Page 4](images/dashboard-page-4.png)

## Report contents

The report uses line charts, tables, matrices, pie charts and bar charts. All pages can be filtered by:

- **Season**
- **Room type**
- **Client country**

| Page | What it shows |
|---|---|
| 1 | Booking Report |
| 2 | Report by rooms |
| 3 | Report by clients |
| 4 | Analysis of seasonality and tariff policy |



## How to open

1. Install [Power BI Desktop]) (Windows).
2. Download `hotel-analysis.pbix` from this repository.
3. Open the file. If Power BI asks for the data source path, point it to the `data/` folder.

## Tools

Power BI Desktop, Power Query, DAX.
