# Exam Outline
::: tip INFO
The following exam objectives were translated directly from the (ISC)2 Certification Exam Outline. The effective date of these objectives is **August 1, 2019.**
:::
| Domains | Weight |
| --- | --- |
| 1 - Cloud Concepts, Architecture and Design | 17% |
| 2 - Cloud Data Security | 19% |
| 3 - Cloud Platform and Infrastructure Security | 17% |
| 4 - Cloud Application Security | 17% |
| 5 - Cloud Security Operations | 17% |
| 6 - Legal, Risk and Compliance | 13% |
## Domain 1
### 1.1 Understand Cloud Computing Concepts
- Cloud Computing Definitions
- [Cloud Computing Roles](../../../concepts/cloud/cloud-roles.md)
  - Cloud Service Customer
  - Cloud Service Provider
  - Cloud Service Partner
  - Cloud Service Broker
- [Key Cloud Computing Characteristics](../../../concepts/cloud/cloud-characteristics.md)
  - On-Demand Self-Service
  - Broad Network Access
  - Multitenancy
  - Rapid Elasticity
  - Scalability
  - Resource Pooling
  - Measured Service
- Building Block Technologies
  - Virtualization
  - Storage
  - Networking
  - Databases
  - Orchestration/Automation
### 1.2 Describe Cloud Reference Architecture
- Cloud Computing Activities
- Cloud Service Capabilities
  - Application Capability Types
  - Platform Capability Types
  - Infrastructure Capability Types
- [Cloud Service Categories](../../../concepts/cloud/cloud-service-models/)
  - [Software as a Service \(SaaS\)](../../../concepts/cloud/cloud-service-models/saas.md)
  - [Platform as a Service \(PaaS\)](../../../concepts/cloud/cloud-service-models/paas.md)
  - [Infrastructure as a Service \(IaaS\)](../../../concepts/cloud/cloud-service-models/untitled.md)
- [Cloud Deployment Models](../../../concepts/cloud/cloud-deployment-models/)
  - [Public](../../../concepts/cloud/cloud-deployment-models/public.md)
  - [Private](../../../concepts/cloud/cloud-deployment-models/private.md)
  - [Hybrid](../../../concepts/cloud/cloud-deployment-models/hybrid.md)
  - [Community](../../../concepts/cloud/cloud-deployment-models/community.md)
- Cloud Shared Considerations
  - Interoperability
  - Portability
  - Reversibility
  - Availability
  - Security
  - Privacy
  - Resiliency
  - Performance
  - Governance
  - Maintenance and Versioning
  - Service Levels and Service Level Agreements
  - Auditability
  - Regulatory
- [Impact of Related Technologies](../../../concepts/technology/)
  - Machine Learning
  - Artificial Intelligence
  - [Blockchain](../../../concepts/technology/blockchain.md)
  - Internet of Things \(IoT\)
  - [Containers](../../../concepts/technology/containers.md)
  - Quantum Computing
### 1.3 Understand Security Concepts Relevant to Cloud Computing
- Cryptography and Key Management
- Access Control
- Data and Media Sanitization
  - Overwriting
  - Cryptographic Erasure
- Network Security
  - Network Security Groups
- Virtualization Security
  - Hypervisor Security
  - Container Security
- Common Threats
### 1.4 Understand Design Principles of Secure Cloud Computing
- [Cloud Secure Data Lifecycle](../../../concepts/data/data-lifecycle.md)
- [Cloud-based Disaster Recovery \(DR\) and Business Continuity \(BC\) planning](../../../concepts/bcdr/)
- Cost Benefit Analysis
- Functional Security Requirements
  - Portability
  - Interoperability
  - Vendor Lock-in
- Security Considerations for Different Cloud Categories
### 1.5 Evaluate Cloud Service Providers
- Verification Against Criteria
  - [ISO/IEC 27017](../../../standards/security-management-and-controls/iso-iec-27017-2015.md)
  - [PCI DSS](../../../standards/security-management-and-controls/pci-dss.md)
