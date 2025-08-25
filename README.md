# Snowflake and dbt - Quickstart

*Production-ready dbt project on Snowflake with GitHub-based workflow.*


This is my first project on Snowflake using dbt Cloud 🎉 <br>
I followed the official guide [Quickstart for dbt and Snowflake](https://docs.getdbt.com/guides/snowflake?step=1) and [dbt Fundamentals course](https://learn.getdbt.com/learn/course/dbt-fundamentals), an excellent starting point for getting into the world of dbt.

## Overview
- **Warehouse:** Snowflake (RAW, ANALYTICS).
- **Transformations:** dbt Cloud (Studio + Orchestration).
- **Versioning:** GitHub PR workflow.
- **Goal:** Learn to build a reliable, documented, and tested analytics models.

## What This Project Does
- Connects **dbt Cloud** to a **Snowflake** data warehouse.
- Builds a layered data model using staging and marts.
- Applies version control with GitHub, practicing branching and pull request workflows.
- Introduces testing, documentation, and lineage tracking in dbt.

## Why I Did This
dbt has become a foundation of modern analytics engineering, bringing software development best practices into analytics and facilitating cross-functional collaboration. I wanted hands-on experience with the tools and workflows that data teams rely on today. This repository documents my learning path and demonstrates how I translate those concepts into a working project. ✨

## Lessons Learned
- Project structure: Learned to follow dbt’s best-practice model layers (src → stg → int → fact → dim) for clarity and maintainability.
- Data modeling: Practiced an agile, denormalized approach that takes advantage of modern cloud warehouse performance.
- Modularity: Used macros and ref() to manage dependencies between models, ensuring reusable, testable SQL.
- Analytics engineering mindset: Applied modular thinking from software engineering (version control, branching, environment setup) to analytics workflows.
- Source management: Configured sources.yml to centralize definitions, enable multi-table lineage, and check freshness with dbt source freshness.
- Scalability practices: Organized source YAML files by domain/schema for easier collaboration and long-term growth.

## Next Steps
 Complete [dbt Fundamentals](https://learn.getdbt.com/learn/course/dbt-fundamentals) for deeper coverage of testing, documentation, and deployment.
