# DIGI-DATA
DIGI DATA transforms forensic accounting investigations from hours of manual spreadsheet analysis into seconds of AI-assisted anomaly detection.
#  DIGI DATA | Specialized Forensic Accounting Agent 

> **DIGI DATA transforms forensic accounting investigations from hours of manual spreadsheet analysis into seconds of AI-assisted anomaly detection.**

*Built for the Google Cloud Rapid Agent Hackathon* ☁️

DIGI DATA is not just an AI wrapper for pandas; it is a specialized Forensic Accounting Agent powered by Google Gemini. It bridges the gap between raw financial datasets and actionable investigative insights by translating natural language commands into complex, executed financial audits in real-time. 

##  The Problem It Solves
Traditional forensic accounting requires hours of manual data wrangling, VLOOKUPs, and pivot tables to find a single fraudulent transaction. DIGI DATA automates this logic. By combining accounting domain expertise with Large Language Models, it allows auditors to hunt down phantom assets, vendor collusion, and duplicate billing using plain English.

##  Core Features

* ** Forensic Knowledge Engine:** Pre-engineered to understand and investigate complex accounting fraud typologies, moving beyond basic data cleaning.
* **Risk Scoring System:** Instead of binary "High/Low" flags, the agent can be prompted to calculate a **Fraud Risk Score (0-100)** based on multiple variables (e.g., missing descriptions, unusual amounts, duplicate dates).
* ** Natural Language Auditing:** Instruct the agent like a junior auditor (e.g., "Find duplicate invoices"). The agent reasons, writes the pandas logic, and executes it securely.
* ** Real-Time Reasoning Terminal:** Judges and users can watch the AI "think." The terminal displays the agent's step-by-step logic and the generated Python code before modifying the dataset.
* ** Secure & Unrestricted Execution:** Engineered with strict systemic guardrails to prevent unintended data loss (no dropped rows without explicit permission). Exports massive datasets using frontend Blob technology without browser truncation.

## Tech Stack

* **Frontend:** React.js (Vite), Glassmorphism UI, Custom Terminal Component.
* **Backend:** FastAPI (Python), Pandas (Data Manipulation), MongoDB (Persistent Logging & Sync).
* **AI Engine:** Google Gemini 1.5/2.5 Flash API (Agentic Reasoning & Code Generation).

## Example Investigative Workflow

Instead of writing complex SQL or Python, an investigator simply types:

> *"Act as a forensic auditor. Evaluate the dataset for Phantom Assets. Create a new column 'Risk_Score'. Add 40 points if the Description is missing, and 60 points if the Amount_USD is unusually high compared to the average. Return the dataset with the exact same number of rows."*

**The Agent Will:**
1. Log its reasoning in the terminal.
2. Write the exact mathematical and pandas logic to evaluate the conditions.
3. Append the new `Risk_Score` column for immediate review and download.

---
*Transforming data into evidence. Developed for the 2026 Google Cloud Rapid Agent Hackathon.*
