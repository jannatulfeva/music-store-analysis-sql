# music-store-analysis-sql
Analyzing a relational music database to understand consumer behavior, artist performance, and regional sales trends using PostgreSQL.

# Overview
This project audits a complex relational music store database to extract actionable business intelligence. The goal is to analyze the relationship between artists, genres, and customer spending habits across different global regions. Using advanced SQL techniques, the project transforms raw transactional data into a clear picture of market performance and listener engagement.

# Business Objective
The main objectives of this project are:

- Analyze revenue distribution across different musical genres.

- Identify the highest-spending customers in each geographic region.

- Determine the most popular artists based on track purchase frequency.

- Rank market performance by country to identify top revenue drivers.

- Solve multi-dimensional business questions using complex relational queries.

# Dataset
The project utilizes a relational database containing several interconnected tables:

- Invoice & InvoiceLine: Transactional details and totals.

- Customer: Geographic and contact information for global clients.

- Track & Album: Details on specific music offerings.

- Artist & Genre: Categorization and credit for the music catalog.

# Tools & Technologies
The analysis was performed using:

- PostgreSQL: For complex data querying and relational management.

- SQL Techniques: CTEs (Common Table Expressions), Window Functions (ROW_NUMBER), Joins, and Aggregations.

- Database Schema: Multi-table relational structure.

# Data Analysis & Query Logic
To extract insights, several advanced SQL operations were executed:

- Complex Joins: Linked customer data with invoice and track details to map global spending.

- CTEs: Used to create temporary result sets for multi-step calculations like "Top Genre per Country."

- Window Functions: Applied ROW_NUMBER() and RANK() to identify the #1 customer and artist in each specific region.

- Aggregations: Summarized total sales and track counts to identify volume leaders.

# Key Findings
The analysis revealed several critical insights regarding global music sales:

- Rock emerged as the dominant genre, yielding the highest total sales volume and listener engagement.

- Identified the top-spending customer for every country by ranking regional invoice totals.

- Discovered the most popular artist in each country based on the number of tracks purchased.

- High-level revenue is heavily concentrated in specific geographic markets, with clear "Top 3" spending countries identified.

# How to Run This Project
- Clone the repository: https://github.com/jannatulfeva/music-store-analysis-sql

- Database Setup: Import the provided .sql file into your PostgreSQL environment (pgAdmin or psql).

- Execute Queries: Open the music_queries.sql file and run the scripts to see the results of the analysis.

# Final Recommendations
- Based on the SQL analysis, the following actions are recommended:

- Inventory Optimization: Increase the catalog depth for high-performing genres like Rock in top-spending regions.

- Targeted Marketing: Launch loyalty campaigns specifically for the "Top-Spending" customer segments identified in the analysis.

- Regional Tours: Use artist popularity data by country to suggest optimal locations for future live events or promotions.

- Cross-Selling: Bundle popular tracks from top artists with emerging artists in the same genre to diversify sales.

# Author & Contact
Jannatul Ferdaus Eva Data Analyst

📧 Email: jannateva76@gmail.com




















