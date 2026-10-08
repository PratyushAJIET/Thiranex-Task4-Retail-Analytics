# Thiranex Task 4 — End-to-End Retail Analytics

**Author:** Pratyush  
**Domain:** Retail / E-commerce  
**Dataset:** **Synthetic educational sample**, not real store sales or private customer records.  
**Tutorial reference:** https://youtu.be/MEJFJHp4tiA

## Objective
Analyze fictional retail transactions using Pandas: join customer/product/transaction tables, compute sales revenue, analyze monthly performance, top products, categories, customer spending and regions, and visualize the results.

## Project results (illustrative)
- Transactions: **1,800**
- Customers: **250**
- Total revenue: **INR 3,606,930.50**
- Average order value: **INR 2,003.85**
- Highest revenue month: **2025-11**
- Top category: **Fashion**
- Top product: **Jacket**

## Run in Google Colab
1. Upload `retail_analytics.ipynb` to https://colab.research.google.com/.
2. In the left Files sidebar upload **all 3** files: `customers.csv`, `products.csv`, `transactions.csv`.
3. If charts do not appear, create a `charts` folder (the project ZIP contains it) or upload the chart images. Locally, keep the `charts/` folder alongside the notebook.
4. Click **Runtime > Run all**. The notebook runs top-to-bottom and produces charts and `retail_analysis_cleaned.csv`.
5. Download the executed notebook if you made changes.

## Repository files
- `retail_analytics.ipynb` — executable notebook with saved outputs
- `customers.csv`, `products.csv`, `transactions.csv` — input tables
- `retail_analysis_cleaned.csv` — merged dataset with calculated revenue
- `charts/` — 5 charts
- `EDA_Report.pdf` — formatted analysis report
- `requirements.txt` — libraries
- `GITHUB_SUBMISSION_GUIDE.md` — submission instructions

## Limitations
All dates, quantities, products, segments and customer IDs are fictional. Findings illustrate technical analysis only and should **not** be represented as results from real e-commerce operations. The tutorial's dataset is not included here. A real retail dataset would be required for claims about real-world market patterns.
