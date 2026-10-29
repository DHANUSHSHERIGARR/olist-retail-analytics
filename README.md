# Olist E-commerce Analytics: Delivery Performance, Customer Satisfaction & Revenue

> End-to-end data analytics project using **Python, SQL (SQL Server), Power BI and GitHub**.

## 1. Business Problem
Olist's marketplace is growing, but customer satisfaction is uneven and very few customers buy a second time. Leadership wants to know:
- Where does revenue come from?
- Where is the delivery experience failing, and how much does it hurt customer reviews?
- What should the business fix first?


## 2. Key Questions
1. How have revenue and orders trended over time?
2. Which product categories drive revenue? Which have high freight cost relative to price?
3. What share of orders are delivered late, and where (state, seller, category)?
4. How does delivery delay affect review scores?
5. How many customers buy again, and is it linked to their first experience?
6. Which sellers combine high volume with poor performance?

## 3. Tools Used
| Stage | Tool | Purpose |
|---|---|---|
| Cleaning & preprocessing | Python (pandas, numpy, matplotlib, seaborn) | Clean data, engineer features, EDA |
| Analysis | SQL (SQL Server) | Joins, CTEs, window functions, views |
| Visualization | Power BI | Interactive executive dashboard |
| Version control | Git & GitHub | Documentation and reproducibility |

## 4. Project Workflow
```
Raw CSVs  ->  Python (clean + features)  ->  SQL Server (analysis + views)  ->  Power BI (dashboard)  ->  Insights & recommendations
```

## 5. Dataset
[Brazilian E-Commerce Public Dataset by Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce) (Kaggle), about 100k orders from 2016 to 2018 across 9 tables.
The raw data is not stored in this repo. See `data/README.md` for download instructions.

## 6. Data Cleaning Summary


## 7. Key Insights


## 8. Dashboard


## 9. Recommendations


## 10. How to Reproduce
1. Clone this repository
2. Install dependencies: `pip install -r requirements.txt`
3. Download the dataset into `data/raw/` (see `data/README.md`)
4. Run the notebooks in `notebooks/` in order
5. Run the SQL scripts in `sql/` in order
6. Open `powerbi/olist_dashboard.pbix`

## 11. Repository Structure
```
├── data/
│   ├── raw/          (original CSVs, not committed)
│   └── processed/    (cleaned CSVs)
├── notebooks/        (Python cleaning and EDA)
├── sql/              (schema, queries, views)
├── powerbi/          (.pbix file and screenshots)
├── docs/             (data dictionary, notes)
├── requirements.txt
└── README.md
```

