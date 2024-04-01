# Security Compliance and Identity Management Project
## Introduction
This project showcases a comprehensive investigation into security compliance and identity management within a cloud environment, utilizing tools and platforms such as Microsoft Sentinel, Microsoft 365 Defender, and Azure Active Directory. The project is structured into a series of investigations carried out over a single day, focusing on detecting, analyzing, and mitigating cybersecurity threats and vulnerabilities.

## Project Overview
Morning Investigation: Leaked File & User Behavior Analysis
Objective: Identify and investigate a leaked Excel document.
Tools Used: Microsoft Sentinel and Microsoft 365 Defender.
Findings: Suspicious activities associated with user "Amari" and execution of a potentially malicious file named Patch.exe.
Afternoon Investigation: Compliance Policies & Device Analysis
Objective: Establish compliance policies and investigate suspicious device activities.
Approach: Implement Zero Trust policies and automatic labeling. Analyze device pc105 for malicious file activities.
Outcome: Configured simulation mode for compliance policies and identified malicious executable files linked to an external IP address.
Evening Investigation: Identity Protection & Communication Compliance
Objective: Enhance Azure AD Identity Protection and investigate suspicious communications.
Actions: Enabled User Risk Policy and Sign-In Risk Policy. Investigated sign-in logs and mailbox communications for users "Angel" and "Amari".
Results: No compromised account found for Angel, but suspicious emails were detected in deleted items.
## Methodology
Leak Detection and Analysis: Utilized Sentinel to search for leaked files and Defender for investigating associated incidents.
User Behavior and Device Analysis: Conducted thorough investigations into user activities and device-level threats.
Compliance and Risk Management: Implemented compliance policies and risk management strategies focusing on Zero Trust principles and identity protection.
Communication Surveillance: Searched internal communications for mentions of suspicious IP addresses and investigated compliance breaches.
## Findings
The investigations led to the discovery of various security issues, including:

Execution of a suspicious file Patch.exe.
Remote execution attempts via curl commands.
Usage of meterpreter tool and PowerShell to manipulate devices.
Leaked documents and suspicious internal communications.
## Recommendations
Enhance Monitoring: Improve real-time monitoring and alerting for suspicious activities associated with file access and user behavior.
Implement Strict Compliance Policies: Use Zero Trust and auto-labeling policies to restrict unauthorized access and manage data leakage effectively.
Strengthen Identity Protection: Activate Azure AD Identity Protection policies to safeguard against compromised identities.
Regular Audits: Conduct regular audits of device logs, sign-in activities, and internal communications to detect and mitigate potential threats promptly.
## Conclusion
The project underscores the importance of a holistic approach to security compliance and identity management in cloud environments. By integrating advanced security tools and adopting stringent compliance policies, organizations can significantly enhance their cybersecurity posture.
