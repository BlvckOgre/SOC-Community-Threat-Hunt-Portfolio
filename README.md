# SOC Community Threat Hunt Portfolio

This repository is a curated portfolio of threat hunting exercises, detection logic, and investigations mapped to the MITRE ATT&CK framework. It has been developed as part of active participation in the MyDFIR SOC Community.

The purpose of this repository is to demonstrate practical SOC analyst capabilities, including threat detection, investigation methodology, and structured reporting.

## Repository Structure

- **/hunts/**  
  Contains detailed write-ups of completed threat hunts and mini-challenges.

- **/investigations/**  
  Includes comprehensive case reports refined through community feedback, supported by evidence such as screenshots and query outputs.

- **/kql/**  
  Houses reusable Kusto Query Language (KQL) queries and detection logic.

## Threat Hunt Template

Each threat hunt write-up follows a consistent structure:

- **Technique**  
  MITRE ATT&CK technique ID and name.

- **Summary**  
  Overview of the technique and how it is typically used by adversaries.

- **Detection Strategy**  
  Relevant log sources and indicators of suspicious activity.

- **KQL**  
  Queries used to identify the technique.

- **Triage and Investigation**  
  Initial analysis steps and escalation criteria.

- **Mitigation and Remediation**  
  Recommended defensive measures and response actions.

## Investigations

All investigation reports:

- Incorporate feedback from the MyDFIR SOC Community  
- Are documented as complete case reports within the `/investigations/` directory  
- Include supporting evidence such as screenshots, queries, and analytical findings  

This section highlights the ability to iteratively improve analysis, apply feedback, and produce well-documented investigations—core competencies for a SOC analyst.

## KQL Documentation Template

Each KQL entry includes:

- **Objective**  
  The purpose of the query.

- **Suspicious Indicators**  
  Key patterns or anomalies to look for in the results.

- **KQL Query**  
  The detection logic.

## Purpose

This repository serves as a professional portfolio demonstrating:

- Threat hunting proficiency  
- Development of detection logic using KQL  
- SOC triage and investigative skills  
- Application of the MITRE ATT&CK framework  

Over time, it provides a structured body of work that can be presented in professional settings to demonstrate analytical thinking, technical capability, and effective communication in a SOC environment.
