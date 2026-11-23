# bankpulse-ai
Early-warning analytics for bank financial health
# BankPulse AI

Early-warning analytics for bank financial health.
ANCP Term 5, 2026 | Team T01

## What it does
Screens 20 Indian banks (FY2017-FY2026) using financial ratios, peer
comparison, DuPont ROE decomposition and IQR-based anomaly flags.

## Folder layout
- `data/raw/`        source workbooks (not uploaded: licensed data)
- `data/processed/`  frozen dataset `bank_financial_data_v3.csv`
- `notebooks/`       EDA and modelling notebooks
- `src/`             analytics engine and dashboard code
- `docs/`            deliverables (D1-D7, E1), meeting log, checksums

## Data versioning
v3 is frozen and never edited in place. Any change creates v4 with a new
SHA-256 checksum and a changelog entry in `docs/CHECKSUMS.md`.

## Setup
    pip install -r requirements.txt

## Team
Team T01, ANCP Term 5, 2026
