# Lusangazi Town Council Digital Footprint & CDF Dataset (CSC 4792)

## Overview
This repository contains the data engineering pipeline, curated open-government datasets, and methodological documentation for the digital footprint of **Lusangazi Town Council**, Zambia. Created as part of the **CSC 4792 Data Engineering** course at the University of Zambia, this project extracts, cleans, standardizes, and audits civic data to enhance open-data access and transparency regarding council operations and Constituency Development Fund (CDF) allocations.

## Key Features
* **Automated Web Scraping:** Programmatic crawling and HTML table extraction from the official council web portal using `BeautifulSoup`.
* **PDF Mining:** Deep text extraction and structural analysis of published council documents, Integrated Development Plans (IDPs), and financial reports using `PyMuPDF` (`fitz`).
* **Standardized Data Schema:** Cleaned, deduplicated, and formatted pipe-delimited (`|`) CSV exports following strict course naming and schema requirements (`db-unza26-csc4792-lusangazi_*`).

## Dataset Architecture
The project curates four primary pipe-delimited CSV datasets:
1. `db-unza26-csc4792-lusangazi_cdf_projects.csv` — CDF project allocations, financial estimates, sectors, and completion statuses.
2. `db-unza26-csc4792-lusangazi_council_documents.csv` — Document metadata audit of council publications and official reports.
3. `db-unza26-csc4792-lusangazi_wards_wdc.csv` — Ward Development Committee (WDC) structures, leadership, and zonal development priorities.
4. `db-unza26-csc4792-lusangazi_administration.csv` — Council administrative departments, key functional responsibilities, and contact directories.

## Tech Stack
* **Language:** Python 3
* **Data Processing:** `pandas`, `NumPy`
* **Scraping & Parsing:** `BeautifulSoup4`, `requests`, `PyMuPDF` (`fitz`)
* **Environment:** Google Colab / Jupyter Notebooks

## Data Availability
* **Kaggle Dataset:** [View on Kaggle](https://www.kaggle.com/datasets/gubasiachalinga/lusangazi-town-council-dataset)
* **License:** Creative Commons Attribution 4.0 International (CC BY 4.0)

