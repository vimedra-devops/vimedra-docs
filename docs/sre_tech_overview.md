# VIMEDRA's Socio-Medical Risk Engine (SRE)

## Overview

The **Socio-Medical Risk Engine (SRE)** is VIMEDRA’s patent-pending intelligence core that predicts patient risk by blending **clinical data with social determinants of health (SDoH)**.

Filed as U.S. Patent Application **63/773,968** on **March 18, 2025**, the SRE represents a first-of-its-kind model that unifies both **structured medical signals** and **unstructured social context** to guide real-time interventions.

---

## 🔬 Why We Built the SRE

Traditional risk models focus on clinical inputs: ICD codes, vitals, or lab data. But these models fail to capture real-life context — such as housing instability, food access, or transportation barriers — which have a massive impact on health outcomes.

VIMEDRA’s SRE fills this gap by:

- Quantifying **social fragility** and **community strain**
- Linking SDoH risk to clinical deterioration likelihood
- Enabling **predictive, not reactive**, navigation

---

## 🧠 Core Architecture

The SRE uses a **dual-layered Bayesian engine**:

1. **Medical Layer**
   - Claims history
   - Diagnoses (e.g., diabetes, COPD, hypertension)
   - ER visits, hospitalizations
   - Medication adherence patterns

2. **SDoH Layer**
   - Housing status
   - Food insecurity indicators
   - Family/caregiver context
   - Community-level deprivation indices
   - Interview-based conversational triggers from Phoebe

These two layers are **cross-weighted and calibrated** in real time to produce a composite score: the **SRE Index** (0–100).

---

## 🧩 What Makes the SRE Unique

- **Dual-source ingestion**: Combines structured (EHR/claims) and conversational (Phoebe) data
- **Dynamic updating**: Scores update with each interaction, even before a new diagnosis is coded
- **Explainability-first**: Outputs come with rationale (e.g., “High risk due to recent housing loss + poorly managed diabetes”)
- **Embedded in voice flow**: Triggers automatic follow-up from Phoebe or human navigators

---

## ⚙️ Technical Stack

- Engineered on Google Cloud using:
  - Vertex AI
  - BigQuery ML
  - Custom TensorFlow + XGBoost models
- Built-in FHIR compliance for healthcare data pipelines
- Easily integratable with EHRs and care platforms

---

## 🔐 Privacy & Compliance

- All risk scores are computed under HIPAA-compliant safeguards
- Data anonymized for aggregate insights
- Users can opt-out of any tracking or feedback

---

## Impact

> With SRE, VIMEDRA can predict who is likely to fall through the cracks — **before** they do.

Whether it’s avoiding preventable hospitalizations or identifying rising-risk patients silently suffering with unmet needs, the SRE is designed to **guide outreach that saves lives and dollars**.

