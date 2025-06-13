# Transactions_Monitoring
This project presents a comprehensive demonstration of a transaction monitoring cycle using synthetically generated data. It simulates realistic datasets for customers, accounts, watchlists, transactions, and country risk profiles.

A set of six scenario-based rule functions is implemented to flag suspicious behavior by generating violation_ids for each customer. Following the detection phase, an alert generation mechanism aggregates violations based on predefined thresholds, assigning unique alert_ids to potential illicit activity.

Subsequently, a case management system assigns case_ids to alerts. If a customer has an existing case within the past three months, the system reuses the previous case_id to maintain continuity.

Additionally, data enrichment techniques and machine learning models are developed to enhance the effectiveness and intelligence of the monitoring system.
