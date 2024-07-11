# Try Hack Me: Threat Intelligence Tools

Explore different OSINT tools used to conduct security threat assessments and investigations.


---

## Task 1: Room Outline

This room will cover the concepts of Threat Intelligence and various open-source tools that are useful. The learning objectives include:

- Understanding the basics of threat intelligence & its classifications.
- Using UrlScan.io to scan for malicious URLs.
- Using Abuse.ch to track malware and botnet indicators.
- Investigating phishing emails using PhishTool.
- Using Cisco's Talos Intelligence platform for intel gathering.

---

## Task 2: Threat Intelligence

### Strategic Intel
High-level intel that looks into the organization’s threat landscape and maps out the risk areas based on trends, patterns, and emerging threats that may impact business decisions.

### Technical Intel
Looks into evidence and artifacts of attack used by an adversary. Incident Response teams can use this intel to create a baseline attack surface to analyze and develop defense mechanisms.

### Tactical Intel
Assesses adversaries' tactics, techniques, and procedures (TTPs). This intel can strengthen security controls and address vulnerabilities through real-time investigations.

### Operational Intel
Looks into an adversary's specific motives and intent to perform an attack. Security teams may use this intel to understand the critical assets available in the organization (people, processes, and technologies) that may be targeted.

---

## Task 3: UrlScan.io

### Scenario
You have been tasked to perform a scan on TryHackMe's domain. The results obtained are displayed in the image below. Use the details on the image to answer the questions:

1. **What was TryHackMe's Cisco Umbrella Rank based on the screenshot?**
   - 345612

2. **How many domains did UrlScan.io identify on the screenshot?**
   - 13

3. **What was the main domain registrar listed on the screenshot?**
   - NAMECHEAP INC

4. **What was the main IP address identified for TryHackMe on the screenshot?**
   - 2606:4700:10::ac43:1b0a

---

## Task 4: Abuse.ch

Abuse.ch is a research project hosted by the Institute for Cybersecurity and Engineering at the Bern University of Applied Sciences in Switzerland. It was developed to identify and track malware and botnets through several operational platforms developed under the project. These platforms are:

- **Malware Bazaar**: A resource for sharing malware samples.
- **Feodo Tracker**: A resource used to track botnet command and control (C2) infrastructure linked with Emotet, Dridex, and TrickBot.
- **SSL Blacklist**: A resource for collecting and providing a blocklist for malicious SSL certificates and JA3/JA3s fingerprints.
- **URL Haus**: A resource for sharing malware distribution sites.
- **Threat Fox**: A resource for sharing indicators of compromise (IOCs).

### Questions

1. **The IOC 212.192.246.30:5555 is identified under which malware alias name on ThreatFox?**
   - Katana

2. **Which malware is associated with the JA3 Fingerprint 51c64c77e60f3980eea90869b68c58a8 on SSL Blacklist?**
   - Dridex

3. **From the statistics page on URLHaus, what malware-hosting network has the ASN number AS14061?**
   - DIGITALOCEAN-ASN

4. **Which country is the botnet IP address 178.134.47.166 associated with according to FeodoTracker?**
   - Georgia

---

## Task 5: Phish Tool

### Analysis Tab

Once uploaded, we are presented with the details of our email for a more in-depth look. Here, we have the following tabs:

- **Headers**: Provides the routing information of the email, such as source and destination email addresses, originating IP and DNS addresses, and timestamp.
- **Received Lines**: Details on the email traversal process across various SMTP servers for tracing purposes.
- **X-headers**: These are extension headers added by the recipient mailbox to provide additional information about the email.
- **Security**: Details on email security frameworks and policies such as Sender Policy Framework (SPF), DomainKeys Identified Mail (DKIM), and Domain-based Message Authentication, Reporting, and Conformance (DMARC).
- **Attachments**: Lists any file attachments found in the email.
- **Message URLs**: Associated external URLs found in the email will be found here.

### Questions

1. **What social media platform is the attacker trying to pose as in the email?**
   - LinkedIn

2. **What is the sender's email address?**
   - darkabutla@sc500.whpservers.com

3. **What is the recipient's email address?**
   - cabbagecare@hotsmail.com

4. **What is the Originating IP address? Defang the IP address.**
   - 204[.]93[.]183[.]11

5. **How many hops did the email go through to get to the recipient?**
   - 4

---

## Task 6: Cisco Talos Intelligence

Cisco Talos encompasses six key teams:

- **Threat Intelligence & Interdiction**: Quick correlation and tracking of threats provide a means to turn simple IOCs into context-rich intel.
- **Detection Research**: Vulnerability and malware analysis is performed to create rules and content for threat detection.
- **Engineering & Development**: Provides the maintenance support for the inspection engines and keeps them up-to-date to identify and triage emerging threats.
- **Vulnerability Research & Discovery**: Working with service and software vendors to develop repeatable means of identifying and reporting security vulnerabilities.
- **Communities**: Maintains the image of the team and the open-source solutions.
- **Global Outreach**: Disseminates intelligence to customers and the security community through publications.

### Questions

1. **What is the listed domain of the IP address from the previous task?**
   - scnet.net

2. **What is the customer name of the IP address?**
   - Complete Web Reviews

---

## Task 7: Scenario 1

### Scenario

You are a SOC Analyst. Several suspicious emails have been forwarded to you from other coworkers. You must obtain details from each email to triage the incidents reported.

### Task

Use the tools and knowledge discussed throughout this room (or use your resources) to help you analyze Email2.eml found on the VM attached to Task 5 and use the information to answer the questions.

### Questions

1. **According to Email2.eml, what is the recipient's email address?**
   - chris.lyons@supercarcenterdetroit.com

2. **From Talos Intelligence, the attached file can also be identified by the Detection Alias that starts with an H...**
   - HIDDENEXT/Worm.Gen

---

## Task 8: Scenario 2

### Scenario

You are a SOC Analyst. Several suspicious emails have been forwarded to you from other coworkers. You must obtain details from each email to triage the incidents reported.

### Task

Use the tools and knowledge discussed throughout this room (or use your resources) to help you analyze Email3.eml found on the VM attached to Task 5 and use the information to answer the questions.

### Questions

1. **What is the name of the attachment on Email3.eml?**
   - Sales_Receipt 5606.xls

2. **What malware family is associated with the attachment on Email3.eml?**
   - Dridex

---

**The End**

By: Jason
