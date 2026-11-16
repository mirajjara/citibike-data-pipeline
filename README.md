# Citi Bike Data Pipeline

A collaborative data engineering project exploring NYC Citi Bike station availability over time.

## Goal

Build a historical dataset of Citi Bike station availability to identify patterns across stations and times of day.

## Tech Stack

- Python / PySpark
- Databricks / Delta Lake
- Apache Airflow
- dbt

## Current Progress

- Retrieved live station data from the Citi Bike GBFS API.
- Defined an explicit PySpark schema.
- Created a historical Delta table.
- Inserted the first snapshot of 2,519 stations using Delta `MERGE`.

## Next Steps

- Test duplicate prevention and data validation.
- Automate ingestion with Airflow.
- Build downstream transformations with dbt.

## Data Source

[Citi Bike GBFS API](https://gbfs.lyft.com/gbfs/2.3/bkn/gbfs.json)

**Status:** Work in progress.
