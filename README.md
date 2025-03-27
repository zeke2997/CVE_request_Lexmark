# Vulnerability Overview

A critical Improper Access Control (CWE-284) vulnerability has been identified in multiple Lexmark XM-series printer models (including XM5365 and XM7355). The affected devices expose web interfaces that lack authentication controls, enabling unauthenticated attackers to remotely execute malicious actions. Exploitation of this vulnerability could lead to unauthorized firmware modification, sensitive data leakage, and full compromise of printer functionality.
# POC:
## Improper Access Control
![poc1.png](poc1.png)
## Malicious Firmware Upload
Attackers may upload custom or tampered firmware to the printer, enabling persistent control over the device. This could facilitate further attacks on the corporate network or disrupt printer operations.
![poc2.png](poc2.png)
## Sensitive Data Exposure
Extract internal employee information, including names, email addresses, and fax numbers, stored on the device. This data could be leveraged for social engineering or targeted phishing campaigns.
![poc3.png](poc3.png)
## Printer Configuration Manipulation
Redirect print/scan jobs to attacker-controlled destinations
![poc4.png](poc4.png)