# LA Crime Analysis (Databricks + Delta Lake + Power BI)

End-to-end analytics project on **Los Angeles crime incidents** using a **Medallion (Bronze/Silver/Gold) pipeline** in Databricks, a **star schema** for reporting, and interactive **Power BI dashboards** for trends, hotspots, and crime patterns.

---

## Project Goals
- Build a reliable data pipeline for LA crime data (raw → cleaned → analytics-ready).
- Design a dimensional model (star schema) to support fast BI reporting.
- Answer key questions:
  - How does crime change over time (year/month/quarter)?
  - What are the most common crime types and where do they occur?
  - How do day/time/week factors affect crime frequency?
  - Which areas show higher crime density (hotspots)?

---

## Tech Stack
- **Databricks** (Spark, Delta Lake, Delta Live Tables optional)
- **Python (PySpark)** for ingestion + transformation
- **SQL** for modeling + validation
- **Power BI** (DirectQuery/Import) for dashboards
- **GitHub** for version control + documentation

---

## Dataset
- **Source:** LA Open Data (Los Angeles Police Department crime incidents)
- **Granularity:** Incident-level records (date/time, location, crime code/desc, area, weapon, victim info, status, etc.)
- **Note:** Dataset may include missing/invalid coordinates, inconsistent text fields, and schema drift over time.


