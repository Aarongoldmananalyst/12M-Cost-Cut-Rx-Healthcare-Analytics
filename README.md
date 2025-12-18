<p align="center">
  <img width="1536" height="1024" alt="7a17b6fd-1663-430d-a85f-dae4d25c5d3e" src="https://github.com/user-attachments/assets/6a0ea2e2-1309-46a7-a235-58f2cb05c8e2" />

</p>


# 🏥 About This Project

**$12M Cost-Cut Rx** is a healthcare analytics portfolio project designed to demonstrate real-world data analysis, predictive modeling, and executive storytelling skills.

It simulates how a data analyst or healthcare business intelligence professional can use **Python, SQL, and Power BI/Tableau** to:
- Identify high-cost patient cohorts driving healthcare spend
- Detect claim denial root causes through predictive analytics
- Deliver dashboards and executive insights that recover **$12.1M annually**

This project mirrors a **consulting-style analytics engagement**, including technical code, synthetic datasets, data governance, and ROI modeling — all packaged for professional portfolio use.

The workflow follows a structured pipeline from raw claims data through feature engineering and analysis to executive-ready insights and recommendations.







<p align="center">
  <img width="1200" height="800" alt="pareto_curve" src="https://github.com/user-attachments/assets/ba7af04e-a3a0-432e-86ec-250f01b59c54" />



# 💊 $12M Cost-Cut Rx — Healthcare Analytics Project
**Executive Summary:** Targeted analytics identified high-cost claim drivers and denial risk segments, enabling projected annual savings of $12.1M with a 7-month payback.

---
![Python](https://img.shields.io/badge/Python-3.11-blue)
![License: MIT](https://img.shields.io/badge/License-MIT-green)
![Status](https://img.shields.io/badge/Status-Portfolio--Ready-success)

**Data-driven healthcare analytics to identify high-cost patients and reduce claim denials.**  
**Projected impact:** $12.1M annual savings · 7-month payback · 9:1 ROI

---

## 🔗 Quick Links
- ▶️ [View Jupyter Notebook](./Cost_Cut_Rx_Analytics.ipynb)
- 📊 [Download Sample Dataset](./sample_claims_data.csv)
- 🖼️ [View Pareto Chart](./pareto_curve.png)

- 📄 [Read Presentation Deck](./docs/12M_Cost_Cut_Rx_Presentation.pdf)

---

## 🖥️ Project Deck Preview
Click below to open the full presentation 👇  

[![Open PDF](https://img.shields.io/badge/View%20Presentation-12M_Cost_Cut_Rx-blue?logo=adobeacrobatreader)](./docs/12M_Cost_Cut_Rx_Presentation.pdf)

---

## 🧠 Problem Statement
- Top 5% of members drive **52%** of spend.  
- **11%** claim-denial rate risks **$9.7M** in annual revenue.  
- Need a unified, data-driven strategy to target **both** cost and denial drivers.

---

## 🧮 Data Overview
> **Note:** All data in this repository is **synthetic** for portfolio demonstration only.  
> No PHI or real patient data is included.

- **Sources:** Claims, EHR, and pharmacy feeds (2.4M claims + 900K encounters)  
- **Join Keys:** `member_id`, `service_date` (<0.1% unmatched)  
- **Reconciliation:** Within ±2% of finance ledger (audit-ready)

---

## 📊 Data Dictionary

| Column Name     | Description |
|-----------------|--------------|
| **member_id**   | Unique identifier for each patient or member. |
| **service_date**| Date of the medical service or claim submission. |
| **claim_amount**| Total billed amount for the service (USD). |
| **denied**      | Binary flag indicating if the claim was denied (1 = denied, 0 = approved). |
| **payer**       | Insurance provider responsible for the claim (e.g., Aetna, Medicare). |
| **service_type**| Type of medical service provided (Imaging, Infusion, Consultation, Surgery). |
| **month** *(derived)* | Month extracted from `service_date` for time-series analysis. |
| **is_high_cost** *(derived)* | Flag indicating if claim is in the top 5% of spenders. |

---

## 🔍 Analytics Approach
- **Exploratory Analysis:** Identify high-cost outliers and denial trends (Pareto principle)  
- **Predictive Modeling:** To identify high-risk claims and key drivers of claim denials 
- **Segmentation:** Stratify members by cost drivers for targeted interventions  
- **Governance:** HIPAA-aligned pipeline with PHI minimization

---

## ⚙️ Tech Stack
| Layer | Tools |
|:--|:--|
| Data Prep | Python (pandas, NumPy), SQL |
| Modeling | scikit-learn, XGBoost |
| Visualization | Power BI / Tableau |
| Pipeline | dbt, Delta Lake |
| Security | OAuth2, Role-Based Access, SHA-256 IDs |

---

## 💰 Results (Projected)
| Metric | Before | After | Impact |
|:--|:--|:--|:--|
| High-Cost Cohort Spend | 52% of total | 43% of total | ↓ 9% PMPM |
| Claim Denial Rate | 11% | < 8% | $4.3M saved |
| Estimated ROI | — | — | 9:1 |
| Payback | — | — | 7 months |

---
## 💡 Business Interpretation

The analysis shows that a small subset of patients and claim types account for the majority of healthcare spend. By prioritizing high-cost patient cohorts and high-denial claim categories, payers can focus intervention efforts where they deliver the greatest financial impact.

---

## 🧪 Quickstart
```bash
# 1) Clone this repository
git clone https://github.com/<YOUR-USERNAME>/<YOUR-REPO-NAME>.git
cd <YOUR-REPO-NAME>

# 2) (Optional) Create and activate a virtual environment
python -m venv venv
source venv/bin/activate   # Windows: venv\Scripts\activate

# 3) Install dependencies
pip install -r requirements.txt

# 4) Launch the notebook
jupyter notebook Cost_Cut_Rx_Analytics.ipynb
🗺️ Roadmap
📅 Six-Month Plan

Month	Milestone
0–1	Charter & Data Access
2	Case Management Pilot
3	AI Coding Rollout
4	Dashboard Launch
6	Savings Validation

🧩 Deliverables
Cost_Cut_Rx_Analytics.ipynb — Jupyter notebook for analysis

sample_claims_data.csv — synthetic dataset

visuals/pareto_curve.png — Pareto visualization

docs/12M_Cost_Cut_Rx_Presentation.pdf — project deck

README.md + data notes

🗂️ Repo Structure
markdown
Copy code
.
├── README.md
├── requirements.txt
├── Cost_Cut_Rx_Analytics.ipynb
├── sample_claims_data.csv
├── visuals/
│   └── pareto_curve.png
└── docs/
    └── 12M_Cost_Cut_Rx_Presentation.pdf
🧭 Lessons Learned
Trusted, reconciled data drives executive buy-in more than complex models.

Cross-functional alignment (finance + clinical + IT) accelerates ROI.

Analytics must feed operational workflows to create sustained impact.

🤝 Contact
Author: Aaron Goldman
LinkedIn: linkedin.com/in/aaron-goldmans


