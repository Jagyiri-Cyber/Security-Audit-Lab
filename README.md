# Security Audit Lab - Botium Toys

## Overview

This project involves conducting an internal security audit for a fictional company, Botium Toys. The audit is part of the Google Cybersecurity Training and aims to identify and mitigate potential risks, threats, or vulnerabilities to the company's critical assets. The project demonstrates skills in compliance and control assessment, with a focus on the NIST Cybersecurity Framework (NIST CSF).

## Project Structure

### 1. Scenario
This scenario is based on a fictional company:

Botium Toys is a small U.S. business that develops and sells toys. The business has a single physical location, which serves as their main office, a storefront, and warehouse for their products. However, Botium Toy’s online presence has grown, attracting customers in the U.S. and abroad. As a result, their information technology (IT) department is under increasing pressure to support their online market worldwide. 

The manager of the IT department has decided that an internal IT audit needs to be conducted. She's worried about maintaining compliance and business operations as the company grows without a clear plan. She believes an internal audit can help better secure the company’s infrastructure and help them identify and mitigate potential risks, threats, or vulnerabilities to critical assets. The manager is also interested in ensuring that they comply with regulations related to internally processing and accepting online payments and conducting business in the European Union (E.U.).   

The IT manager starts by implementing the National Institute of Standards and Technology Cybersecurity Framework (NIST CSF), establishing an audit scope and goals, listing assets currently managed by the IT department, and completing a risk assessment. The goal of the audit is to provide an overview of the risks and/or fines that the company might experience due to the current state of their security posture.

Your task is to review the IT manager’s scope, goals, and risk assessment report. Then, perform an internal audit by completing a controls and compliance checklist. 

### 2. Scope and Goals
- **Scope of the audit**: The scope of this audit is defined as the entire security program at Botium Toys. This includes their assets like employee equipment and devices, their internal network, and their systems. You will need to review the assets Botium Toys has and the controls and compliance practices they have in place.

- **Goals**: Assess existing assets and complete the controls and compliance checklist to determine which controls and compliance best practices that need to be implemented to  improve Botium Toys’ security posture.

### 3. Current assets
Assets managed by the IT Department include: 
- On-premises equipment for in-office business needs  
- Employee equipment: end-user devices (desktops/laptops, smartphones), remote workstations, headsets, cables, keyboards, mice, docking stations, surveillance cameras, etc.
- Storefront products available for retail sale on site and online; stored in the company’s adjoining warehouse
- Management of systems, software, and services: accounting, telecommunication, database, security, ecommerce, and inventory management
- Internet access
- Internal network
- Data retention and storage
- Legacy system maintenance: end-of-life systems that require human monitoring 


### 4. Risk Assessment
- **Detailed risk assessment report.**
  - **Risk description**: Currently, there is inadequate management of assets. Additionally, Botium Toys does not have all of the proper controls in place and may not be fully compliant with U.S. and international regulations and standards.
    
  - **Control best practices**: The first of the five functions of the NIST CSF is Identify. Botium Toys will need to dedicate resources to identify assets so they can appropriately manage them. Additionally, they will need to classify existing assets and determine the impact of the loss of existing assets, including systems, on business continuity.
    
  - **Risk score**: On a scale of 1 to 10, the risk score is 8, which is fairly high. This is due to a lack of controls and adherence to compliance best practices.
    
**Additional comments**: The potential impact from the loss of an asset is rated as medium, because the IT department does not know which assets would be at risk. The risk to assets or fines from governing bodies is high because Botium Toys does not have all of the necessary controls in place and is not fully adhering to best practices related to compliance regulations that keep critical data private/secure. Review the following bullet points for specific details:

