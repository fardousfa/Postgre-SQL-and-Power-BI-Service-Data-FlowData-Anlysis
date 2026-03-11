# Postgre-SQL-Microsoft-Fabric-and-Power-BI-Service-Data-Anlysis
Designed and implemented a secure, automated reporting solution that connects on‑premises PostgreSQL data to Power BI Service, enabling semantic modelling, interactive dashboards, and enterprise‑wide app distribution. The solution follows data governance best practices to ensure accuracy, compliance, and trust in reporting.


## Tech Stack

- Database: PostgreSQL (On‑Premises)

- ETL: Power BI Dataflows, Power Query

- Modelling: Power BI Desktop (DAX, Star Schema)

- Deployment: Power BI Service, Power BI Apps

- Security & Governance: On‑Premises Data Gateway, Row‑Level Security, Azure AD, GDPR compliance

## Process & Workflow

### 1. Data Source & Connectivity ###

     Connected to on‑premises PostgreSQL database via On‑Premises Data Gateway for secure, encrypted data transfer.

     Selected and optimised relevant tables/views for reporting (e.g., financial transactions, operational KPIs).
    
### 2. Dataflow Creation in Power BI Service ###

    Built Power BI Dataflows to centralise ETL logic.

    Applied Power Query transformations for data cleaning, standardisation, and enrichment.

    Implemented incremental refresh policies to optimise performance.

### 3. Semantic Model in Power BI Desktop

    Designed a star schema for efficient querying and scalability.

    Created calculated columns and measures using DAX for financial metrics (e.g., YoY growth, variance analysis).

    Applied consistent formatting, naming conventions, and hierarchies for usability.

### 4. Publishing & App Creation

    Published the semantic model and reports to Power BI Service.

    Organised content into Workspaces and created Power BI Apps for controlled distribution.

    Configured scheduled refreshes to ensure up‑to‑date insights.

### 5. Data Security, Governance & Administration

    Row‑Level Security (RLS) to restrict data access by department or role.

    Managed user permissions via Azure Active Directory groups.

    Followed data governance practices:

        Defined data ownership and stewardship roles.

        Maintained data dictionaries and metadata documentation.

        Applied naming conventions and version control for datasets and reports.

        Ensured compliance with GDPR and internal data handling policies.

    Monitored refresh history, performance metrics, and usage analytics for governance.

## Dashboard

<img width="1919" height="1001" alt="Dashboard" src="https://github.com/user-attachments/assets/a80d75df-ea73-489d-aceb-3a7c822a6d3e" />

## Dataflow

<img width="1919" height="709" alt="Dataflow" src="https://github.com/user-attachments/assets/fb062e94-1ded-4e63-9214-1edfe6d3c374" />


