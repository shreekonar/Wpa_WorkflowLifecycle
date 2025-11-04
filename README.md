# Wpa_WorkflowLifecycle
Efficient workflow lifecycle analytics pipeline processing 4M+ workflows and 41M+ audit events using DuckDB and Python. Features chunked Parquet processing, feature engineering for complexity and SLA metrics, exporting data for Power BI dashboards enabling operational insights and bottleneck identification at scale.

# WPA Workflow Lifecycle Analytics

**Advanced workflow lifecycle analytics for high-volume operational data.**

This repository contains the data engineering pipeline, feature extraction, and dashboard integration used for large-scale analysis of workflow lifecycle records at WPA. Developed as part of a dissertation project.

## Key Features

- Efficient chunked Parquet file processing using DuckDB and Python
- Feature engineering for complexity scoring, SLA assessment, and workflow performance categorization
- Data export in CSV and Parquet formats, compatible with Power BI dashboarding
- Dashboard screenshot samples and a link to the interactive Power BI visualization

## Files

- `workflow_analysis.py` or `workflow_analysis.ipynb`: Main processing code
- `Appendix.md`: Methodology, detailed data dictionary, and documentation
- `/images/`: Dashboard snapshots
- `LICENSE`: Terms of use (MIT or enterprise-specific)

## Power BI Dashboard

Access the interactive Power BI dashboard 
https://cf-my.sharepoint.com/personal/konars_cardiff_ac_uk/_layouts/15/onedrive.aspx?id=%2Fpersonal%2Fkonars%5Fcardiff%5Fac%5Fuk%2FDocuments%2Fshree%2FDissertation%2FWpa%5Fworkflow%2Epbix&parent=%2Fpersonal%2Fkonars%5Fcardiff%5Fac%5Fuk%2FDocuments%2Fshree%2FDissertation&ga=1.

## Getting Started

1. Install requirements:  
   `pip install duckdb pandas`
2. Place your Parquet data files in the `/Data` folder (sample data only, no confidential data).
3. Run the Python script or Jupyter notebook.
4. Exported results are available in CSV/Parquet and can be visualized using Power BI.



