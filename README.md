# MTA Ridership Recovery & Strategic Diagnostic

This project provides a comprehensive, high-fidelity analysis of New York City’s MTA ridership recovery, covering over 1,700 days of data from the onset of the pandemic in March 2020 through October 2024. By deploying a synchronized analytical stack of **Python, SQL, Tableau, and Excel**, I established a cross-validated "single source of truth." This rigorous methodology ensures that every insight—from recovery velocity to structural shifts in traffic share—remains perfectly consistent across all technical environments.

## Technical Execution & Methodology

To ensure absolute data integrity, I addressed four core business questions in parallel across all platforms, utilizing the unique strengths of each while cross-verifying the mathematical outputs.

* **Python (Predictive & Statistical Engine):** Engineered a robust pipeline to process daily ridership volumes across seven transit services. I utilized Python for time-series analysis, calculating recovery velocities (e.g., Access-A-Ride at 0.069 pp/day) and projecting full recovery timelines using statistical modeling.
* **SQL (Relational Infrastructure):** Developed a specialized schema to transform raw transit data into an audit-ready relational database. Through complex CTEs and window functions, I quantified the precise "drop-off" points and recovery percentages for each service branch, providing a high-performance backend for the study.
* **Tableau (Visual Intelligence):** Built a high-fidelity interactive workbook to visualize recovery trends and structural shifts. The dashboards focus on the "pp" (percentage point) changes in traffic share, highlighting the transition from public transit to private vehicle usage over time.
* **Excel (Executive Diagnostic):** Structured the final reporting layer, creating an executive dashboard that translates technical recovery rates into business-ready status indicators (e.g., "Recovered" vs. "Recovering").

## Core Analytical Pillars

The analysis yielded a unified set of strategic findings across all platforms:

* **Structural Traffic Shifts:** Identified a permanent shift in NYC's transit landscape, with **Bridges & Tunnels** gaining the most significant traffic share (+3.7 pp) while **Buses** experienced the most substantial long-term loss.
* **Recovery Variance:** Isolated the recovery leaders, specifically **Access-A-Ride (126%)** and **Bridges & Tunnels (103%)**, contrasting them against services like the **Staten Island Railway**, which experienced a total 100% drop-off at its nadir.
* **Velocity & Projection:** Calculated that all major services are on a trajectory to reach pre-pandemic levels by **February 2025**, assuming current recovery velocities remain stable.
* **Data Integrity:** Validated the upgraded MTA methodology (February 2023) across the dataset to ensure baseline comparisons for non-holiday weekdays and weekends were statistically sound.

## Strategic Impact

This project serves as a strategic roadmap for understanding post-pandemic urban mobility. By bridging the gap between raw transit data engineering and high-level behavioral analysis, the framework provides the clarity needed to forecast service demand and optimize resource allocation across North America’s largest transportation network.

---

