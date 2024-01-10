# Botium-Toys-Security-Audit

Review Botium's IT manager’s scope, goals, and risk assessment report. Then, perform an internal audit by completing a controls and compliance checklist. 

# Table of contents

1. [Introduction](#introduction)
2. [Controls Assessment](#control-assessment)
3. [Security Audit](#workflow)
4. [Compliance Checklist](#compliance-checklist)
5. [Stakeholder Memorandum](#stakeholder-memo)
6. [Conclusion](#conclusion)

----------
# Introduction <a name="introduction">

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

# Controls Assessment  <a name="control-assessment">
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

# Botium's Internal Security Audit<a name="workflow">
### Risk description
Currently, there is inadequate management of assets. Additionally, Botium Toys does not have all of the proper controls in place and may not be fully compliant with U.S. and international regulations and standards.

### Control best practices
The first of the five functions of the NIST CSF is Identify. Botium Toys will need to dedicate resources to identify assets so they can appropriately manage them. Additionally, they will need to classify existing assets and determine the impact of the loss of existing assets, including systems, on business continuity.


### Control Assessment Checklist
| Yes | No | Control |
|---|---|---------------|
| [x] | [ ] | Least Privilege |
| [x] | [ ] | Disaster recovery plans |
| [x] | [ ] | Password policies |
| [x] | [ ] | Separation of duties |
| [x] | [ ] | Firewall |
| [x] | [ ] | Intrusion detection system (IDS) |
| [x] | [ ] | Backups |
| [x] | [ ] | Manual monitoring, maintenance, and intervention for legacy systems |
| [x] | [ ] | Encryption |
| [x] | [ ] | Password management system |
| [x] | [ ] | Locks (offices, storefront, warehouse) |
| [x] | [ ] | Closed-circuit television (CCTV) surveillance |
| [x] | [ ] | Least Privilege |


### Compliance Checklist

Payment Card Industry Data Security Standard (PCI DSS)
| Yes | No | Control |
|---|---|---------------|
| [x] | [ ] | Least Privilege |
| [x] | [ ] | Least Privilege |
| [x] | [ ] | Least Privilege |
| [x] | [ ] | Least Privilege |

General Data Protection Regulation (GDPR)
| Yes | No | Control |
|---|---|---------------|
| [x] | [ ] | Least Privilege |
| [x] | [ ] | Least Privilege |
| [x] | [ ] | Least Privilege |
| [x] | [ ] | Least Privilege |


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
| Firewall | Preventative | Firewalls ***are already in place*** to filter unwanted/malicious traffic from entering internal network | NA |
| Intrusion Detection System (IDS) | Detective | Allows IT team to identify possible intrusions (e.g., anomalous traffic) quickly | High |
| Encryption | Deterrent | Makes confidential information/data more secure (e.g., website payment transactions) | High |
| Backups | Corrective | Supports ongoing productivity in the case of an event; aligns to the disaster recovery plan | High |
| Password management system | Corrective | Password recovery, reset, lockout notifications | High |
| Antivirus (AV) software | Corrective | Detect and quarantine known threats | High |
| Manual monitoring, maintenance, and intervention | Preventative/corrective | Required for legacy systems to identify and mitigate potential threats, risks, and vulnerabilities | High |


### Physical Controls
| Control Name | Control type | Control Purpose | Priority |
| ------ | --- | --- | --- |
| Time-controlled safe | Deterrent | Reduce attack surface/impact of physical threats | Medium/Low |
| Adequate lighting | Deterrent | Limit “hiding” places to deter threats | Medium/Low |
| Closed-circuit television (CCTV) surveillance | Preventative/detective | Can reduce risk of certain events; can be used after event for investigation | High/Medium |
| Locking cabinets (for network gear) | Preventative | Increase integrity by preventing unauthorized personnel/individuals from physically accessing/modifying network infrastructure gear | High/Medium |
| Signage indicating alarm service provider | Deterrent | Makes the likelihood of a successful attack seem low | Low |
| Locks | Preventative | Physical and digital assets are more secure | High |
| Fire detection and prevention (fire alarm, sprinkler system, etc.) | Detective/Preventative | Detect fire in the toy store’s physical location to prevent damage to inventory, servers, etc. | Medium |
