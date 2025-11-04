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
