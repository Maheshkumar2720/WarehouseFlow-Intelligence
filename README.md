# WarehouseFlow Intelligence

## End-to-End Warehouse & Logistics Analytics Platform

WarehouseFlow Intelligence is an end-to-end supply-chain analytics portfolio project built around a fictional device repair and returns warehouse.

The project demonstrates how warehouse operational data can be transformed into useful business insights using SQL, Python, forecasting, anomaly detection, and Generative AI.

> All data used in this project is synthetic. No proprietary employer, customer, or operational data is included.

## Business Questions

This project investigates:

- Which warehouse routes generate the highest workload?
- Which flows may represent bottlenecks?
- How efficiently are movements completed?
- Which locations are approaching or exceeding capacity?
- Are SKUs fragmented across too many storage locations?
- Which movements show unusual processing delays?
- Can future warehouse workload be predicted?
- Can an AI copilot explain warehouse analytics to managers?

## Technology Stack

- PostgreSQL
- SQL
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- JupyterLab
- Power BI
- OpenAI API
- Git
- GitHub

## Project Stages

1. Business Understanding
2. Data Architecture
3. Synthetic Dataset Generation
4. Data Cleaning & Transformation
5. SQL Business Analysis
6. Python EDA
7. Advanced Analytics
8. Power BI
9. Forecasting & Anomaly Detection
10. AI Supply Chain Copilot
11. GitHub Portfolio Packaging
12. Recruiter Presentation & Interview Preparation

## Key Findings

- 66,425 movement records analysed
- Approximately 2.29 million units moved
- Completion rate of approximately 85.9%
- Average completed movement processing time of approximately 236 minutes
- Median processing time of approximately 201 minutes
- High-risk routes included:
  - Racking → Racking
  - Screening → Racking
  - Repair → Racking
- One BIN location exceeded configured capacity
- Severe SKU fragmentation was not observed
- Baseline workload prediction MAE was approximately 14.9 movements per day
- Workload and processing-time anomalies were identified

## AI Copilot Architecture

Manager Question
↓
Trusted Analytics Layer
↓
KPI / Risk Results
↓
LLM Interpretation
↓
Manager-Friendly Recommendation

## Repository Structure

WarehouseFlow_Intelligence/
├── 01_Raw_Data/
├── 02_SQL/
├── 03_Python/
├── 04_PowerBI/
├── 05_Documentation/
├── 06_Final_Portfolio/
├── README.md
├── requirements.txt
└── .gitignore

## Data Ethics

The project is inspired by realistic warehouse and logistics workflows but uses only synthetic data.

## Future Improvements

- Complete Power BI dashboard
- Improve forecasting with lag features
- Deploy the AI copilot through a web application
- Add automated warehouse alerts
- Improve risk-scoring methodology

## Author

Mahesh Kumar Akula

Computer Science student focused on Data Analytics, Data Science, Generative AI, and practical AI engineering.
