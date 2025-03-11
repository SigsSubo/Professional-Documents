# Professional-Documents

<details>
<summary>Vulnerability Assessment Report</summary>
</br>
**Date:** 11th March 2025

## Scenario

As a newly hired cybersecurity analyst for an e-commerce company, I have been tasked with conducting a vulnerability assessment of the company's database server. The company stores sensitive information on a remote database server that is accessible to employees working remotely from different locations around the world. However, the database has been open to the public since the company's launch three years ago, which is a serious security vulnerability.

This report aims to communicate the potential risks to decision-makers and propose ways to secure the database server, ensuring that access is restricted to authorized employees only.

## System Description

The server's hardware consists of a powerful CPU processor with 128GB of memory. It runs the latest version of the Linux operating system and hosts a MySQL database management system. The server is configured with a stable network connection using IPv4 addresses and interacts with other servers on the network. Security measures in place include SSL/TLS encrypted connections to secure data transmission.

### Key Points:
- **Server access** needs to be restricted to only remote employees.
- **Database** is currently open to the public, a crucial security issue that must be addressed.
- **Interacts with other servers** on the network, with **SSL/TLS encryption** in place to protect data.

## Scope

The scope of this vulnerability assessment focuses on evaluating the current access controls of the system. This assessment will be carried out over a three-month period, from March 2025 to June 2025, and will follow the NIST SP 800-30 Rev. 1 guidelines to analyze risks associated with the information system.

## Purpose

The database server is crucial for managing customer data, which is vital for the company's marketing operations. However, the current open access to the database exposes it to various vulnerabilities, including SQL injection and Man-In-The-Middle (MITM) attacks. Protecting the database is essential to ensure that regular marketing operations can continue without disruption.

## Risk Assessment

The table below outlines the potential threats and their corresponding risk scores:

| Threat Source | Threat Event | Likelihood | Severity | Risk |
|---------------|--------------|------------|----------|------|
| Hacker        | Obtain sensitive information via exfiltration | 3 | 3 | 9 |
| Hacker        | Conduct "man-in-the-middle” attacks | 3 | 3 | 9 |
| Employee      | Insider misuse/data theft | 2 | 3 | 6 |
| Customer      | Alter/Delete critical information | 1 | 3 | 3 |

### Risk Scoring:
- **Likelihood:** Likelihood of the event happening (1-5 scale)
- **Severity:** Potential impact if the event occurs (1-5 scale)
- **Risk:** The calculated risk, determined by multiplying likelihood and severity.

## Approach

The risks assessed consider the data storage and management procedures of the business. Potential threat sources and events were identified based on the open access permissions of the information system. The severity of potential incidents was evaluated with regard to their impact on daily operations, which rely heavily on the customer data stored in the database.

## Remediation Strategy

To mitigate the identified risks, the following measures should be implemented:

1. **Authentication and Authorization:**
   - Implement role-based access controls (RBAC) to ensure that only authorized users can access the database.
   - Enforce strong password policies and multi-factor authentication (MFA) for additional security.

2. **Encryption:**
   - Migrate from SSL to TLS encryption for data in transit to ensure stronger protection against eavesdropping and MITM attacks.

3. **IP Allow-Listing:**
   - Restrict database access to only known IP addresses from corporate offices and authorized employees to prevent unauthorized access from the public internet.

4. **Auditing and Monitoring:**
   - Set up auditing mechanisms to track access and usage of the database, ensuring accountability and detecting suspicious activity.

By implementing these remediation strategies, the company can significantly reduce the risk of unauthorized access and data breaches while ensuring that critical business operations continue without disruption.

## Conclusion

Securing the database server is essential for maintaining the confidentiality, integrity, and availability of customer data. The current open access to the database represents a significant vulnerability that must be addressed promptly. By following the recommended remediation strategy, the company can safeguard its operations and protect sensitive information from potential threats.

</details>
