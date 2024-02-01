# Botium-Toys-Security-Audit

Review Botium's IT manager’s scope, goals, and risk assessment report. Then, perform an internal audit by completing a controls and compliance checklist. 

## Table of contents

1. [Introduction](#introduction)
2. [Controls Assessment](#control-assessment)
3. [Botium's Internal Security Audit](#workflow)
4. [Assessment Checklist](#checklist)
5. [Control Categories Assessment](#assessment)
6. [Recommendation/Summary](#summary)

----------
## Introduction <a name="introduction">

Botium Toys is a small U.S. business that develops and sells toys. The business has a single physical location, which serves as their main office, a storefront, and warehouse for their products. However, Botium Toy’s online presence has grown, attracting customers in the U.S. and abroad. As a result, their information technology (IT) department is under increasing pressure to support their online market worldwide. 

The manager of the IT department has decided that an internal IT audit needs to be conducted. She expresses concerns about not having a solidified plan of action to ensure business continuity and compliance, as the business grows. She believes an internal audit can help better secure the company’s infrastructure and help them identify and mitigate potential risks, threats, or vulnerabilities to critical assets. The manager is also interested in ensuring that they comply with regulations related to internally processing and accepting online payments and conducting business in the European Union (E.U.).   

The IT manager starts by implementing the National Institute of Standards and Technology Cybersecurity Framework (NIST CSF), establishing an audit scope and goals, listing assets currently managed by the IT department, and completing a risk assessment. The goal of the audit is to provide an overview of the risks and/or fines that the company might experience due to the current state of their security posture.

**Scope**: Review Botium Toys' internal Audit that assesses the entire security program at Botium Toys such as the following:
- Current user permissions set in the following systems: accounting, end point
    detection, firewalls, intrusion detection system, security information and event
    management (SIEM) tool.
- Current implemented controls in the following systems: accounting, end point
    detection, firewalls, intrusion detection system, Security Information and Event
    Management (SIEM) tool.
- Current procedures and protocols set for the following systems: accounting,
    end point detection, firewall, intrusion detection system, Security Information
    and Event Management (SIEM) tool.
- Ensure current user permissions, controls, procedures, and protocols in place
    align with necessary compliance requirements.
- Ensure current technology is accounted for. Both hardware and system access.

## Controls Assessment  <a name="control-assessment">
### Current assets
Assets managed by the IT Department include:
- On-premises equipment for in-office business needs
- Employee equipment: end-user devices (desktops/laptops, smartphones),
remote workstations, headsets, cables, keyboards, mice, docking stations,
surveillance cameras, etc.
- Storefront products available for retail sale on site and online; stored in the
company’s adjoining warehouse
- Management of systems, software, and services: accounting,
telecommunication, database, security, ecommerce, and inventory
management
- Internet access
- Internal network
- Data retention and storage
- Legacy system maintenance: end-of-life systems that require human
monitoring

## Botium's Internal Security Audit<a name="workflow">
### Risk description
Currently, there is inadequate management of assets. Additionally, Botium Toys does not have all of the proper controls in place and may not be fully compliant with U.S. and international regulations and standards.

### Control best practices
The first of the five functions of the NIST CSF is Identify. Botium Toys will need to dedicate resources to identify assets so they can appropriately manage them. Additionally, they will need to classify existing assets and determine the impact of the loss of existing assets, including systems, on business continuity.

### Risk score
On a scale of 1 to 10, the risk score is 8, which is fairly high. This is due to a lack of
controls and adherence to compliance best practices.

The potential impact from the loss of an asset is rated as medium, because the IT
department does not know which assets would be at risk. The risk to assets or fines
from governing bodies is high because Botium Toys does not have all of the necessary
controls in place and is not fully adhering to best practices related to compliance
regulations that keep critical data private/secure. Review the following bullet points for
specific details:
-  Currently, all Botium Toys employees have access to internally stored data and
may be able to access cardholder data and customers’ PII/SPII.
- Encryption is not currently used to ensure confidentiality of customers’ credit
card information that is accepted, processed, transmitted, and stored locally in
the company’s internal database.
- Access controls pertaining to least privilege and separation of duties have not
been implemented.
- The IT department has ensured availability and integrated controls to ensure
data integrity.
- The IT department has a firewall that blocks traffic based on an appropriately
defined set of security rules.
- Antivirus software is installed and monitored regularly by the IT department.
- The IT department has not installed an intrusion detection system (IDS).
- There are no disaster recovery plans currently in place, and the company does
not have backups of critical data.
- The IT department has established a plan to notify E.U. customers within 72
hours if there is a security breach. Additionally, privacy policies, procedures, and
processes have been developed and are enforced among IT department
members/other employees, to properly document and maintain data.
- Although a password policy exists, its requirements are nominal and not in line
with current minimum password complexity requirements (e.g., at least eight
characters, a combination of letters and at least one number; special
characters).
- There is no centralized password management system that enforces the
password policy’s minimum requirements, which sometimes affects
productivity when employees/vendors submit a ticket to the IT department to
recover or reset a password.
- While legacy systems are monitored and maintained, there is no regular
schedule in place for these tasks and intervention methods are unclear.
- The store’s physical location, which includes Botium Toys’ main offices, store
front, and warehouse of products, has sufficient locks, up-to-date
closed-circuit television (CCTV) surveillance, as well as functioning fire
detection and prevention systems.

## Assessment Checlist<a name="checklist">
### Control Assessment Checklist
| Yes | No | Control |
| ----- | ----- |---------------|
| &#x2610; | &#x2612; | Least Privilege |
| &#x2610; | &#x2612; | Disaster recovery plans |
| &#x2610; | &#x2612; | Separation of duties |
| &#x2612; | &#x2610; | Firewall |
| &#x2610; | &#x2612; | Intrusion detection system (IDS) |
| &#x2610; | &#x2612; | Backups |
| &#x2612; | &#x2610; | Antivirus software |
| &#x2612; | &#x2610; | Manual monitoring, maintenance, and intervention for legacy systems |
| &#x2610; | &#x2612; | Encryption |
| &#x2610; | &#x2612; | Password management system |
| &#x2612; | &#x2610; | Locks (offices, storefront, warehouse) |
| &#x2612; | &#x2610; | Closed-circuit television (CCTV) surveillance |
| &#x2612; | &#x2610; | Fire detection/prevention (fire alarm, sprinkler system, etc.) |


### Compliance Checklist
Payment Card Industry Data Security Standard (PCI DSS)
| Yes | No | Best Practice |
|---|---|---------------|
| &#x2610; | &#x2612; | Only authorized users have access to customers’ credit card information.  |
| &#x2610; | &#x2612; | Credit card information is stored, accepted, processed, and transmitted internally, in a secure environment. |
| &#x2610; | &#x2612; | Implement data encryption procedures to better secure credit card transaction touchpoints and data.. |
| &#x2612; | &#x2610; | Adopt secure password management policies. |

General Data Protection Regulation (GDPR)
| Yes | No | Best Practice |
|---|---|---------------|
| &#x2610; | &#x2612; | E.U. customers’ data is kept private/secured. |
| &#x2612; | &#x2610; | There is a plan in place to notify E.U. customers within 72 hours if their data is compromised/there is a breach. |
| &#x2610; | &#x2612; | Ensure data is properly classified and inventoried. |
| &#x2610; | &#x2612; | Enforce privacy policies, procedures, and processes to properly document and maintain data. |

System and Organizations Controls (SOC type 1, SOC type 2)
| Yes | No | Best Practice |
|---|---|---------------|
| &#x2610; | &#x2612; | User access policies are established. |
| &#x2610; | &#x2612; | Sensitive data (PII/SPII) is confidential/private. |
| &#x2612; | &#x2610; | Data integrity ensures the data is consistent, complete, accurate, and has been validated. |
| &#x2610; | &#x2612; | Data is available to individuals authorized to access it. |


## Control Categories Assessment<a name="assessment">
### Administrative Controls 
| Control Name | Control type | Control Purpose | Priority |
| ------ | --- | --- | --- |
| Least Privilege | Preventative | Reduces risk by making sure vendors and non-authorized staff only have access to the assets/data they need to do their jobs | High |
| Disaster recovery plans | Corrective | Business continuity to ensure systems are able to run in the event of an incident/there is limited to no loss of productivity downtime/impact to system components, including: computer room environment (air conditioning, power supply, etc.); hardware (servers, employee equipment); connectivity (internal network, wireless); applications (email, electronic data) data and restoration | High |
| Password policies | Preventative | Establish password strength rules to improve security/reduce the likelihood of account compromise through brute force or dictionary attack techniques | High |
| Access control policies | Preventative | Increase confidentiality and integrity of data | High |
| Account management policies | Preventative | Reduce attack surface and limit overall impact from disgruntled/former employees | High |
| Separation of duties | Preventative | Ensure no one has so much access that they can abuse the system for personal gain | High |

### Technical Controls 
| Control Name | Control type | Control Purpose | Priority |
| ------ | --- | --- | --- |
| Firewall | Preventative | Firewalls to filter unwanted/malicious traffic from entering internal network | Low |
| Intrusion Detection System (IDS) | Detective | Allows IT team to identify possible intrusions (e.g., anomalous traffic) quickly | High |
| Encryption | Deterrent | Makes confidential information/data more secure (e.g., website payment transactions) | High |
| Backups | Corrective | Supports ongoing productivity in the case of an event; aligns to the disaster recovery plan | High |
| Password management system | Corrective | Password recovery, reset, lockout notifications | High |
| Antivirus (AV) software | Corrective | Detect and quarantine known threats | High |
| Manual monitoring, maintenance, and intervention | Preventative/corrective | Required for legacy systems to identify and mitigate potential threats, risks, and vulnerabilities | High |


### Physical Controls
| Control Name | Control type | Control Purpose | Priority |
| ------ | --- | --- | --- |
| Time-controlled safe | Deterrent | Reduce attack surface/impact of physical threats | Medium |
| Adequate lighting | Deterrent | Limit “hiding” places to deter threats | Medium |
| Closed-circuit television (CCTV) surveillance | Preventative/detective | Can reduce risk of certain events; can be used after event for investigation | High |
| Locking cabinets (for network gear) | Preventative | Increase integrity by preventing unauthorized personnel/individuals from physically accessing/modifying network infrastructure gear | High |
| Signage indicating alarm service provider | Deterrent | Makes the likelihood of a successful attack seem low | Low |
| Locks | Preventative | Physical and digital assets are more secure | High |
| Fire detection and prevention (fire alarm, sprinkler system, etc.) | Detective/Preventative | Detect fire in the toy store’s physical location to prevent damage to inventory, servers, etc. | Medium |


## Recommendation/Summary<a name="summary">

It is crucial that Botium Toys promptly addresses the critical findings related to PCI and GDPR compliance, as the company accepts online payments and is expanding its services to handle customers' data from the European Union. The audit goal should align with the SOC1 and SOC2 guidance related to user access policies, which should adapt to the concept of least permissions. This will help develop the policies and procedures necessary for compliance.

To ensure business continuity in the event of an incident, such as a physical disaster or a cyber attack, it is recommended that Botium Toys have a disaster recovery plan and backups in place. Implementing fire detection and prevention systems to protect against physical attacks is also worth considering.

Integrating IDS and AV software into the existing system will assist with intrusion detection and spot and mitigate potential risks while considering the existing legacy systems that need manual monitoring and intervention.

Locks and CCTV should be used to secure physical assets at Botium Toys' physical location. Potential threats can be monitored with a time-controlled safe, adequate lighting, and signage indicating the alarm service provider.