- System/subsystem Product Certifications
  - [CC](../../../standards/auditing-and-assurance/cc.md)
  - [FIPS 140-2](../../../standards/auditing-and-assurance/nist-fips-140-2.md)
## Domain 2
### 2.1 Describe Cloud Data Concepts
- [Cloud Data Life Cycle Phases](../../../concepts/data/data-lifecycle.md)
- Data Dispersion
### 2.2 Design and Implement Cloud Data Storage Architectures
- [Storage Types](../../../concepts/cloud/cloud-components/cloud-storage/untitled.md)
  - Long Term
  - Ephemeral
  - Raw-disk
- Threats to Storage Types
### 2.3 Design and Apply Data Security Technologies and Strategies
- Encryption and Key Management
- Hashing
- Masking
- Tokenization
- [Data Loss Prevention \(DLP\)](../../../concepts/data/data-security/dlp.md)
- Data Obfuscation
- Data De-identification
  - Anonymization
### 2.4 Implement Data Discovery
- Structured Data
- Unstructured Data
### 2.5 Implement Data Classification
- Mapping
- Labeling
- Sensitive Data
  - Protected Health Information \(PHI\)
  - Personally Identifiable Information \(PII\)
  - Cardholder Data
### 2.6 Design and Implement Information Rights Management \(IRM\)
- Objectives
  - Data Rights
  - Provisioning
  - Access Models
- Appropriate Tools
  - Issuing and Revocation of Certificates
### 2.7 Plan and Implement Data Retention, Deletion and Archiving Policies
- Data Retention Policies
- Data Deletion Procedures and Mechanisms
- Data Archiving Procedures and Mechanisms
- Legal Hold
### 2.8 Design and Implement Auditability, Traceability and Accountability of Data Events
- Definition of Event Sources and Requirement of Identity Attribution
- Logging, Storage and Analysis of Data Events
- Chain of Custody and Non-repudiation
## Domain 3
### 3.1 Comprehend Cloud Infrastructure Components
- Physical Environment
- Network and Communications
- [Compute](../../../concepts/cloud/cloud-components/compute.md)
- [Virtualization](../../../concepts/cloud/cloud-components/virtualization.md)
- [Storage](../../../concepts/cloud/cloud-components/cloud-storage/)
- Management Plane
### 3.2 Design a Secure Data Center
- Logical Design
  - Tenant Partitioning
  - Access Control
- Physical Design
  - Location
  - Buy or Build
- Environmental Design
  - Heating, Ventilation and Air Conditioning \(HVAC\)
  - Multi-Vendor Pathway Connectivity
### 3.3 Analyze Risks Associated with Cloud Infrastructure
- Risk Assessment and Analysis
- Cloud Vulnerabilities, Threats and Attacks
- Virtualization Risks
- Counter-measure Strategies
### 3.4 Design and Plan Security Controls
- Physical and Environmental Protection
  - On-premise
- System and Communication Protection
- Virtualization Systems Protection
- Identification, Authentication and Authorization in Cloud Infrastructure
- Audit Mechanisms
  - Log Collection
  - Packet Capture
### 3.5 Plan Disaster Recovery \(DR\) and Business Continuity \(BC\)
- Risks Related to the Cloud Environment
- Business Requirements
  - Recovery Time Objective \(RTO\)
  - Recovery Point Objective \(RPO\)
  - Recovery Service Level \(RSL\)
  - Business Continuity/Disaster Recovery Strategy
  - Creation, Implementation and Testing of Plan
