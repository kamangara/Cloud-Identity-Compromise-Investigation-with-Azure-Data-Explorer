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
## Investigation Objectives

The investigation was conducted to answer the following key security questions:

1. **Identify the affected account**  
   Determine which user account was associated with the suspicious authentication activity.

2. **Identify the source of the suspicious activity**  
   Analyze IP addresses, geographic locations, and authentication patterns to identify anomalous access.

3. **Determine whether unauthorized access was successful**  
   Analyze failed and successful sign-in events to determine whether the suspicious authentication attempts resulted in account compromise.

4. **Investigate post-compromise activity**  
   Correlate sign-in and audit logs to determine what actions were performed after unauthorized access was obtained.

5. **Identify persistence and account changes**  
   Investigate authentication method changes, mailbox rules, external forwarding, application consent, and group membership modifications.

6. **Assess potential data exposure**  
   Determine whether mailbox content, SharePoint files, or other sensitive organizational resources were accessed.

7. **Determine the scope of the incident**  
   Investigate whether the suspicious IP address or infrastructure successfully authenticated to any additional Cloudora user accounts.

8. **Develop response recommendations**  
   Recommend appropriate containment, remediation, and verification actions based on the investigation findings.

