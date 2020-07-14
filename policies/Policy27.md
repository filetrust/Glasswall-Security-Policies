# Test Data Policy


|                  |            | 
|------------------|------------|
| **ID**           | [Policy-27](https://glasswall.atlassian.net/browse/POLICY-27) |
| **Status**       | Draft      |
| **Release Date** | TBD        |
| **Version**      | v0.1       |
| **Owners**       | [CISO](https://glasswall.atlassian.net/browse/ROLE-38), [CEO](https://glasswall.atlassian.net/browse/ROLE-37)       |
| **Stakeholders** | [Head of IT](https://glasswall.atlassian.net/browse/ROLE-43), Head of HR, Test Teams|

# Contents


 1.0 Overview        
 2.0 Purpose        
 3.0 Scope        
 4.0 Policy        
 4.1 Handling Malicious Files      
 4.2 Customer Data  
 4.3 Files Acquired from External Sources       
 4.4 Personal Data        
 4.5 Data Destruction        
 4.6 Data Sharing or Publishing
 4.7 Applicability of Other Policies        
 5.0 Enforcement        
 6.0 Definitions        

Glasswall is hereinafter referred to as &quot;the company.&quot;

### 1.0 Overview

The engineering teams needs realistic data files for a number of reasons. Because of the nature of the companies products some of these files are malicious. Also our customers provide data for support cases that may also be malicious and/or confidential. In addition to creating specific test data some data is periodically scraped from the internet or acquired from other sources. A policy is therefore needed to govern the aquiistion, storage and destruction of test data.

### 2.0 Purpose

The purpose of this policy is to specify the company&#39;s guidelines for aqcuiring, storing and deletion of test data. 

### 3.0 Scope

The scope of this policy covers all test data used by engineering teams working on the company&#39;s products.

The creation of bespoke test data is out of scope.


### 4.0 Policy

#### 4.1 Handling Malicious Files

Malicious files, such as malware or viruses, should not be stored long term on the company&#39;s devices, networks or cloud services. 

The normal method for testing known malicious files is:

1) Download the required file from virustotal or similar service to a seperate or segragated area, e.g. a container.
2) Run the test
3) Delete the file.

Malicious files may be stored temporarily under the following conditions:

1) The area used is segregated or separated from other test data storage areas.
2) Each file is in a passworded zip file.
3) Once the need for the file has passed it is deleted.

The above policies are designed to reduce the chance of an accidential detonation of malware within the company&#39;s infrastructure.

#### 4.2 Customer Data

Data from customers should only be retained by the engineering teams for as long has been agreed with that customer. Such data may be retained by other parts of the business separately in line with other retention policies, e.g. in support databases. Customer data files should be stored in a separate aeaa to other test data. 

Any confidential customer supplied test data must be password pretected.


#### 4.3 Files Acquired from External Sources.

All data acquired from external sources, including files directly from customers, should be treated as potentially malicious.

If it is not known if an acquired file is malicious or potetnially malicious it should be virus scanned before adding to any data set. Files should be stored in a segregated area until considered safe.


#### 4.4 Personal Data

Any personal data used for testing must be stored in accordance with the relevant security policy and legislation, i.e. GDPR.


#### 4.5 Data Destruction

Once test data is deemed to be no longer requierd it should be deleted from the company&#39;s infrastrucure in accordance with the relevant data retention policy

#### 4.6 Data Sharing or Publishing

Any test data considered confidential may only be shared with the express permission of the data owner and must not be put in any public repository, file share or similar. 

Test data files to be shared publically or with external parties must only be shared if we have the right to do so. Consideration should be given to any copyright or relevant legislation. Any data shared or published should include a statement on ownership/copyright, e.g. if glasswall, creative commons or some other third party copyright.

#### 4.7 Applicability of Other Policies

This document is part of the company&#39;s cohesive set of security policies.  Other policies may apply to the topics covered in this document and as such the applicable policies should be reviewed as needed.

### 5.0 Enforcement

This policy will be enforced by the IT Manager and/or Executive Team. Violations may result in disciplinary action, which may include suspension, restriction of access, or more severe penalties up to and including termination of employment. Where illegal activities or theft of company property (physical or intellectual) are suspected, the company may report such activities to the applicable authorities.

### 6.0 Definitions

Refer to Information Security Policy Guide.

Acquired file - a file purchased, downloaded or sent from an extrnal source. It includes customer supplied data files.

Rendered
Glasswall Solutions Ltd.
Data
Retention Policy
Information contained herein is the property of Glasswall Limited and is company confidential.
Revision 0.1
Document History
Table 1: Document Change History
Issue Date	Issue Number	Document Owner	Description
14th July  2020 | 0.1 | | First Draft | | | | | | | | | | | | | | | | | | | | |

Document Distribution
Table 2: Document Distribution
Name	Position	Date	Signature


Data Retention Policy
| | |

