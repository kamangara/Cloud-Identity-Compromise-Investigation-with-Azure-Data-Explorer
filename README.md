# Cloud Identity Compromise Investigation with Azure Data Explorer

Hands-on cloud security investigation using Azure Data Explorer and KQL to detect suspicious authentication, confirm account compromise, analyze post-compromise activity, and assess the scope of the incident.

## Project Overview

This project demonstrates a hands-on investigation of a simulated cloud identity compromise using Azure Data Explorer (ADX) and Kusto Query Language (KQL).

The investigation analyzes sign-in and audit logs to identify suspicious authentication activity, determine whether an account was compromised, investigate actions performed after unauthorized access, and assess the scope of the incident.

The project follows a structured SOC investigation process from detection and analysis through incident findings and recommended containment and remediation actions.

## Project Scenario

Cloudora is a simulated cloud-based organization used for this security investigation.

Suspicious authentication activity was identified within the organization's sign-in logs. The investigation was conducted to determine whether the activity represented an account compromise, identify the affected account and source of the activity, and establish what occurred after access was gained.

The investigation also examines audit activity to identify actions performed after the compromise and checks the wider environment to determine whether additional user accounts were affected.
