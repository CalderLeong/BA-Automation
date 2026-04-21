Business Analyst: Automation & Workflow Optimization

This repository serves as a centralized hub for tools and scripts developed to solve repetitive manual processes in the banking sector. The focus is on **Regulatory Compliance**, **Requirement Engineering**, and **UAT Acceleration**.

---

## 🚀 Active Projects

### 1. SDIC Clause Validator (OCR)
* **The Problem:** Manual auditing of 10k+ customer letters for mandatory SDIC clauses was slow and high-risk.
* **The Solution:** A Python-based OCR script (Tesseract) that scans PDFs for specific string patterns.
* **Impact:** Reduced audit time from 40 hours to ~12 minutes with 100% population coverage.

### 2. Logic-Driven UAT Generator
* **The Problem:** Writing manual UAT test cases for complex products was prone to human error and oversight.
* **The Solution:** A script that transforms structured requirements into comprehensive SIT/UAT test case sheets.
* **Impact:** Standardized testing quality across Deposits, Mobile, and Web teams.

### 3. Requirement Mapping Tool (Mermaid.js)
* **The Problem:** Fragmented email chains make it difficult to visualize system dependencies for new projects.
* **The Solution:** Converts text-based requirements into interactive dependency maps for faster onboarding.

---

## 🛠️ Productivity Toolbox
*Tools designed to accelerate daily BAU (Business As Usual) tasks.*

### 📸 Automated UAT Evidence Capturer
* **Problem:** Manually taking and saving screenshots for hundreds of UAT steps is the most time-consuming part of testing.
* **Solution:** A Python script using `Selenium` or `PyAutoGUI` to automatically capture, timestamp, and label screenshots based on test case IDs.
* **Benefit:** Ensures audit-ready evidence with zero manual effort.

### 🧪 Synthetic Customer Data Factory
* **Problem:** Manually creating mock data (NRIC, Account Numbers, Names) for SIT/UAT environments is repetitive and prone to duplication.
* **Solution:** A data generation script that outputs CSV/Excel files containing unique, valid-format "Dummy Customers" for bulk uploading into the RBS/ODUS systems.
* **Benefit:** Speeds up test environment setup by 90%.
---

### 🔒 Data Safety & Compliance
**Strict adherence to banking security protocols:** * All code utilizes **synthetic data** and dummy variables.
* No PII (Personally Identifiable Information) or internal bank credentials are included.
* All internal server paths have been abstracted to generic local directories.
