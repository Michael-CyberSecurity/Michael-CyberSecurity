## Hi there 👋

I’m currently seeking jobs related to Cyber Security/Information Security/IT Risk in New Zealand. GitHub readme extends my resume by showcasing my AI Risk and Mitigation, InfoSec GRC experience, Cyber Security background, SOC, Penetration Testing, IT Governance experience, Other IT skills, as well as my hobbies and personality.

- ⚡ AI Risk and Mitigation
- 1- Since 2018, focused on AI-driven cybersecurity, completing training and earning three certifications that year. Palo Alto Networks and FireEye leverage Machine Learning (ML) and, in some cases, Deep Learning (DL) for unstructured data analysis, such as detecting malicious patterns in images and videos, while Splunk primarily applies ML for anomaly detection and behavioral analytics.
- 2- During the Master of Cyber Security studies, continued learning Machine Learning (ML) and Deep Learning (DL), with a focus on Neural Networks. Completed AI Risk&Mitigation and AWS SageMaker training.

- 3- Based on the above AI developments, AI Risk--Four Key Domains:
  1) Data Risk – CIA, Privacy, Data Poisoning
  2) Model Risk – Theft, Reverse Engineering, Unauthorized Manipulation, Adversarial Attacks, Model Interpretability, Supply Chain Attacks
  3) Operational Risk – Drift or Decay, Sustainability Issues, Lack of Accountability
  4) Ethical & Legal Risk
     
- 4- Intentional Failure Modes / Attacks
  1) Adversarial Attack
  2) Poisoning Attack
  3) Reprogramming neural nets--Adapting a pre-trained neural network to a new task to behave maliciously
  4) Physical Domain
  5) Model Inversion--reverse-engineer the data it was trained
  6) Modelling Stealing -- model extraction/reconstruction
  7) System Manipulation: Attacker train system abnormal to normal behavior
  8) AI underlying system attack--OS Vulnerabilities, Hardware Failure, Buffer Overflow
     
- 5- Mitigation Plans for Intentional Failure Modes / Attacks:
  1) Dataset Hygiene
  2) Adversarial Training
  3) Access Control to APIs
  4) Threat Modelling, Secure Engineering, Vulnerability Management, Penetration Testing, Hardware Maintenance

- 6- Unintentional Failure Modes/Intrinsic Design Flaws
  1) Reward Hacking-Creating messy and clean up, Reinforcement Learning(RL) cheat the reward function without doing the intended task
  2) Side Effect- Unintended negative consequence that occur when the agent complete the task correctly
  3) Distributional shift-It occurs when the real-world data the model sees later is different from the training data.
  4) Incomplete testing
  5) Overfitting and underfitting
  6) Data Bias
     
- 7- Mitigation Plans for Unintentional Failure Modes/Intrinsic Design Flaws:
  1) Design reward functions to align with the true goal
  2) Adding penalties for undesired behaviors, add side-effect penalties
  3) Implement periodic retraining with new data
  4) Split data into training, validation, and test sets; Use regularization techniques (L1/L2, dropout) to prevent overfitting.
  5) Increase training data or improve feature engineering to prevent underfitting.
  6) Apply bias detection and fairness metrics.

- 👯 InfoSec GRC--Designed and implemented security systems from the ground up, aligning with ISO 27001 requirements and objectives while integrating industry best practices to achieve its security goals, including:
  1) Led the development of Information Security Governance bodies (Committee, leading group, representatives, and working group). Served as a key liaison to ensure effective collaboration with department leaders and stakeholders, successfully organizing and coordinating governance activities.
  2) Business Continuity & Disaster Recovery (BCP): Ensured resilience by integrating NIST SP 800-34 Rev.1, ISO/IEC 27031, and ISO/TS 22317 contingency planning guidelines.
  3) Risk Management Framework: Applied NIST SP 800-30, NIST CSF 2.0, ISCSI IT Asset Valuation, Risk Assessment & Control Model, and CVSS to enhance risk assessment and mitigation strategies.
  4) Incident Management: Strengthened security incident response by aligning NIST SP 800-61 Rev.3, and NIST CSF 2.0 recommendations.
  5) Secure System Development & Acquisition: Enforced secure development including security coding, secure development environment, security of version control, security testing and procurement processes by integrating OWASP, and ISO 27002 guidelines.
  6) Additionally, implemented ISO 27002 to support security objectives in key areas, including: Organization of Information Security, Asset Management, Supplier Relationships, Human Resource Security, Operations Security, and Access Control.
  7) The above Information Security Management System (ISMS) is referenced by the Cyber Security Architecture(see subsequent section). The cyber architecture is not only based on the ISMS but also integrates broader security elements and business perspectives。Within the cyber security architecture, ISMS policies are referenced by the Conceptual Security Architecture, the Logical Security Architecture (high level) applies ISMS standards and control objectives, and the Physical and Component Security Architectures (lower level) implement the corresponding ISMS procedures.


