# WLAN and Mobile Security Plan

## Objective

Developed a comprehensive WLAN and Mobile Security Plan as part of a college course on emerging technologies in cybersecurity. Given a scenario, the task involved critically assessing a company's existing WLAN setup, identifying vulnerabilities, and advising on security upgrades backed by pertinent regulations. Additionally, mobile device vulnerabilities were addressed with recommended mitigation strategies and preventative measures.

### Skills Learned

- Vulnerability Assessment: Identified and analyzed vulnerabilities in WLAN and mobile device environments.
- Mitigation Strategies: Developed and proposed strategies to mitigate identified vulnerabilities.
- Preventative Measures Implementation: Recommended preventative measures to improve overall security..

### Tools Used

- Security Information and Event Management (SIEM) system for log ingestion and analysis.
- Network analysis tools (such as Wireshark) for capturing and examining network traffic.
- Telemetry generation tools to create realistic network traffic and attack scenarios.

## Steps

Identified WLAN Vulnerabilities:

- Observation: A wireless access point (WAP) was located in a large back patio area for employee use, extending signals beyond building walls.
  - Vulnerability: Susceptible to evil twin attacks where attackers set up a fake Wi-Fi access point to intercept data.
- Observation: The company hosted website servers in-house without using a VPN.
  - Vulnerability: Exposed to man-in-the-middle attacks due to unencrypted data transmission between the main office and the servers.

Identified Mobile Device Vulnerabilities:

- Observation: Company laptops used by traveling account reps lacked security controls.
  - Vulnerability: No encryption, biometric authenticators, or password protection, making them vulnerable to unauthorized access.
- Observation: Difficulty in ensuring timely security updates for mobile devices.
  - Vulnerability: Devices more susceptible to attacks exploiting known vulnerabilities due to lack of updates.

Proposed Mitigation Strategies:

- WLAN: Change default passwords on all access points, enable WPA-2 encryption, increase physical security, use MAC filtering, and disable SSID broadcasting.
- VPN: Implement a VPN to encrypt data transmissions between the main office and servers, and use multi-factor authentication for additional security.

Mobile Device Mitigation Strategies:
- Implement screen time-out and lock policies, complex password requirements, and multi-factor authentication for company-owned devices.
- Use MDM software to manage and remotely wipe lost devices, and enforce automatic software updates.

Recommended Preventative Measures:
- WLAN: Regular security and network checks per NIST guidelines and implementation of an IDPS.
- Mobile Devices: Use MDM and Mobile Application Management (MAM) solutions to manage and secure devices and applications.

Regulatory Justifications:
- Compliance with the Sarbanes-Oxley Act (SOX) for financial data accuracy.
- Adherence to the Payment Card Industry Data Security Standard (PCI DSS) for maintaining a secure network.

## Summary and Findings (From Scenario) 

WLAN Vulnerabilities

- WAP in Back Patio Area:
  - Vulnerability: Susceptible to evil twin attacks.
  - Mitigation: Change default passwords, enable WPA-2, increase physical security, use MAC filtering, and disable SSID broadcasting.
- In-House Website Servers:
  - Vulnerability: Lack of VPN leading to man-in-the-middle attacks.
  - Mitigation: Implement a VPN and multi-factor authentication.


Mobile Device Vulnerabilities
- Traveling Account Reps:
  - Vulnerability: Lack of security controls on company laptops.
  - Mitigation: Implement screen time-out, complex passwords, multi-factor authentication, and full disk encryption.

Software Updates:
  - Vulnerability: Difficulty ensuring timely security updates.
  - Mitigation: Enforce automatic updates and manage updates centrally.

Recommended Preventative Measures
- For WLAN:
  - Regular security checks per NIST guidelines and implementation of an IDPS.
- For Mobile Devices:
  - Use of MDM and MAM solutions to manage and secure devices and applications.
