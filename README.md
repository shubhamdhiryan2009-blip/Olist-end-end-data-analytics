# Olist End-to-End E-Commerce & Marketing Analytics

An end-to-end data analytics pipeline engineered on the Olist Brazilian E-Commerce and Marketing Funnel datasets. This repository mirrors production-grade analytics workflows, covering the complete lifecycle: **Raw Data Ingestion ➔ Structural Schema Design ➔ Controlled Data Validation ➔ Advanced SQL Analytics ➔ Interactive Power BI Intelligence**.

---

## 📌 Business Context & Objectives
[Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce) is the leading e-commerce department store solution connecting independent merchants across Brazil to major digital marketplaces. 

The objective of this project is to provide growth, operational, and financial insights by analyzing:
*   **Macro Performance:** Revenue quality, GMV progression, and historical order fulfillment velocity.
*   **Behavioral Dynamics:** Core geographical and cyclical trends driving buyer and merchant behaviors.
*   **Growth Marketing Funnel:** The efficiency of transitioning Marketing Qualified Leads (MQLs) into closed revenue-generating sellers.

---

## 📂 Data Scope & Architecture
This project blends operational transaction data with growth CRM datasets hosted on [Kaggle](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce), breaking down into two primary operational domains:

### 1. E-Commerce Transactions
*   **Core Entities:** `customers`, `orders`, `sellers`, `products`, `product_category_name_translation`, `order_items`, `order_payments`, `order_reviews`, and `geolocation`.

### 2. Marketing CRM Funnel
*   **Core Entities:** `marketing_qualified_leads` (Top-of-Funnel) and `closed_deals` (Bottom-of-Funnel Conversion metrics).

Detailed schema lineages and dataset references are thoroughly mapped out inside the [`02_data_sources/`](02_data_sources/) directory.

---

## ⚙️ Repository Architecture
The structure of this project directly reflects the progressive engineering checkpoints of an enterprise analytics team:

*   **[`01_project_overview/`](01_project_overview/)**: High-level problem framing, KPIs, and operational scopes.
*   **[`02_data_sources/`](02_data_sources/)**: Source profiles, structural types, and file lineage maps.
*   **[`03_ddl_table_creation/`](03_ddl_table_creation/)**: Primary structural DDL staging arrays and final analytical schemas.
*   **[`04_dml_data_load/`](04_dml_data_load/)**: Regulated ingestion scripts and data transformation transformations.
*   **[`05_data_validation/`](05_data_validation/)**: Data quality checks, primary/foreign key constraint verifications, and sanity audits.
*   **[`06_star_schema/`](06_star_schema/)**: Modeled definitions and comprehensive dimensional ERDs.
*   **[`07_Analytical_Insights/`](07_Analytical_Insights/)**: Performance-tuned production SQL queries driving metric calculations.
*   **[`08_power_bi_dashboard/`](08_power_bi_dashboard/)**: Power BI asset distribution maps, measures code, and UI screenshots.

---

## 🧠 Data Modeling Strategy
> *"Knowing when not to use a star schema is just as crucial as knowing how to design one."*
