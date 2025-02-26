# ThreatSentry
An automated threat hunting tool using machine learning to detect and report suspicious activity in logs.

## Features
- Parses logs with regex for threat patterns (e.g., brute force, SQL injection)
- Classifies threats with a trained ML model (85% accuracy on test data)
- Generates CSV and HTML reports with IOCs

## Tech Stack
- Python 3.9, scikit-learn, pandas
- Flask (for optional web dashboard)

## Setup
1. Clone the repo: git clone https://github.com/ravitejaannam-008/ThreatSentry.git cd ThreatSentry
2. Install dependencies: pip install -r requirements.txt
3. Download sample logs or use your own.
## Usage
Hunt threats in a log file: python hunt.py --log logs/auth.log --output reports/threats.csv 
Or launch the dashboard: python app.py
## Example
## Why This Matters
Evolved from my SIEM optimization at Indian Railways, where I cut false positives by 25%—now with ML power.
