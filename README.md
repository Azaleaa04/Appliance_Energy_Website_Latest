# Appliance Energy Consumption Website (COS30045)

## Project Overview
This repository contains the interactive demonstration website and data exploration project built for COS30045 Data Visualisation. It features a multi-page layout (Home, Televisions, About Us) styled with custom CSS matching our power theme and interactive navigation.

## Data Story & Overview
* **Data Source:** Published by the Australian Government via data.gov.au ("Energy Rating Data for household appliances – Labelled Products - Televisions").
* **Data Processing:** Cleaned using KNIME Analytics Platform to drop missing values, filter duplicate model registrations (retaining the most recent submission), isolate models with an `Available` status, convert screen dimensions from centimeters to inches, and normalize brand names to uppercase.
* **Privacy:** Contains public manufacturer registration data with no personal or private user information involved.
* **Accuracy and Limitations:** Data relies on standard manufacturer test declarations under specific test conditions (`AS/NZS 62087.1`), which may vary slightly under real-world household usage.
* **Ethics:** Ensures unbiased, accurate representation across all registered appliance brands and manufacturers.

## AI Declaration
* **Tool Used:** GitHub Copilot.
* **Usage Reflection:** GitHub Copilot assisted in structuring HTML templates, writing responsive CSS layout rules, and debugging navigation event handlers. All generated code was reviewed, tested, and understood independently without relying solely on inline comments.
