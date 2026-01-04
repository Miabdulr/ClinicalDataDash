# ClinicalDataDash
Clinical Data Dashboard
# Clinical Data Dashboard (Flask + Plotly + pandas)

A lightweight web dashboard that lets you upload a CSV of clinical/device metrics and instantly explore:
- time-series trends (when a timestamp column is detected)
- distributions and correlations across numeric metrics
- missing-value breakdown
- summary statistics preview

This project is designed to demonstrate practical software engineering skills: data ingestion, backend routing, basic analytics, and interactive visualization.

## Demo Features
- **CSV upload** with validation and file-size limits
- **Automatic timestamp detection** (e.g., `timestamp`, `date`, `time`)
- **Interactive Plotly charts**:
- trend line over time (if time column exists)
- histogram distribution
- scatter plot correlation (first two numeric columns)
- **Data quality checks**: missing values and summary statistics

## Tech Stack
- Python
- Flask
- pandas
- Plotly

## Getting Started

### 1) Clone and install
```bash
git clone <your-repo-url>
cd clinical-dashboard
python -m venv .venv
source .venv/bin/activate # Windows: .venv\Scripts\activate
pip install -r requirements.txt
