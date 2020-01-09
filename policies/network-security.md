# Network Security Policy  - Draft

Issue Date : 2nd January 2018 
Issue Number : 2.1

Document Owner 

### Contents

- **1.0 Overview**
- **2.0 Purpose**
- **3.0 Scope** 
- **4.0 Policy**
  - 4.1 Network Device Passwords
    - 4.1.1 Password Construction
    - 4.1.2 Failed Logins
    - 4.1.3 Change Requirements
    - 4.1.4 Password Policy Enforcemen
    - 4.1.5 Administrative Password Guidelines
  - 4.2 Logging
    - 4.2.1 Administrator Acces
    - 4.2.2 Application Servers
    - 4.2.3 Network Devices
    - 4.2.4 Critical Devices
    - 4.2.5 Log Management
    - 4.2.6 Log Review
    - 4.2.7 Log Retention
  - 4.3 Firewalls
    - 4.3.1 Configuration
    - 4.3.2 Outbound Traffic Filtering
    - 4.4 Networking Hardware
  - 4.5 Network Servers
    - 4.6 Intrusion Detection Systems/Intrusion Prevention Systems (IDS/IPS)
    - 4.6.1 Ruleset Configuration
    - 4.6.2 Configuration
    - 4.6.3 Connections
    - 4.6.4 Configuration Management
  - 4.7 Security Testing
    - 4.7.1 Internal Security Testing
    - 4.7.2 External Security Testing
  - 4.8 Disposal of Information Technology Assets
  - 4.9 Network Segregation 
    - 4.9.1 Higher Risk Networks
    - 4.9.2 Externally-Accessible Systems
    - 4.9.3 Internal Networks
    - 4.10 Network Documentation
    - 4.11 Antivirus/Anti-Malware
    - 4.12 Software Use Policy
    - 4.13 Maintenance Windows and Scheduled Downtime
    - 4.14 Change Management
    - 4.15 Suspected Security Incidents
    - 4.16 Redundancy
    - 4.17 Manufacturer Support Contracts for Network Devices
    - 4.18 Applicability of Other Policies
  - **5.0 Enforcement**
  - **6.0 Definitions**
￼ 

Glasswall is hereinafter referred to as "the company." 

## 1.0 Overview 

This document sets out the organisations intention to protect the confidentiality, integrity and availability of the Company’s network. 

## 2.0 Purpose 

The purpose of this policy is to establish administrative direction, procedural requirements, and requirements to ensure the appropriate protection of Company information handled by computer networks. 

## 3.0 Scope 

This policy covers all Company IT systems and devices regardless of location or ownership.  

## 4.0 Policy 

### 4.1 Network Device Passwords 

Passwords used to secure network devices, such as routers, switches, and servers, must be held to higher standards than standard user-level or desktop system passwords. 

#### 4.1.1 Password Construction 

The following must apply to the construction of passwords for network devices: 

Passwords should be at least 12 characters where possible. 

Passwords should be comprised of a mix of letters, numbers and special characters (punctuation marks and symbols). 

Passwords should be comprised of a mix of upper and lower-case characters. 

Passwords should not be comprised of, or otherwise utilise, words that can be found in a dictionary. 

Passwords should not be comprised of an obvious keyboard sequence (i.e., qwerty). 

Passwords should not include "guessable" data such as personal information like birthdays, addresses, phone numbers, locations, etc. 

Passwords should not be similar to the manufacturer provided default. 

#### 4.1.2 Failed Logins 

The Company must lock network user accounts after 3 unsuccessful logins.   

When login failures occur, the error message transmitted to the user must not indicate specifically whether the account name or password were incorrect.  The error must only state "the username and/or password you supplied were incorrect." 

#### 4.1.3 Change Requirements 

Passwords must be changed according to the company's Password Policy.  Additionally, the following requirements apply to changing network device passwords: 

If any network device password is suspected to have been compromised, all network device passwords must be changed immediately. 

If a company network or system administrator leaves the company, all passwords to which the administrator could have had access must be changed immediately.  This statement also applies to any consultant or contractor who has access to administrative passwords. 

Vendor default passwords must be changed when new devices are put into service. 

#### 4.1.4 Password Policy Enforcement 

Where passwords are used, the network device management application must be configured to enforce the company's password policies on construction, changes, re-use, lockout, etc. 

#### 4.1.5 Administrative Password Guidelines 

Administrative (also known as "root") access to systems must be limited to only those who have a legitimate business need for this type of access. 


### 4.2 Logging 

The following sections detail the company's requirements for logging and log review. 

#### 4.2.1 Administrator Access 

All System administrator and system operator activities should be logged. 

