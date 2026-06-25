# Mapping Security Findings to Controls: From Vulnerability to Compliance Gap

**Prepared By:** Mohammad Hesham Wazir Ali Behlum  
**University:** Rochester Institute of Technology (RIT) Dubai  
**Program:** BS Cybersecurity  
**Internship:** Sohail Smart Solutions Summer Training Program 2026

## Introduction

A key responsibility of a Governance, Risk, and Compliance (GRC) analyst is translating the technical security findings into both business and compliance language. Security vulnerabilities are not only technical issues; they often tend to indicate that the required security controls are missing and improperly implemented, or even operating ineffectively.

The purpose of this exercise is to be able to demonstrate how the common web application vulnerabilities can be mapped to the applicable NIST 800-53 security controls.


## Control Mapping Table

| Security Finding | NIST 800-53 Control ID(s) | Justification | Compliance Gap Statement |
|-----------------|--------------------------|---------------|--------------------------|
| The SQL Injection vulnerability is able to allow the unsanitized user input to be able to interact with the backend database queries. | SI-10, SI-11 | The User-supplied input is not properly validated before processing. | The application does not adequately validate input data, which is able to increase the risk of unauthorized database access as well as data manipulation. |
| The Broken Access Control / IDOR is able to allow the users to be able to access the records belonging to other users by modifying the object identifiers. | AC-3, AC-6 | The access restrictions are not consistently enforced on the protected resources. | The application fails to be able to enforce authorization checks, which is able to allow the users to access information beyond their assigned permissions. |
| Weak Authentication due to simple passwords and lack of Multi-Factor Authentication (MFA). | IA-2, IA-5 | Authentication mechanisms do not provide sufficient protection against credential compromise. | User authentication controls are insufficient to reduce the risk of unauthorized account access. |
| Any missing or insufficient audit logging for critical user and administrative actions. | AU-2, AU-6, AU-12 | The security-relevant activities are not consistently logged or even reviewed. | The organization tends to lack adequate logging and monitoring capabilities to be able to support incident detection and investigation. |
| There is Sensitive Data Exposure through unencrypted transmission or even the improper protection of confidential information. | SC-8, SC-28 | Sensitive information is not adequately protected during the storage or transmission. | The Data protection controls are insufficient to be able to ensure the confidentiality of sensitive information. |
