# MySQL Supply Chain and Procurement Analysis

This folder contains the SQL scripts used to store, analyze, and calculate performance metrics from the prepared Trans Mountain supply chain and procurement datasets.

MySQL will be used to examine procurement spending, purchase order activities, supplier performance, delivery efficiency, and materials and inventory performance.

## SQL Scripts

### 01_database_setup.sql
Creates the project database and the required tables for storing prepared procurement and supply chain datasets.

### 02_procurement_analysis.sql
Analyzes purchasing activities, procurement expenditure, purchase order volumes, and procurement trends.

### 03_supplier_performance_analysis.sql
Evaluates supplier performance, delivery reliability, lead times, and supplier-related procurement issues.

### 04_procurement_kpi_calculations.sql
Calculates relevant procurement and supplier performance KPIs using the available dataset fields.

### 05_materials_and_inventory_analysis.sql
Examines material availability, consumption patterns, stock levels, and potential inventory risks where the required data is available.

## Tools
- MySQL
- SQL

## Workflow
Prepared Datasets → MySQL Database → SQL Analysis → KPI Calculations → Procurement and Supply Chain Insights

**Note:** Forecasting model development will be handled separately in the forecasting folder using Python. SQL analysis will provide historical data and performance metrics that may support forecasting.