- 🌱 Designed and Built Business-Driven Cyber Security Architecture (see the three key points below)
- 1- Referenced SABSA enterprise architecture framework to design and build five security architecture layers from different perspectives:
  1) The Business's  view --  Contextual Security Architecture 
  2) The Architect's view -- Conceptual Security Architecture
  3) The Designer's  view -- Logical Security Architecture (high-level)
  4) The builder's   view --  Physical & Component Security Architecture (lower-level)
  5) The FacilityManager's view -- Operational Security Architecture
- 2- Established strong connections between the five layers to help business owners clearly understand enterprise risks and align security strategy with business decisions.
- 3- Physical & Component Security Architecture (lower-level) and Operation Security Architecture – implemented measures include:
  1) Data Security: Implemented the 5A Methodology and developed three key security architectures: Product Security Architecture, Security Technology Architecture, and Audit Architecture. Applied NIST Data Security Framework and PCI DSS standards for comprehensive data protection.
  2) Secure engineering & Application Security: Led secure engineering initiatives by embedding security into the software development lifecycle through threat modeling, secure coding, and security testing. Drove the adoption of OWASP Secure Coding Practices, focusing on input validation, output encoding, authentication and password management, session management, error handling, and database security. Strengthened application security posture by implementing configurations aligned with CIS Benchmarks.
  3) Cryptography: Based on CISSP standards and Cryptography and Network Security: Principles and Practice (Pearson), strengthened the cryptosystem by optimizing algorithms, ensuring key secrecy, selecting appropriate key lengths, and using initialization vectors to achieve ideal confusion and diffusion. Analysed cipher suites and selected suitable options for enterprise applications.
  4) Communications Security: Designed and implemented a Robust Security Network (RSN) with IEEE 802.11i for wireless security. Analysed common network attacks and performed security hardening on routers, switches, and firewalls, following vendor best practices.
  5) System Security: In alignment with CIS standards, led secure hardening initiatives for Linux, AIX, Windows, Apple Server Systems, Virtualization, Cloud Computing, and NAS/SAN Storage to ensure comprehensive security across diverse platforms.
  6) AAA: Authentication, Authorization, and Accounting — using RADIUS for initial authentication, integrated with EAP methods such as EAP-TLS/PEAP, PKI for certificate-based access, Kerberos for Single Sign-On (SSO), and LDAP for centralized identity management.
  7) Operation Security Architecture – implemented through ⚡ Internal SOC and 🔭 Penetration Testing (see details below):
    
- ⚡ Internal SOC (Security Operation Center) 
  1) Designed and implemented an enterprise SOC architecture integrating SIEM (Splunk), Logstash, and Salesforce (later migrated to ServiceNow) to centralize incident tracking and workflow automation.
  2) Integrate log sources from on-prem systems (Palo Alto firewalls, servers, endpoints, email, network devices) and cloud AWS into centralized SIEM (Splunk).
  3) Developed and maintained use cases to generate automated security alerts and improve threat detection including Data Exfiltration/Large Outbound Transfers, Malware Execution, Ransomware/Encryption Activity, Ransomware/Encryption Activity, Suspicious PowerShell/Script Execution, Brute-force Login Attempts, Unusual Login Locations, Unauthorized Privilege Escalation/ Admin account creation, Unusual Network Connections， Phishing/Compromised Email Activity, Policy Violations/Compliance Breach, Unauthorized Security Group Change, KMS/Encryption Key Abuse, Lambda/Unusual Invocation, Lambda/Unusual Invocation.
  4) Conducted static and dynamic malware analysis in sandbox environments to identify malicious behaviors and enhance detection rule accuracy.
  5) Performed incident analysis, and threat validation, continuously fine-tuning detection rules to minimize false positives and false negatives.
  6) Provided analytical feedback to vendors (e.g., Palo Alto) to improve security product detection accuracy and contribute to the broader cybersecurity community.

- 🔭 Penetration Testing
  1) Follow PTES and OWASP frameworks to conduct web application and network Penetration Testing.
  2) Perform information gathering, threat modelling, vulnerability identification, exploitation, and post-exploitation (privilege escalation, process migration, security products and services evasion, persistence, lateral movement).
  3) Wireless security — assess WPA2, WPA and WEP deployments and detect rogue/fake access points.
  4) Network segmentation & exposure testing — evaluate segmentation controls and identify enterprise sensitive-data exposure to the public Internet.
  5) Conduct phishing simulations with malware attachment testing to evaluate user awareness


