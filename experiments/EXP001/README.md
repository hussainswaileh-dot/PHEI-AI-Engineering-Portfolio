# Experiment 001 — Medical Waste Manifest Validator

## Project Overview
A Python-based, rule-driven prototype for detecting weight discrepancies between medical waste transportation and treatment records.

## Business Problem
Differences between transportation and treatment weights require verification before operational or compliance conclusions can be made.

## Technologies
- Python 3.13.18
- pandas 2.2.3
- Google Colab
- Jupyter Notebook

## Methodology
1. Created three synthetic medical waste manifest records.
2. Calculated transportation minus treatment weight.
3. Filtered records with non-zero differences.
4. Validated expected results using four Python assertions.

## Verified Results
- Synthetic records: 3
- Records flagged for review: 1
- Flagged manifest: MW002
- Weight difference: 5 kg
- Automated assertions passed: 4/4

## Limitations
This prototype was tested on three synthetic records only. It does not establish real-world accuracy, compliance violations, scalability, or measured operational savings.

## Privacy and Governance
No real healthcare operational records or confidential information were used. Human review is required before drawing operational conclusions.

## Next Development
Expand to CSV/Excel imports, missing-value checks, duplicate detection, and transportation-treatment reconciliation.
