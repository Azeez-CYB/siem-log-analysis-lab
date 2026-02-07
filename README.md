# SIEM Log Analysis Lab (Elastic Stack)

## Overview
This project demonstrates a basic Security Operations Centre (SOC) workflow using the Elastic Stack. The lab focuses on log ingestion, investigation, visualisation, and incident reporting.

## Objectives
- Analyse web traffic logs using a SIEM
- Identify suspicious patterns and high-volume source IPs
- Build dashboards to visualise traffic trends
- Document findings in a security incident report

## Tools & Technologies
- Elasticsearch
- Kibana
- Docker
- Sample Web Logs

## Investigation Process
- Logs were analysed using Kibana Discover
- Fields such as source IP address and timestamps were reviewed
- Visualisations were created to identify traffic spikes and repeated activity
- A dashboard was built to summarise findings

## Findings
Analysis revealed repeated requests from specific IP addresses over short periods of time, which may indicate automated scanning or suspicious behaviour.

## Screenshots
See included screenshots demonstrating:
- Log analysis in Discover
- Source IP distribution
- Traffic trends dashboard

## Skills Demonstrated
- SIEM log analysis
- SOC investigation workflow
- Dashboard creation
- Incident documentation
