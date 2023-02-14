# Challenge 06 - Log Queries with KQL and Grafana

[< Previous Challenge](./Challenge-05.md) - **[Home](../README.md)** - [Next Challenge >](./Challenge-07.md)

## Introduction

The Kusto Query Language (KQL) KQL is a query language used in Log Analytics and Azure Monitor to retrieve and analyze data. In this challenge you will write and save queries and run them against your Log Analytics Workspace data.

## Description

Write a performance query that renders a time chart for the last 4 hours for both of the Web Servers and the SQL Server for the following perf metrics. Save each query to your favorites.
* Processor Utilization: Processor / % Processor Time
* Memory Utilization: Memory / % Committed Bytes In Use
* Disk Utilization (IO): Disk Reads/sec and Disk Writes/sec
* Disk Utilisation (MB/GB): Disk Free Space (% or MB)
* Create a heartbeat query for Web Servers and SQL Server
* Write a performance query that renders a time chart for the last hour of the max percentage CPU usage of the AKS Cluster nodes

* Bonus Challenge if you completed the VM and Containers Challenges
- Combine infrastructure and application logs to create a single timeseries chart that includes:
  - CPU usage from the node in your AKS cluster hosting the eshoponweb app
  - Duration of page views on your eshoponweb app hosted on the cluster
  - Save each query to your favorites.

Bonus question:
How can we save our log queries and share them across multiple workspaces?

## Success Criteria
* Display results
- Show the above 3 charts
- Show the saved queries

## Learning Resources
- [Getting started with Kusto](https://docs.microsoft.com/en-us/azure/data-explorer/kusto/concepts/)
* [Log queries in Azure Monitor](https://docs.microsoft.com/en-us/azure/azure-monitor/logs/log-query-overview)
* [Overview of queries](https://docs.microsoft.com/en-us/azure/data-explorer/kusto/query/)
* [Query best practises](https://docs.microsoft.com/en-us/azure/data-explorer/kusto/query/best-practices)
* [Query operators](https://docs.microsoft.com/en-us/azure/data-explorer/kusto/query/queries)
* [Telemetry correlation in Application Insights](https://docs.microsoft.com/en-us/azure/azure-monitor/app/correlation)
* [Query Packs in Azure Monitor](https://learn.microsoft.com/en-us/azure/azure-monitor/logs/query-packs(
