# Appliance Energy Consumption Website (COS30045)

## Project Overview
This repository contains the interactive website and data exploration project built for **COS30045 Data Visualisation** at Swinburne University of Technology Sarawak Campus[cite: 1, 6]. It features a multi-page layout (Home, Televisions, About Us) to help everyday users explore energy efficiency trends for televisions in Australia[cite: 1, 6].

## Data Story & Audience Overview
* **Target Audience:** Everyday Australian consumers and eco-friendly households who want to check energy ratings, power usage, and screen technology before buying a new TV.
* **Narrative Flow:** The website starts by showing general market trends—such as the most popular screen technologies and top brands—and then dives deeper into technical details like screen size versus power consumption.

## About the Data
* **Data Source:** Published by the Australian Government via [data.gov.au](https://data.gov.au) (*Energy Rating Data for household appliances – Labelled Products - Televisions*)[cite: 1].
* **Data Processing:** I processed the dataset using the KNIME Analytics Platform to drop missing rows, filter for active products (`Availability Status = "Available"`), remove duplicates, convert screen sizes from centimeters into inches, and make brand names uppercase[cite: 1].
* **Privacy:** The dataset only contains public manufacturer registration details with no personal user information involved.
* **Accuracy and Limitations:** The data is based on standard manufacturer tests (`AS/NZS 62087.1`), which means real-world energy use at home might vary slightly depending on individual usage habits.
* **Ethics:** The project maintains an ethical approach by presenting an unbiased and fair representation of all registered appliance brands.

## AI Declaration
* **Tool Used:** GitHub Copilot[cite: 1].
* **Usage Reflection:** GitHub Copilot helped me draft the initial HTML structure and organize the responsive CSS grid layout. I carefully reviewed, tested, and understood all the code myself without relying on inline comments[cite: 1].