- Currently, all Botium Toys employees have access to internally stored data and may be able to access cardholder data and customers’ PII/SPII.
-- Encryption is not currently used to ensure confidentiality of customers’ credit card information that is accepted, processed, transmitted, and stored locally in the company’s internal database. 
- Access controls pertaining to least privilege and separation of duties have not been implemented.
- The IT department has ensured availability and integrated controls to ensure data integrity.
- The IT department has a firewall that blocks traffic based on an appropriately defined set of security rules.
- Antivirus software is installed and monitored regularly by the IT department. 
- The IT department has not installed an intrusion detection system (IDS).
- There are no disaster recovery plans currently in place, and the company does not have backups of critical data. 
- The IT department has established a plan to notify E.U. customers within 72 hours if there is a security breach. Additionally, privacy policies, procedures, and processes have been developed and are enforced among IT department members/other employees, to properly document and maintain data.
- Although a password policy exists, its requirements are nominal and not in line with current minimum password complexity requirements (e.g., at least eight characters, a combination of letters and at least one number; special characters). 
- There is no centralized password management system that enforces the password policy’s minimum requirements, which sometimes affects productivity when employees/vendors submit a ticket to the IT department to recover or reset a password.
- While legacy systems are monitored and maintained, there is no regular schedule in place for these tasks and intervention methods are unclear.
- The store’s physical location, which includes Botium Toys’ main offices, store front, and warehouse of products, has sufficient locks, up-to-date closed-circuit television (CCTV) surveillance, as well as functioning fire detection and prevention systems.

### 5. Controls and Compliance Checklist

#### Controls Assessment Checklist
| Control | Yes/No | Explanation |
| --- | --- | --- |
| **Least Privilege** | No | Currently, all employees have access to customer data; privileges need to be limited to reduce the risk of a breach |
| **Disaster Recovery Plans** | No | There are no disaster recovery plans in place. These need to be implemented to ensure business continuity. |
| **Password Policies** | No | Employee password requirements are minimal, which could allow a threat actor to more easily access secure data/other assets via employee work equipment/the internal network.

 |
| **Separation of Duties** | No | Needs to be implemented to reduce the possibility of fraud/access to critical data, since the company CEO currently runs day-to-day operations and manages the payroll. |
| **Firewall** | Yes | The existing firewall blocks traffic based on an appropriately defined set of security rules. |
| **Intrusion Detection System (IDS)** | No | The IT department needs an IDS in place to help identify possible intrusions by threat actors. |
| **Backups** | No | The IT department needs to have backups of critical data, in the case of a breach, to ensure business continuity. |
| **Antivirus Software** | Yes | Antivirus software is installed and monitored regularly by the IT department. |
| **Manual Monitoring for Legacy Systems** | No | The list of assets notes the use of legacy systems. The risk assessment indicates that these systems are monitored and maintained, but there is not a regular schedule in place for this task and procedures/ policies related to intervention are unclear, which could place these systems at risk of a breach.  |
| **Encryption** | No | Explanation |
| **Password Management System** | No | Explanation |
| **Locks** | Yes | Explanation |
| **CCTV Surveillance** | Yes | Explanation |
| **Fire Detection/Prevention** | Yes | Explanation |

#### Compliance Checklist

##### PCI DSS
| Best Practice | Yes/No | Explanation |
| --- | --- | --- |
| **Authorized Users** | No | Explanation |
| **Secure Credit Card Information** | No | Explanation |
| **Data Encryption Procedures** | No | Explanation |
| **Secure Password Management** | No | Explanation |

##### GDPR
| Best Practice | Yes/No | Explanation |
| --- | --- | --- |
| **EU Customer Data Security** | No | Explanation |
| **72-Hour Breach Notification** | Yes | Explanation |
| **Data Classification and Inventory** | No | Explanation |
| **Privacy Policies** | Yes | Explanation |

##### SOC Type 1, Type 2
| Best Practice | Yes/No | Explanation |
| --- | --- | --- |
| **User Access Policies** | No | Explanation |
| **PII/SPII Confidentiality** | No | Explanation |
| **Data Integrity** | Yes | Explanation |
| **Data Availability** | No | Explanation |

### 6. Recommendations
- Suggestions for implementing controls and compliance best practices.
- Importance of improving Botium Toys' security posture.

### 7. Conclusion
- Summary of findings.
- The importance of regular security audits.

## Files and Directories

- **README.md**: Contains the project overview, scenario, scope and goals, and conclusions.
- **RiskAssessment.md**: Detailed risk assessment report.
- **ControlsComplianceChecklist.md**: Controls and compliance checklist with explanations.
- **Recommendations.md**: Recommendations for improving security posture.
