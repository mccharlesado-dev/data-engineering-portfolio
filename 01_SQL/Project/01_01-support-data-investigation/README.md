
# Missing Customer Orders Investigation

## Scenario

A customer reports that orders from yesterday are missing from the reporting dashboard.

## Objective

Investigate the data pipeline and determine whether the issue came from:

- Source data
- ETL load
- Database transformation
- Reporting query
- Data quality issue

## Skills Demonstrated

- SQL joins
- Date filtering
- Aggregate functions
- CTEs
- Data validation
- Root cause analysis
- Customer-facing incident documentation

## Investigation Summary

The reporting dashboard showed fewer orders than expected because some records failed validation during the ETL process due to missing customer IDs.

## Repository Files

- `01_create_tables.sql` creates the sample database tables.
- `02_insert_sample_data.sql` inserts valid and invalid order records.
- `03_investigation_queries.sql` contains the investigation process.
- `04_root_cause_and_fix.md` documents the incident, root cause, fix, and prevention plan.