#### 4.2.2 Application Servers 

Logging should be enabled to the fullest degree possible. No passwords should be contained in logs. 

#### 4.2.3 Network Devices 

Logging should be enabled to the fullest degree possible. No passwords should be contained in logs. 

#### 4.2.4 Critical Devices 

Logging should be enabled to the fullest degree possible. No passwords should be contained in logs. 

#### 4.2.5 Log Management 

Audit logs must be collated and stored centrally, and kept in accordance with the Data Retention Policy.  Real time analysis of security logs from network devices and applications must be facilitated using a Security Incident & Event Management (SIEM) application or service. 

#### 4.2.6 Log Review 

Log reviews must be performed weekly. 

#### 4.2.7 Log Retention 

Logs should be retained in accordance with the company's Retention Policy. 

#### 4.2.8 Log Testing 

The end-to-end logging process should be tested periodically.  

### 4.3 Firewalls 

The following sections detail the use of a Company firewall. 

#### 4.3.1 Configuration 

The following must be applied: 

##### 4.3.1.1 Rule Management 

The firewall configuration changes must follow the appropriate change management procedure. 

The firewall ruleset must be documented and audited. 

Reviews must take place quarterly to ensure optimal security and to remove any unused rules. 

##### 4.3.1.2 Ruleset Configuration 

The firewall ruleset should include a "deny/block all," rule as the last rule to avoid any security lapse. 

The firewall ruleset should include a "stealth rule," which forbids connections to the firewall itself. 

The firewall should be configured to log dropped or rejected packets. 

 

4.3.1.3 Configuration 

Clocks should be synchronised using NTP. 

Operating systems and applications must be fully up-to-date with latest versions from software vendor. 

Separate accounts must be used for each administrator. 

Configuration settings should be backed up periodically in accordance with the Back Up policy. 

Backs Ups should be completed before applying updates. 

 

4.3.1.4 Connections 

Only encrypted access from authorised networks may allow management of firewalls. 

No unnecessary services or applications should be enabled on firewalls. 

 

4.3.2 Outbound Traffic Filtering 

Outbound traffic should be limited to only authorised services using authorised ports. All other outbound traffic must be blocked. 

 

4.4 Networking Hardware 

The following sections detail the use of Company networking hardware. 

 

The following statements apply: 

Only encrypted access from authorised networks may allow management of network hardware. 

Clocks on network devices should be synchronised using NTP. 

Access control lists must be implemented on network devices to prohibit direct connections to the devices. 

Unused services and ports should be disabled on networking hardware. 

Access to administrative ports on networking hardware should be restricted to known management hosts and otherwise blocked with a firewall or enforced by an access control list. 

 

Page Break
 

4.5 Network Servers 

The following statements apply to the company's use of network servers: 

 

Network servers must be built to Company standards using a Company server-hardening guide. 

Server software should be fully up-to-date with latest versions from software vendor. 

Network servers must be protected by a firewall or access control list. 

An installation process must be developed for the company's network servers to ensure standard configuration. 

Clocks on network servers should be synchronised with the company's other networking hardware using NTP or another means. 

 

4.6 Intrusion Detection Systems/Intrusion Prevention Systems (IDS/IPS) 

 

The company must continuously monitor for signs of attack and compromise using IDS/IPS. 

The following statements apply to the company's use of IDS/IPS: 

 

4.6.1 Ruleset Configuration 

Ensure the latest vendor updates to detection signatures are obtained and applied. 

Capture at least packet headers of traffic and retain for at least 7 days. 

 

4.6.2 Configuration 

Each IDS/IPS instance must be secured appropriately following vendor guidelines or industry best practice. 

Suspicious activities must generate automated alerts to the IT Manager. 

Clocks should be synchronised using NTP. 

Operating systems and applications must be fully up-to-date with latest versions from software vendor. 

Separate accounts must be used for each administrator. 

 

4.6.3 Connections 

Only encrypted access from authorised networks may allow management of each IDS/IPS instance. 

No unnecessary services or applications should be enabled. 

 

4.6.4 Configuration Management 

Configuration settings should be backed up periodically in accordance with the Back Up policy. 

Backs Ups should be completed before applying updates. 

  

4.7 Security Testing 

 

The company must undertake regular vulnerability assessments, security audits and penetration testing to assess the company's network security posture. 

 

The following sections detail the company's requirements for security testing. 

 

4.7.1 Internal Security Testing 

Internal security testing should only be performed by trained employees whose job functions are to assess security, and only with permission of the IT Manager. 

Vulnerability scans must be conducted monthly using company approved tools and methods. 

Upon any configuration change to a system, an internal scan must be performed. 

