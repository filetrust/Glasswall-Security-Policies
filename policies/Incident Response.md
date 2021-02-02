# Incident Response Policy

|                  |            | 
|------------------|------------|
| **ID**           | [Policy-15](https://glasswall.atlassian.net/browse/POLICY-14) |
| **Status**       | Approved by InfoSec, Awaiting Final Approval             |
| **Release Date** | TBD        |
| **Version**      | v2.1       |
| **Owners**       | [CISO](https://glasswall.atlassian.net/browse/ROLE-38), [CEO](https://glasswall.atlassian.net/browse/ROLE-37)       |
| **Stakeholders** | [Head of IT](https://glasswall.atlassian.net/browse/ROLE-43), Head of HR, [Head of InfoSec](https://glasswall.atlassian.net/browse/ROLE-47|

Glasswall is hereinafter referred to as &quot;the company.&quot;

### 1.0 Overview

An incident can come in many forms: a malicious attacker gaining access to the network, a virus or other malware infecting computers, infrastructure failure, a natural disaster or even a stolen laptop containing confidential data.  A well-thought-out Incident Response Policy is critical to successful recovery from an incident.  This policy covers all incidents that may affect the security and integrity of the company&#39;s information assets, and outlines steps to take in the event of such an incident.

### 2.0 Purpose

This policy is intended to ensure that the company is prepared if any incident was to occur.  It details what must occur if an incident is suspected, covering both electronic and physical security incidents. The company is a fully online company therefore the scope of this policy is limited to certain cases. 

### 3.0 Scope

The scope of this policy covers all information assets owned or provided by the company, whether they reside on the company cloud network or elsewhere.

### 4.0 Policy

#### 4.1 Types of Incidents

For the purposes of this policy an incident is defined as one of the following:

- Electronic: This type of incident can range from an attacker or malicious user accessing the network for unauthorised purposes, or a malware infection.
- Physical: A physical IT security incident involves the loss or theft of a laptop, mobile device, Smartphone, tablet, portable storage device, or other digital device that may contain sensitive or company confidential information. The physical incidents also cover cases of major natural disasters, global pandemics or major incidents related to the area that most of the company's employees reside on. 

### 4.1.1 Incident Classification



#### 4.2 Preparation

The company must identify a third-party IT Security company that offers incident response services to ensure that high-end resources are quickly available during an incident.

The company should review any industry or governmental regulations that dictate how it must respond to a security incident (specifically, loss of customer data), and ensure that its incident response plans adhere to these regulations.

The company should develop a communications process for incident response in the event that corporate communications systems may have been compromised.

Prior to an incident, the company must ensure that the following is clear to IT personnel:

- What actions to take when an incident is suspected or reported.
- Who is responsible for responding to an incident.

Prior to an incident, the company must ensure that the following is clear to all personnel:

- Incidents must be reported at the earliest opportunity on the basis that enforcement of this policy supports openness, trust and learning from security incidents.

#### 4.3 Confidentiality

All information related to an electronic or physical security incident must be treated as confidential information until the incident is fully contained.  This will serve both to protect employees&#39; reputations (if an incident is due to an error, negligence, or carelessness), and to control the release of information to the media and/or customers.

Details of security incidents must not be;

- Shared with unauthorised individuals.
- Made public by unauthorised staff.
- Discussed in an open forum.

#### 4.4 Incident Response Team

**Incident First Responder**

Any Glasswall employee, Information Security and IT Support Squad member that gets notified or notices the incident. Reporting and triggering incidents is the responsability of every employee. The first responder does immediate necessary steps to prevent further breach or exploitation of affected assets (or if necessary delegates this task to someone who can execute these emergency procedures) and triggers the incident procedure. 

**Incident Manager**

Assigns roles within the team and delegates tasks on Jira. Asks key questions from the team. Closes the incident

**Incident Handlers**

Collect evidence. Execute various digital forensic and technical tasks required to contain and investigate incident. Answer key questions. 

**Incident communicator/reporter**

Communicates with authorities and other third parties that need to be involved. Communicates with rest of the Glasswall team and the executive team about the incident. Formulates report at the end of the incident based on the evidence collected and formulates future steps and controls in cooperation with the InfoSec squad and CISO

#### 4.5 Electronic Incidents

When an electronic incident is suspected, the company&#39;s goal is to recover as quickly as possible, limit the damage done, and secure the network.  An incident response plan must be developed to include the following steps:

1. Identify immediate steps to prevent further harm to the Glasswall assets
2. Determine incident severity (see table) and based on that consider triggering the business continuity and disaster recovery plan
3. Start Slack Channel with Incident Name and mobilise team - communicate the incident to the company via relevant designated channels
4. Create Jira incident and activate the relevant incident Playbook
5. Identify steps necessary to regain or ensure business continuity
6. Depending on severity notify Executive Team and Management via a newly created #comms channel
7. Contact the retained third party IT company as needed
8. Notify Authorities and ICO if applicable
9. Ensure that other company assets are not prone to the same or similar vulnerabilities
10. Start documentation on incident – timeline (create events), evidence log and evidence acquisition log
11. Consider involving a professional digital forensics team and if not involved proceed to analyse acquired evidence while preserving it.
12. Root Cause Analysis
13. Risk Assesment (identify vulnerabilities, risks, security controls)
14. Identify next steps to prevent further incidents – update policies, processes and identify future controls
15. Discuss vulnerability strategy with head of InfoSec and/or product owner

#### 4.6 Physical Incidents

Physical incidents, regardless of cause, must be treated as if they were targeted at the company.

The company must assume that such a loss will occur at some point, and periodically survey a random sampling of laptops and mobile devices to determine the risk if one were to be lost or stolen.

### 4.6.1 Response

Establish the severity of the incident by determining the data stored on the missing device.  This can often be done by referring to a recent backup of the device.  Two important questions must be answered:

- Was confidential data involved?

-
  - If not, refer to &quot;Loss Contained&quot; below.
  - If confidential data was involved, refer to &quot;Data Loss Suspected&quot; below.

- Was strong encryption used?

-
  - If strong encryption was used, refer to &quot;Loss Contained&quot; below.
  - If not, refer to &quot;Data Loss Suspected&quot; below.

### 4.6.2 Loss Contained

First, change any usernames, passwords, account information, WEP/WPA keys, passphrases, etc., that were stored on the system.  Notify the IT Manager.  Replace the lost hardware and restore data from the last backup.  Notify the applicable authorities if a theft has occurred.

### 4.6.3 Data Loss Suspected

First, notify the executive team, legal counsel, and/or public relations group so that each team can evaluate and prepare a response in their area.

Change any usernames, passwords, account information, WEP/WPA keys, passphrases, etc., that were stored on the system.  Replace the lost hardware and restore data from the last backup.  Notify the applicable authorities as needed if a theft has occurred and follow disclosure guidelines specified in the notification section.

Review procedures to ensure that risk of future incidents is reduced by implementing stronger physical security controls.

#### 4.7 Notification

If an electronic or physical security incident is suspected to have resulted in the loss of third-party/customer data, notification of the public or affected entities should occur in compliance with local regulation.

The executive team and legal counsel must determine an appropriate course of action.

If external notification is deemed appropriate, it should occur in an organized and consistent manner in compliance with local regulation.

#### 4.8 Managing Risk

Managing risk of a security incident or data loss is the primary reason to create and maintain a comprehensive security policy.  Risks can come in many forms: electronic risks like data corruption, computer viruses, hackers, or malicious users; or physical risks such as loss/theft of a device, hardware failure, fire, or a natural disaster.  Protecting critical data and systems from these risks is of paramount importance to the company. Risks and vulnerabilities related to an incident should be logged in the company central database (Jira)

### 4.8.1 Risk Assessment

As part of the risk management process, the company must conduct an accurate and thorough assessment of the potential risks (man-made and natural) and any vulnerabilities to the confidentiality, integrity, and availability of the company&#39;s critical or confidential information.  An assessment must be thorough, can be performed by company personnel or external consultants (or both), and must be well documented. It should be qualitative using the pre-approved Glasswall risk-matrix. 

	![Glasswall Risk Matrix](RiskMatrix.jpg)

### 4.8.2 Risk Management Program

A formal risk management program must be implemented to cover any risks known to the company (which should be identified through a risk assessment), and ensure that reasonable security measures are in place to mitigate any identified risks to a level that will ensure the continued security of the company&#39;s confidential and critical data.

#### 4.9 Applicability of Other Policies

This document is part of the company&#39;s cohesive set of security policies.  Other policies may apply to the topics covered in this document and as such the applicable policies should be reviewed as needed.

### 5.0 Enforcement

This policy will be enforced by the IT Manager and/or Executive Team. Violations may result in disciplinary action, which may include suspension, restriction of access, or more severe penalties up to and including termination of employment. Where illegal activities or theft of company property (physical or intellectual) are suspected, the company may report such activities to the applicable authorities.

### 6.0 Definitions

Refer to Glasswall Information Security Policy Guide.
