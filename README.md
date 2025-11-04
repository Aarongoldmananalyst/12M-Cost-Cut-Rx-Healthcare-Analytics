# 12M-Cost-Cut-Rx-Healthcare-Analytics
Data-driven healthcare analytics: identify high-cost patients &amp; reduce claim denials. $12.1M savings, 7-month payback, 9:1 ROI.
💊 $12M Cost-Cut Rx — Restoring Healthcare Margins Through Data

Project Goal:
Use data analytics to identify high-cost patient cohorts and reduce insurance claim denials — driving $12.1M in annual savings and improving financial resilience.

## 🧠 Problem Statement

Top 5% of members drive 52% of spend.

11% claim-denial rate risks $9.7M in annual revenue.

Need for a unified, data-driven strategy to target both cost and denial drivers.

## 🧮 Data Overview

Sources: Claims, EHR, and pharmacy feeds (2.4M claims + 900K encounters).

Join Keys: member_id, service_date (<0.1% unmatched).

Data Quality: 2% reconciliation variance with finance ledger.

## 🔍 Analytics Approach

Exploratory Analysis: Identify high-cost outliers and denial trends (Pareto principle).

Predictive Modeling: Machine-learning denial probability model (AUC > 0.85).

Segmentation: Stratify patients into cost cohorts for care management targeting.

Governance: Audit-ready, HIPAA-compliant data pipeline with PHI minimization.

## ⚙️ Tech Stack
Layer	Tools Used
Data Prep	Python (pandas, NumPy), SQL
Modeling	scikit-learn, XGBoost
Visualization	Power BI / Tableau
Data Pipeline	dbt, Delta Lake
Security	OAuth2, Role-Based Access, SHA-256 ID hashing
## 💰 Results
Metric	Before	After	Impact
High-Cost Cohort Spend	52% of total	43% of total	↓ 9% PMPM
Claim Denial Rate	11%	<8%	$4.3M saved
ROI	-	-	9:1
Payback	-	-	7 months
## 🗺️ Roadmap

Month 0–1: Charter + Data Access
Month 2: Case Management Pilot
Month 3: AI Coding Rollout
Month 4: Dashboard Launch
Month 6: Savings Validation

## 🧩 Deliverables

Jupyter notebooks for analysis

Power BI dashboard screenshots

Data dictionary / ERD diagram

PDF presentation (link to your “$12M Cost-Cut Rx” deck
)

Project documentation notebook

## 🧭 Lessons Learned

Data-driven governance ensures both accuracy and compliance.

Cross-functional collaboration (finance, IT, clinical) accelerates ROI.

Predictive analytics must tie directly to actionable workflows to drive savings.

## 🤝 Contact

Author: Aaron Goldman
LinkedIn: linkedin.com/in/aaron-goldmans
