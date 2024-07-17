# Intro to Cyber Threat Intelligence

## Introduction

Welcome to the Cyber Threat Intelligence (CTI) module, where we explore essential concepts in cyber threat intelligence and related frameworks. CTI is crucial for security analysts to investigate and report on adversary attacks, collaborating with organizational stakeholders and external communities.

### Cyber Threat Intelligence Module

This is the first room in a new Cyber Threat Intelligence module. The module will cover:

- **Threat Intelligence Tools:**
  - YARA
  - OpenCTI
  - MISP

### What is Cyber Threat Intelligence (CTI)?

CTI is evidence-based knowledge about adversaries, including their indicators, tactics, motivations, and actionable advice to protect critical assets and inform business decisions.

### Primary Goals:

- Identify who is attacking you.
- Understand their motives.
- Assess their capabilities.
- Identify relevant artifacts and indicators of compromise.

### Sources of Threat Intelligence:

- Internal sources
- Community sources (forums, telegram, websites, etc.)
- External sources

### Threat Intelligence Classifications:

- Strategic
- Technical
- Tactical
- Operational

## CTI Lifecycle

CTI is derived from a process that transforms raw data into actionable insights for incident response. This process follows a six-phase cycle:

### Direction

- Define assets requiring defense.
- Assess potential impact and interruptions.
- Identify data and intel sources.
- Determine necessary tools and resources for defense.

### Collection

- Begin collecting data and resources once objectives are defined, preferably through automated means.

### Processing

- Process includes logs, vulnerability information, malware samples, network traffic, and other data sources.
- Ensure data is extracted, organized, correlated, and presented visually for analysts.
- Security Information and Event Management (SIEM) tools facilitate data parsing.

### Analysis

- Investigate threat patterns and potential attacks.
- Develop action plans to prevent attacks and strengthen security posture.

### Dissemination

- Tailor intelligence reports for various stakeholders.
- Provide concise reports to C-suite executives on adversary trends, financial impacts, and strategic recommendations.
- Communicate threat indicators, adversary tactics, and tactical plans to technical teams.

### Feedback

- Analysts depend on stakeholder feedback to enhance the threat intelligence process.
- Regular feedback ensures ongoing interaction between teams, sustaining the lifecycle.

## CTI Standards and Frameworks

### MITRE ATT&CK

- Framework categorizes and describes tactics and techniques used by adversaries.
- Enables organizations to analyze and improve cybersecurity defenses.

### TAXII

- Trusted Automated eXchange of Indicator Information.
- Defines guidelines for securely exchanging threat intelligence.
- Supports Collection and Channel sharing models.

### STIX

- Structured Threat Information Expression.
- Specifies, captures, characterizes, and communicates standardized cyber threat information.
- Establishes clear relationships between threat data types.

### Cyber Kill Chain

- Framework detailing stages of a cyber attack.
- Includes reconnaissance, weaponization, delivery, exploitation, installation, command & control, and actions on objectives.

## Q & A

- **What does CTI stand for?**
  - Cyber Threat Intelligence

- **Where would IP addresses, hashes, and other threat artifacts be found?**
  - Technical Intel

- **What sharing models are supported by TAXII?**
  - Collection and Channel

- **When an adversary has obtained access to a network and is extracting data, what phase of the kill chain are they on?**
  - Actions on Objectives

## Practical Analysis

Access the task site [here](https://tryhackme.com/r/room/cyberthreatintel).

- **What was the source email address?**
  - Log dated Sept 10th 2020, 08:40:20:091

- **What was the name of the downloaded file?**
  - Log dated Sept 10th 2020, 08:41:35:123

- **What is the threat actor's IP?**
  - 91.185.23.222

- **Threat actor's email?**
  - vipivillain@badbank.com

- **User Victim Logged Account?**
  - Administrator

- **Victim Email Recipient?**
  - John Doe

- **Malware?**
  - flbpfuh.exe

- **After building the threat profile, what message do you receive?**
  - THM{REDACTED}
