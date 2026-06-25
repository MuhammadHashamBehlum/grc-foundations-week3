# Risk Assessment & Building a Risk Register (Likelihood × Impact)

**Prepared By:** Mohammad Hesham Wazir Ali Behlum  
**University:** Rochester Institute of Technology (RIT) Dubai  
**Program:** BS Cybersecurity  
**Internship:** Sohail Smart Solutions Summer Training Program 2026

---

## Introduction

The risk assessment is a core Governance, Risk, and Compliance (GRC) activity that is used to be able to evaluate the likelihood, as well as the possible impacts of the identified security risks. After identifying the security findings and mapping them to the relevant controls, the organizations must determine which of the risks require immediate attention and which can be monitored or even accepted.
One of the most widely used approaches in cybersecurity risk management is the qualitative risk assessment model, where the risk is calculated using:

**Risk Score = Likelihood × Impact**

This method is able to help organizations prioritize the remediation efforts, as well as allocate the resources effectively, and even communicate the risk levels to management in a clear and actionable manner.

The following risk register was developed based on the five security findings that were identified during the previous control mapping exercise.

---

## Risk Rating Matrix

### Likelihood Scale

| Rating | Value |
|----------|--------|
| Low | 1 |
| Medium | 2 |
| High | 3 |
| Very High | 4 |

### Impact Scale

| Rating | Value |
|----------|--------|
| Low | 1 |
| Medium | 2 |
| High | 3 |
| Critical | 4 |

### Risk Classification

| Score | Risk Rating |
|---------|-------------|
| 1–3 | Low |
| 4–6 | Medium |
| 8–11 | High |
| 12–16 | Critical |

---

## Risk Register

| Risk ID | Risk Description | Affected Asset | Likelihood | Impact | Score | Risk Rating | Treatment | Owner | Status |
|----------|-----------------|---------------|------------|---------|--------|-------------|-----------|---------|---------|
| R-001 | Missing the Multi-Factor Authentication may allow unauthorized access through the compromised credentials. | User Accounts & Authentication System | 4 | 4 | 16 | Critical | Mitigate | Security Administrator | Open |
| R-002 | Excessive user privileges could potentially lead to unauthorized access or even modification of the sensitive data. | ERP/CRM Application & Database | 3 | 4 | 12 | Critical | Mitigate | Identity & Access Management Team | Open |
| R-003 | Insufficient security logging and monitoring may delay the detection of malicious activity. | Security Monitoring Infrastructure | 3 | 3 | 9 | High | Mitigate | SOC Analyst | Open |
| R-004 | Malware or ransomware infection may disrupt the operations and impact the system availability. | Endpoints & Business Systems | 3 | 3 | 9 | High | Mitigate | IT Security Team | Open |
| R-005 | Lack of tested backup as well as recovery procedures may result in prolonged downtime or even data loss after an incident. | Business Data & Recovery Systems | 2 | 4 | 8 | High | Mitigate | Infrastructure Manager | Open |

---

## Risk Prioritization

| Priority Rank | Risk ID | Risk Rating | Score |
|---------------|----------|-------------|--------|
| 1 | R-001 | Critical | 16 |
| 2 | R-002 | Critical | 12 |
| 3 | R-003 | High | 9 |
| 4 | R-004 | High | 9 |
| 5 | R-005 | High | 8 |

---

## Justification of Highest-Risk Items

### 1. Missing Multi-Factor Authentication (R-001)

This risk had received the highest score because compromised credentials remain one of the most common causes of cybersecurity incidents. Password-only authentication is able to create a significant attack surface, which is particularly when the users reuse passwords or even fall victim to phishing attacks. If an attacker is able to gain access to a privileged account, they they may be able to view the sensitive information, as well as alter the system configurations, or even disrupt business operations. Implementing Multi-Factor Authentication (MFA) is able to significantly reduce the likelihood of unauthorized access and even aligns with the security best practices which are recommended by both NIST and ISO 27001.

### 2. Excessive User Privileges (R-002)

Excessive permissions is able to increase the risk of unauthorized access, along with the accidental data exposure, and even the insider threats. Users who have access beyond their operational requirements may unintentionally or even deliberately access the sensitive information that should be restricted. This can result in compliance violations and financial losses, as well as reputational damage. Applying the Role-Based Access Control (RBAC) and the Principle of Least Privilege is able to help that the ensure users only receive the permissions necessary to be able to perform their responsibilities.

---

## Conclusion

The risk assessment is able to transform the technical security findings into measurable business risks that the management can understand and even prioritize. Using a likelihood × impact methodology is able to allow the organizations to be able to focus on the remediation efforts on the most significant threats first. Based on this assessment, the weaknesses in authentication and access control are able to represent the highest-priority risks and should be addressed immediately to be able to reduce overall organizational exposure and strengthen the security posture.