## Domain 4
### 4.1 Advocate Training and Awareness for Application Security
- Cloud Development Basics
- Common Pitfalls
- Common Cloud Vulnerabilities
### 4.2 Describe the Secure Software Development Life Cycle \(SDLC\) Process
- Business Requirements
- [Phases and Methodologies](../../../concepts/software/software.md)
### 4.3 Apply the Secure Software Development Life Cycle \(SDLC\)
- Avoid Common Vulnerabilities During Development
- Cloud-specific Risks
- Quality Assurance
- Threat Modeling
- Software Configuration Management and Versioning
### 4.4 Apply Cloud Software Assurance and Validation
- Functional Testing
- [Security Testing Methodologies](../../../concepts/software/security-testing.md)
### 4.5 Use Verified Secure Software
- [Approved Application Programming Interfaces \(API\)](../../../concepts/software/apis.md)
- Supply-chain Management
- Third Party Software Management
- Validated Open Source Software
### 4.6 Comprehend the Specifics of Cloud Application Architecture
- Supplemental Security Components
  - Web Application Firewall \(WAF\)
  - Database Activity Monitoring \(DAM\)
  - Extensible Markup Language \(XML\) Firewalls
  - Application Programming Interface \(API\) Gateway
- Cryptography
- Sandboxing
- Application Virtualization and Orchestration
### 4.7 Design Appropriate Identity and Access Management \(IAM\) Solutions
- [Federated Identity](../../../concepts/iam/fim.md)
- Identity Providers
- [Single Sign-On \(SSO\)](../../../concepts/iam/sso.md)
- [Multifactor Authentication](../../../concepts/iam/mfa.md)
- Cloud Access Security Broker \(CASB\)
## Domain 5
### 5.1 Implement and Build Physical and Logical Infrastructure for Cloud Environment
- Hardware Specific Security Configuration Requirements
  - Basic Input Output System \(BIOS\)
  - Settings for Virtualization and Trusted Platform Module \(TPM\)
  - Storage Controllers
  - Network Controllers
- Installation and Configuration of Virtualization Management Tools
- Virtual Hardware Specific Security Configuration Requirements
  - Network
  - Storage
  - Memory
  - Central Processing Unit \(CPU\)
- Installation of Guest Operating System \(OS\) Virtualization Toolsets
### 5.2 Operate Physical and Logical Infrastructure for Cloud Environment
- Configure Access Control for Local and Remote Access
  - Secure Keyboard Video Mouse \(KVM\)
  - Console-based Access Mechanisms
  - Remote Desktop Protocol \(RDP\)
- Secure Network Configuration
  - Virtual Local Area Networks \(VLAN\)
  - Transport Layer Security \(TLS\)
  - Dynamic Host Configuration Protocol \(DHCP\)
  - Domain Name System \(DNS\)
  - Virtual Private Network \(VPN\)
- Operating System \(OS\) Hardening Through the Application of Baselines
  - Windows
  - Linux
  - VMware
- Availability of Standalone Hosts
- Availability of Clustered Hosts
  - Distributed Resource Scheduling \(DRS\)
  - Dynamic Optimization \(DO\)
  - Storage Clusters
  - Maintenance Mode
  - High Availability
- Availability of Guest Operating System \(OS\)
### 5.3 Manage Physical and Logical Infrastructure for Cloud Environment
- Access Controls for Remote Access
  - Remote Desktop Protocol \(RDP\)
  - Secure Terminal Access
  - Secure Shell \(SSH\)
- Operating System \(OS\) Baseline Compliance Monitoring and Remediation
- Patch Management
- Performance and Capacity Monitoring
  - Network
  - Compute
  - Storage
  - Response Time
- Hardware Monitoring
  - Disk
  - Central Processing Unit \(CPU\)
  - Fan Speed
  - Temperature
- Configuration of Host and Guest Operating System \(OS\) Backup and Restore Functions
- Network Security Controls
  - Firewalls
  - Intrusion Detection Systems \(IDS\)
  - Intrusion Prevention Systems \(IPS\)
  - Honeypots
  - Vulnerability Assessments
  - Network Security Groups
- Management Plane
  - Scheduling
  - Orchestration
  - Maintenance