Failed tests should be documented and must have a plan to remediate any failures. 

Any failures not remediated must be reported to Management for Risk Assessment. 

 

4.7.2 External Security Testing 

Regular external security testing must be conducted at least once per quarter. 

Security testing should avoid negatively affecting network performance, company systems or data. 

Testing should be performed as often as is necessary, as determined by the IT Manager. 

Failed tests should be documented and must have a plan to remediate any failures. 

Any failures not remediated must be reported to Management for Risk Assessment. 

 

4.8 Disposal of Information Technology Assets 

When Information Technology assets are decommissioned, the following guidelines must be followed: 

 

Any asset tags or stickers that identify the company must be removed before disposal. 

Hard disk data wiping must only be performed with approved tools that meet as a minimum DoD 3 parse overwrite standard (DoD 5220.22-m).  

For disposal of all information technology assets that contain company data, the following applies; 

Data wiping must be used. 

Or 

The device must be physically destroyed beyond the ability to retrieve any data. 

 

4.9 Network Segregation 

With regards to network segregation, the following applies; 

 

4.9.1 Higher Risk Networks 

Segmentation of higher risk networks from the company's internal network is required, and must be enforced with a firewall or router that provides access controls. 

 

4.9.2 Externally-Accessible Systems 

Segmentation of externally-accessible systems from the company's internal network is required, and must be enforced with a firewall or router that provides access controls.  

 

4.9.3 Internal Networks 

The company requires that networks be segmented to the fullest reasonable extent. 

 

4.10 Network Documentation 

At a minimum, network documentation must include: 

Network diagram(s) 

System configurations 

Firewall ruleset 

IP Addresses 

Access Control Lists 

 

Network documentation must be updated upon any changes, and must be reviewed on a quarterly basis.  

 

4.11 Antivirus/Anti-Malware 

All company-provided equipment must have antivirus/anti-malware software installed. 

All Company devices must have the most up to date patches and virus signature/definition file applied in a timely manner. 

Antivirus and malware scanning must be implemented at the Internet gateway. 

 

4.12 Software Use Policy 

The company requirements for the use of software is as follows: 

Only legally licensed software may be used. 

Licenses for the company's software must be stored securely. 

Only approved open source and/or public domain software can be installed. 

Software must be kept up-to-date by installing new patches and releases from the manufacturer. 

Vulnerability alerts should be monitored for all software products that the company uses. 

Any patches that fix vulnerabilities or security holes must be installed in a timely manner. 

 

4.13 Maintenance Windows and Scheduled Downtime 

Planned downtime for network devices must only be outside normal business hours. 

Tasks that are deemed as an emergency measure can be performed at any time as determined by the IT Manager or as instructed by Management. 

Only the IT Manager or authorised delegated staff can approve downtime during business hours. 

 

4.14 Change Management 

The IT Staff must document configuration changes to network devices in a change log. 

Physical network devices must bear an asset tag showing only the asset number, all further details and information must be recorded in a separate asset register. 

 

4.15 Suspected Security Incidents 

When a security incident is suspected that may impact a network device, the IT Staff must comply with the company's Incident Response policy. 

 

4.16 Redundancy 

The company must ensure minimal disruption and downtime for network devices, and plan for outages. 

 

Redundancy should be implemented where it is needed, and must include but is not limited to the following: 

Power redundancy, such as Uninterrupted Power Supply (UPS). 

Server level redundancy, such as clustering or high availability. 

Hard drive redundancy, such as mirroring or RAID. 

Component level redundancy, such as redundant power supplies or redundant NICs. 

Maintaining a supply of hot or cold spares onsite for replaceable components likely to fail. 

 

4.17 Manufacturer Support Contracts for Network Devices 

The company must purchase a vendor approved hardware/software support agreement for all network devices. 

For the duration of the support agreement, the following minimum requirements must be followed: 

Hardware: The support agreement must allow for repair/replacement of the device within an acceptable time period, as determined by the IT Manager, as well as firmware or embedded software updates. 

Software: The support agreement must allow for updates, upgrades, and hotfixes. 

 

4.18 Applicability of Other Policies 

This document is part of the company's cohesive set of security policies.  Other policies may apply to the topics covered in this document and as such the applicable policies should be reviewed as needed. 

 

5.0 Enforcement 

 

This policy will be enforced by the IT Manager and/or Executive Team. Violations may result in disciplinary action, which may include suspension, restriction of access, or more severe penalties up to and including termination of employment. Where illegal activities or theft of company property (physical or intellectual) are suspected, the company may report such activities to the applicable authorities. 

 

6.0 Definitions 

Refer to Glasswall Information Security Policy Guide. 

 

 

 

 
