# Model Change Classification & Governance Decision Engine

## Overview

A rules-based Model Risk Governance tool that automatically classifies model-change requests as **Minor, Moderate, or Major** based on materiality, regulatory impact, methodology changes, data changes, validation requirements, production impact, and previous model issues.
The project demonstrates how manual model-change triage can be standardized and partially automated using Python and Power BI.

## Business Objective
Model changes in financial institutions require different levels of governance review. The objective of this project was to:
- Standardize model-change risk assessment
- Automate low-risk change triage
- Route higher-risk changes to appropriate governance teams
- Provide management visibility through a Power BI dashboard
- Estimate the potential reduction in manual review effort

## Key Results
The engine automatically triaged **50% of simulated change requests** as Minor while routing Moderate and Major changes for enhanced governance review.

**Power BI Dashboard**
The dashboard provides:
- Executive KPI summary
- Change classification distribution
- Risk score monitoring
- Model-level change analysis
- Change-type analysis
- Regulatory-triggered changes
- Prior model issue monitoring
- Approval and governance status
- Required reviewer/action

**Tools**
- Python
- Pandas
- Jupyter Notebook
- Power BI
- Excel / CSV
- Matplotlib