### 5.4 Implement Operational Controls and Standards \(e.g., ITIL, ISO/IEC 20000-1\)
- Change Management
- Continuity Management
- Information Security Management
- Continual Service Improvement Management
- Incident Management
- Problem Management
- Release Management
- Deployment Management
- Configuration Management
- Service Level Management
- Availability Management
- Capacity Management
### 5.5 Support Digital Forensics
- Forensic Data Collection Methodologies
- Evidence Management
- Collect, Acquire and Preserve Digital Evidence
### 5.6 Manage Communication with Relevant Parties
- Vendors
- Customers
- Partners
- Regulators
- Other Stakeholders
### 5.7 Manage Security Operations
- Security Operations Center \(SOC\)
- Monitoring of Security Controls
  - Firewalls
  - Intrusion Detection Systems \(IDS\)
  - Intrusion Prevention Systems \(IPS\)
  - Honeypots
  - Vulnerability Assessments
  - Network Security Groups
- Log Capture and Analysis
  - Security Information and Event Management \(SIEM\)
  - Log Management
- Incident Management
## Domain 6
### 6.1 Articulate Legal Requirements and Unique Risks within the Cloud Environment
- Conflicting International Legislation
- Evaluation of Legal Risks Specific to Cloud Computing
- Legal Framework and Guidelines
- eDiscovery
  - [ISO/IEC 27050](../../../standards/forensics/iso-iec-27050.md)
  - CSA
- Forensics Requirements
### 6.2 Understand Privacy Issues
- Difference Between Contractual and Regulated Private Data
  - PHI
  - PII
- Country-Specific Legislation Related to Private Data
  - PHI
  - PII
- Jurisdictional Differences in Data Privacy
- Standard Privacy Requirements
  - ISO/IEC 27018
  - GAPP
  - GDPR
### 6.3 Understand Audit Process, Methodologies, and Required Adaptations for a Cloud Environment
- Internal and External Audit Controls
- Impact of Audit Requirements
- Identify Assurance Challenges of Virtualization and Cloud
- Types of Audit Reports
  - [SSAE SOC](../../../standards/auditing-and-assurance/aicpa-soc.md)
  - ISAE
- Restrictions of Audit Scope Statements
  - SSAE
  - ISAE
- Gap Analysis
- Audit Planning
- Internal Information Security Management System \(ISMS\)
- Internal Information Security Controls System
- Policies
  - Organization
  - Functional
  - Cloud Computing
- Identification and Involvement of Relevant Stakeholders
- Specialized Compliance Requirements for Highly-Regulated Industries
  - NERC/CIP
  - [HIPAA](../../../laws/united-states/hipaa.md)
  - [PCI](../../../standards/security-management-and-controls/pci-dss.md)
- Impact of Distributed Information Technology \(IT\) Model
  - Diverse Geographical Locations and Crossing Over Legal Jurisdictions
### 6.4 Understand Implications of Cloud to Enterprise Risk Management
- Assess Providers Risk Management Programs
  - Controls
  - Methodologies
  - Policies
- [Difference Between Data Owner/Controller vs. Data Custodian/Processor](../../../concepts/data/data-ownership.md)
  - Risk Profile
  - Risk Appetite
  - Responsibility
- Regulatory Transparency Requirements
  - Breach Notification
  - [SOX](../../../laws/united-states/sox.md)
  - [GDPR](../../../laws/eu-eea/gdpr.md)
- [Risk Treatment](../../../concepts/risk/risk-response.md)
  - Avoid
  - Modify
  - Share
  - Retain
- Different Risk Frameworks
- Metrics for Risk Management
- Assessment of Risk Environment
  - Service
  - Vendor
  - Infrastructure
### 6.5 Understand Outsourcing and Cloud Contract Design
- Business Requirements
  - [Service Level Agreement \(SLA\)](../../../concepts/business/operations-management/service-level-management/slas.md)
  - Master Service Agreement \(MSA\)
  - Statement of Work \(SOW\)
- Vendor Management
- Contract Management
  - Right to Audit
  - Metrics
  - Definitions
  - Termination
  - Litigation
  - Assurance
  - Compliance
  - Access to Cloud/Data
  - Cyber Risk Insurance
- Supply-Chain Management
  - ISO/IEC 27036