- 🌱 Designed and Built Business-Driven Data Security Architecture
- 1- Contextual Security Architecture (Business View – SABSA EA): At Baoneng Motor, a key stakeholder requirement stated that “enterprise sensitive information must not be used, disclosed, altered, or deleted without authorization.” As data security was the primary concern, a dedicated Data Security Architecture was developed independently from the overall Cyber Security Architecture, referencing the TOGAF framework.
- 2- Data Security Architecture consists of three sub-domain architectures:
   1) Domain 1-Product Security Architecture: Implements the 5A principles (Authentication, Authorization, Accounting, Account Management, and Asset Protection and key lifecycle management to safeguard product-related data, while integrating DevSecOps practices to ensure continuous security across the development and deployment lifecycle.
   2) Domain 2-Security Technology System Architecture: Covers four layers — Application & Data, Equipment & Host, Network & Communication, and Physical & Environmental — applying the 5A principles across each layer to strengthen data protection.
   3) Domain 3-Audit Architecture: Utilizes DLP and SIEM (Splunk) use cases with multiple indicators for real-time monitoring of sensitive data and detection of potential insider or external threats. Suspicious employee activities trigger deeper investigations following 📫 Digital Forensic Procedures and technique (outlined in the next section) , with the capability to produce court-ready technical reports when required.


- 📫 Digital Forensic
  1) Conducted forensic imaging and evidence preservation using write blockers and cryptographic hashing (SHA-256, MD5).
  2) Created and verified forensic copies with dd, ensuring chain of custody and data integrity.
  3) Mounted forensic images in read-only mode for analysis and data recovery.
  4) Recovered deleted and hidden files via FAT/MFT and slack space analysis using Autopsy tool.
  5) Applied password recovery and steganography detection techniques using tools John and Identify
  6) Documented forensic processes, maintained chain of custody and job sheets, and produced court-ready technical reports.

- 👯 IT Governance
  1)	Assisted the Chief Information Officer (CIO) in planning activities, including the annual work plan of the Information Management Center, performance evaluations, and the development of IT governance documentation.
  2)	Acted as PMO role in designing and building IT project management systems aligned with PMP standards. Managed projects through all six stages: preparation, initiation, planning, implementation, go-live preparation and closure;
  3)	Acted in a PMO role, designing and monitoring key project deliverables across all project stages: Project Preparation, Project Initiation, Project Planning, Project Implementation, Go-Live Preparation, and Project Closure.
  4)	Assisted in project permission management, risk assessment, and progress monitoring using the ZenTao tool, ensuring alignment with organizational objectives.
     


- 📫 IT Infrastructure and Web Application Architecture
  1) Server: Experienced in maintaining and hardening Windows, Linux, AIX, and macOS servers
  2) Cloud: Experienced with AWS, Microsoft Office 365, Microsoft Dynamic 365, Alibaba, and OpenStack for infrastructure deployment, automation, security hardening and control implementation, as well as security incident analysis. Proficiency in AWS services including ECS, EKS, EC2, S3, and Lambda, and with cloud security services such as IAM, KMS, CloudTrail, CloudWatch, Config, Security Hub, WAF, Inspector, and GuardDuty.
  3) Active Director: Skilled in designing and troubleshooting complex AD environments (multi-domain/site), Group Policy, RBAC, domain trusts, and IAM integration.
  4) Docker: Experienced in Dockerfile creation and container orchestration using Kubernetes and AWS EKS.
  5) Virtualization: Proficient in Hyper-V clustering; experienced with KVM and VMware vSphere maintenance.
  6) Storage: Experienced with EMC and IBM San storage arrays, as well as the distributed storage system MogileFS.
  7) Database: Basic DBA skills—MySQL backup, replication, transaction handling, caching (Memcached/Redis), and HA (MHA, Redis Sentinel).
  8) Web Infrastructure: Optimized LNMP stacks for performance, availability, and cost-efficiency using HAProxy, Varnish, Nginx, Keepalived, MHA, Redis, and MogileFS.
  9) Monitoring: Used Zabbix for infrastructure monitoring (e.g., CPU, network, disk)
  10) Automated deployment and configuration management: Used Puppet for automated server deployment, configuration, and drift correction.
      
- 😄 Hobbies&Personality: I'm a good dancer! I'm a social person who enjoys meeting new friends. I love animals and embracing nature. I'm also interested in Maori's culture and hope to have the opportunity to contribute to the Mario community.

<!--
**Michael-CyberSecurity/Michael-CyberSecurity** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
