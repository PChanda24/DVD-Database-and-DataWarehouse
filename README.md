# DVD Rental Database and Data Warehouse

## Problem Definition

The problem at hand involves efficiently managing and extracting valuable insights from a DVD rental database to address various business needs and challenges. The database consists of 15 tables storing information related to actors, films, categories, stores, inventory, rentals, payments, staff, customers, addresses, cities, and countries.

## Operational Business Context
- **Inventory Management:** Tracks DVD availability and stock.
- **Customer Information:** Stores customer data and rental history.
- **Rental Transactions:** Records rental details for billing and tracking.
- **Payment Processing:** Handles payment transactions.
- **Staff Management:** Manages information about store staff.
- **Film Catalog:** Maintains a catalog of available films.
- **Relationships:** Establishes relationships between films, actors, and categories.

## Analysis
- **Customer Behavior Analysis:** Analyzing frequently rented DVDs, customer demographics, and rental durations.
- **Inventory Management:** Monitoring inventory and identifying high-demand genres.
- **Financial Analysis:** Tracking revenue to identify peak seasons.
- **DVD Preferences:** Identifying popular films and influences on rental choices.
- **Geographic Analysis:** Analyzing rental preferences by location.
- **Time-Series Analysis:** Identifying trends and seasonality in rentals.
- **Operational KPIs:** Monitoring key performance indicators.
- **Inventory Aging:** Identifying under-rented DVDs for potential discounts or retirement.

## Steps involved:
- Set up the PostgreSQL database.
- Create a database named DVD_Rental.
- Run the SQL scripts in the sql folder to create tables and populate data.
- Set up the ETL pipeline using Talend.
- Configure the PostgreSQL connection and run the ETL jobs.
- Perform analysis using Tableau
- Connect to the PostgreSQL database and refresh data sources to update the visualizations.

The completion of this project marks the successful integration of the DVD Rental Database into Talend, with data loaded from PostgreSQL. The implemented ETL pipelines have significantly enhanced data processing efficiency, streamlining the flow of information throughout the system. The project's architecture is designed with scalability in mind, allowing for future expansion and adaptation to accommodate growing data volumes and evolving business needs.
