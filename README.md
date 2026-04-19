# Startup-investment-sql-analysis
SQL analysis of 27,000+ Crunchbase‑style startup records to identify funding trends, high‑risk sectors, and cleantech failure patterns. Demonstrates SQL querying, data cleaning, pattern matching, and analytical reasoning.

## Dataset
This project uses a Crunchbase‑style dataset provided by the Global Career Accelerator program. 
Due to licensing restrictions, the dataset cannot be publicly distributed and is therefore not included in this repository.

## Project Overview
This project explores startup funding patterns using SQL queries on a dataset of over 27,000 companies.  
The analysis focuses on:

- Identifying the top-funded companies  
- Investigating companies that received high funding but later closed  
- Examining the cleantech sector, which appears disproportionately in the “closed” category  
- Using pattern matching to explore naming trends within cleantech companies  

The goal is to understand funding distribution, risk factors, and industry-specific challenges.

## Key Findings
- **Clearwire** received the highest total funding among all companies.  
- **Abound Solar** was the most-funded company that later closed, with **$510M** in funding.  
- **6 of the top 12 closed companies** were in the **cleantech** category.  
- **898 companies** were labeled as cleantech; **7.02%** of them were closed.  
- **275 cleantech companies** contained “solar”, “power”, or “energy” in their names.

These findings highlight cleantech as a **high-funding but high-risk** sector.

## Skills Demonstrated
- SQL querying and data filtering  
- Handling NULL values  
- Aggregations, ordering, and segmentation  
- Pattern matching with 'ILIKE'  
- Data exploration and insight generation  
- Professional documentation and project structuring  

## Repository Structure
startup-investment-sql-analysis/
│
├── queries/
│   ├── top_funded_companies.sql
│   ├── top_closed_companies.sql
│   ├── cleantech_companies.sql
│   ├── closed_cleantech_companies.sql
│   └── cleantech_keyword_search.sql
│
└── results/
    └── findings.md


## How to Run the Queries
These queries are written for PostgreSQL syntax.  
To run them:

1. Load the dataset into a PostgreSQL database (if you have access).  
2. Open any .sql file from the queries folder.  
3. Execute the query in your SQL environment (psql, DBeaver, pgAdmin, etc.).  

Each query is self-contained and can be run independently.

## About This Project
This analysis was completed as part of the **Global Career Accelerator** program, where I served as a data analyst evaluating startup investment patterns for a hypothetical venture capital firm.
