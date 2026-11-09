# Jayvik-Labs-Day-14

Day 14 – Nmap Network Scanning
Cybersecurity Learning Journey | Network Security Fundamentals

!Kali Linux !Tool !Domain !Learning !Status

1. Project Overview

This project focuses on understanding Nmap (Network Mapper), an open-source network discovery and security auditing tool widely used in cybersecurity.

Nmap helps security professionals identify active hosts, examine network ports, discover available services, and understand network configurations.

The objective of this practical learning activity is to develop foundational knowledge of network scanning, port states, service identification, and responsible security assessment.

Student Name: Nethra M
Assignment: Day 14
Topic: Nmap Network Scanning
Operating System: Kali Linux
Tool: Nmap (Network Mapper)
Environment: Oracle VirtualBox
Category: Network Security

2. Learning Objectives
Understand Nmap and its applications in cybersecurity.
Learn network discovery and port scanning concepts.
Identify open, closed, and filtered ports.
Understand basic Nmap command-line options.
Learn service and version detection concepts.
Understand how to save and document scan results.
Recognize the importance of cybersecurity scope and authorization.
Understand the difference between scanning and exploitation.
Develop responsible network assessment practices.
3. Nmap Fundamentals
What is Nmap?

Nmap stands for Network Mapper. It is an open-source tool used for network discovery and security auditing.

Primary Applications
Network host discovery.
Port identification.
Service identification.
Network inventory.
Basic security assessment.
Network configuration analysis.
Network Discovery

Network discovery is the process of identifying active devices and systems within an authorized network environment.

Port Scanning

Port scanning is a technique used to examine communication ports on a target system and determine their availability.

Port States
State	Description
Open	A service is accepting connections.
Closed	The system is reachable, but no service is listening on the port.
Filtered	Network filtering prevents Nmap from determining whether the port is open or closed.
4. Important Nmap Command Reference

The following commands demonstrate basic Nmap functionality in an authorized local laboratory environment.

Command	Description
nmap --version	Displays the installed Nmap version.
nmap --help	Displays command usage information.
nmap 127.0.0.1	Performs a basic scan of the local system.
nmap -p 22 127.0.0.1	Examines TCP port 22 on localhost.
nmap -sV 127.0.0.1	Attempts to identify services and versions on localhost.
nmap -oN scan-results.txt 127.0.0.1	Saves scan output in normal text format.
Understanding Common Options
Option	Function
-p	Specifies the port or port range.
-sV	Enables service and version detection.
-oN	Saves results in normal text format.
Example: Check Nmap Version
bash
nmap --version

Example: Scan Localhost
bash
nmap 127.0.0.1

Example: Identify a Local Service
bash
nmap -sV -p 22 127.0.0.1

Example: Save Scan Results
bash
nmap -oN scan-results.txt 127.0.0.1

5. Important Cybersecurity Concepts
Open Port vs Vulnerability

An open port does not automatically represent a security vulnerability. It indicates that a service is available for communication.

The security risk depends on the service, software version, configuration, authentication, and network exposure.

Scanning vs Exploitation
Scanning	Exploitation
Identifies available network services.	Attempts to take advantage of security weaknesses.
Collects information about ports.	May affect system security or functionality.
Supports security assessment.	Requires additional authorization and safeguards.
Cybersecurity Scope

Scope defines the approved systems, IP addresses, and activities included in a security assessment.

Authorization

Permission must be obtained before scanning systems that are not personally owned. All assessments must remain within the approved scope.

6. Practical Implementation

The practical exercises focus on understanding Nmap commands and reviewing network scan results within a local Kali Linux laboratory.

Practical Tasks
Verify Nmap installation.
Review Nmap command-line help.
Perform a localhost scan.
Examine selected local ports.
Understand service identification.
Save scan results into a text file.
Review and document the observations.
Expected Observations
Nmap displays information about scanned ports.
Port states help describe service availability.
Service detection may identify applications running on available ports.
Saved scan reports provide a record for further analysis.

Actual results depend on the services and network configuration of the local system.

7. Practical Evidence

Screenshots from the Kali Linux terminal should be included to demonstrate the commands executed.

text
screenshots/
├── nmap-version.png
├── localhost-scan.png
├── service-detection.png
└── scan-results.png

Screenshot Descriptions
Screenshot	Evidence
nmap-version.png	Nmap installation and version verification

<img width="629" height="419" alt="image" src="https://github.com/user-attachments/assets/96cc086f-86d8-4b23-ba88-88f3d8ea4236" />


localhost-scan.png	Localhost network scan

<img width="1246" height="714" alt="image" src="https://github.com/user-attachments/assets/49eefaed-91d3-4a23-a942-0610c1a78a8b" />


service-detection.png	Service and version detection

<img width="1400" height="764" alt="image" src="https://github.com/user-attachments/assets/bc6e097a-4994-4d96-aa19-2ec8a80102c6" />


scan-results.png	Saved scan output

<img width="748" height="607" alt="image" src="https://github.com/user-attachments/assets/527d18bc-e0e1-4d1a-9d5e-43759a8f2cc2" />


Replace these filenames with genuine screenshots captured from your own practical environment.

8. Key Learning Outcomes

Through this assignment, I developed an understanding of:

Nmap fundamentals and network discovery.
Port scanning and port-state identification.
Common Nmap command-line options.
Service and version detection.
Saving and documenting scan results.
Network assessment scope and authorization.
The distinction between scanning and exploitation.
Responsible cybersecurity testing practices.
