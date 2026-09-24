# Appliance Energy Consumption Website (COS30045)

## Project Overview
This repository contains the interactive demonstration website and data exploration project built for **COS30045 Data Visualisation** at Swinburne University of Technology Sarawak Campus. It features a fully styled multi-page layout (Home, Televisions, About Us) communicating energy consumption insights for televisions in Australia[cite: 1, 6].

## Data Story & Audience Overview
* **Target Audience:** Everyday Australian consumers and eco-conscious households looking to evaluate energy efficiency, screen technologies, and operating power costs when purchasing new televisions.
* **Narrative Flow:** The website guides readers from general market adoption (screen technologies and top brands) down to specific efficiency metrics (screen size versus operating power consumption).

## About the Data
* **Data Source:** Published by the Australian Government via [data.gov.au](https://data.gov.au) (*Energy Rating Data for household appliances – Labelled Products - Televisions*)[cite: 1].
* **Data Processing:** Processed using KNIME Analytics Platform to remove missing records, filter active models (`Availability Status = "Available"`), eliminate duplicate entries (retaining the most recent model submission), convert screen dimensions from centimeters to inches, and normalize brand names to uppercase[cite: 1].
* **Privacy:** Contains public manufacturer registration data with no personal or private user information involved.
* **Accuracy and Limitations:** Data relies on standard manufacturer test declarations under controlled testing conditions (`AS/NZS 62087.1`), which may vary slightly under real-world household usage patterns.
* **Ethics:** Ensures unbiased, accurate representation across all registered appliance brands and manufacturers.

## AI Declaration
* **Tool Used:** GitHub Copilot[cite: 1].
* **Usage Reflection:** GitHub Copilot assisted in drafting HTML templates, structuring responsive CSS grid layouts, and writing navigation rules. All generated code was thoroughly reviewed, tested, and understood independently without relying on inline comments[cite: 1].
