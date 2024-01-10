# Botium-Toys-Security-Audit

Review Botium's IT manager’s scope, goals, and risk assessment report. Then, perform an internal audit by completing a controls and compliance checklist. 

# Table of contents

1. [Introduction](#introduction)
2. [Internal Security Audit Workflow](#workflow)
3. [Controls Assessment](#control-assessment)
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


### Administrative Controls 
| Control Name | Control type and explanation | Priority |
| --- | --- | --- |
| Least Privilege | Preventative; reduces risk by making sure vendors and non-authorized staff only have access to the assets/data they need to do their jobs | High |
| Disaster recovery plans | Corrective; business continuity to ensure systems are able to run in the event of an incident/there is limited to no loss of productivity downtime/impact to system components, including: computer room environment (air conditioning, power supply, etc.); hardware (servers, employee equipment); connectivity (internal network, wireless); applications (email, electronic data); data and restoration | High |
| Password policies | Preventative; establish password strength rules to improve security/reduce likelihood of account compromise through brute force or dictionary attack techniques | High |
| Access control policies | Preventative; increase confidentiality and integrity of data | High |
| Account management policies | Preventative; reduce attack surface and limit overall impact from disgruntled/former employees | High |
| Separation of duties | Preventative; ensure no one has so much access that they can abuse the system for personal gain | High |

### Technical Controls 
| Control Name | Control type and explanation | Priority |
| --- | --- | --- |
| Firewall | Preventative; firewalls ***are already in place*** to filter unwanted/malicious traffic from entering internal network | NA |
| Intrusion Detection System (IDS) | Detective; allows IT team to identify possible intrusions (e.g., anomalous traffic) quickly | High |
| Encryption | Deterrent; makes confidential information/data more secure (e.g., website payment transactions) | High |
| Backups | Corrective; supports ongoing productivity in the case of an event; aligns to the disaster recovery plan | High |
| Password management system | Corrective; password recovery, reset, lock out notifications | High |
| Antivirus (AV) software | Corrective; detect and quarantine known threats | High |
| Manual monitoring, maintenance, and intervention | Preventative/corrective; required for legacy systems to identify and mitigate potential threats, risks, and vulnerabilities | High |


### Physical Controls
| Control Name | Control type and explanation | Priority |
| --- | --- | --- |
| Time-controlled safe | Deterrent; reduce attack surface/impact of physical threats | Medium/Low |
| Adequate lighting | Deterrent; limit “hiding” places to deter threats | Medium/Low |
| Closed-circuit television (CCTV) surveillance | Preventative/detective; can reduce risk of certain events; can be used after event for investigation | High/Medium |
| Locking cabinets (for network gear) | Preventative; increase integrity by preventing unauthorized personnel/individuals from physically accessing/modifying network infrastructure gear | High/Medium |
| Signage indicating alarm service provider | Deterrent; makes the likelihood of a successful attack seem low | Low |
| Locks | Preventative; physical and digital assets are more secure | High |
| Fire detection and prevention (fire alarm, sprinkler system, etc.) | Detective/Preventative; detect fire in the toy store’s physical location to prevent damage to inventory, servers, etc. | Medium |
