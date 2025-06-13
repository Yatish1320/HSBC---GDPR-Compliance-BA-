 Phase 1: Initiation & Stakeholder Engagement- Kick-off Meetings:
  Conducted initial stakeholder meetings with Compliance Officers, Data Protection Officers (DPOs), IT
 Security, Legal, and Business Unit Heads.
  Objectives included defining the scope of GDPR compliance, identifying system boundaries, understanding
 stakeholder expectations, and aligning on business priorities.- Stakeholder Matrix:
  Developed a comprehensive RACI matrix to outline stakeholder roles across workstreams:
  - Responsible: Business Analysts, Data Owners
  - Accountable: DPO, Project Sponsor
  - Consulted: Legal, Marketing, Risk Teams
  - Informed: All impacted business units
 Phase 2: Current State Assessment- Data Inventory:
  Worked with IT and business units to catalog all personal and sensitive data processed, stored, and
 transmitted.
  Data types included customer IDs, contact info, transactional records, cookies, and biometric data.
  Inventory categorized by system, geography, purpose, and lawful basis for processing.- Process Mapping:
  Used Microsoft Visio to map data collection, processing, sharing, and retention across departments.
  Identified data ingress points (web forms, mobile apps), processing workflows (CRM, ERP, marketing
 automation), and egress (third-party APIs, reporting tools).- Gap Analysis:
  Benchmarked existing policies and processes against GDPR requirements.
  Key gaps included lack of automated consent revocation, missing DSAR processing workflow, unclear data
 retention rules, and absence of audit trails.
  Prepared a gap report with recommended actions for each compliance failure.
 Phase 3: Requirements Gathering
Business Analyst Case Study: GDPR Compliance at HSBC- Workshops & Interviews:
  Conducted over 20 cross-functional workshops with Legal, Marketing, Operations, and IT to gather:
  - Functional requirements: DSAR handling, consent logging, data classification, encryption
  - Non-functional requirements: scalability, system availability, response time SLAs- Documentation:
  All requirements were captured in Confluence, categorized by GDPR article (e.g., Article 5 for data
 minimization).
  Applied version control for each requirement, maintained change logs, and linked user stories directly to
 JIRA for traceability.
 Phase 4: Solution Design & Implementation Roadmap- Consent Management:
  Redesigned customer-facing interfaces (web, mobile) to capture informed, granular consent with versioned
 text.
  Backend logging of consent status, user ID, timestamp, and source.
  Developed APIs for real-time consent validation across channels.
  Created audit logs for consent withdrawal events.- DSAR Automation:
  Designed and implemented a self-service DSAR portal.
  Integrated authentication, case management dashboard, and automated data fetching scripts from CRM,
 ERP, cloud databases.
  Enabled status tracking and SLA notifications for DPOs.- Retention & Deletion:
  Mapped legal retention periods to data categories.
  Designed automated job scheduler to delete or archive expired records.
  Logged retention events with digital signatures for audit purposes.- Privacy by Design:
  Embedded privacy checklists into project intake forms.
  Required DPIAs for new features involving sensitive data.
  Updated procurement templates to mandate DPAs with vendors.- Implementation Roadmap:
  Defined 6-month implementation timeline:
  - Phase 1: Inventory & MVP consent logging
  - Phase 2: DSAR portal deployment
  - Phase 3: Retention automation
Business Analyst Case Study: GDPR Compliance at HSBC
  - Phase 4: Monitoring dashboard & audit readiness
  Tools used: MS Project, JIRA, Power BI, Excel Gantt
 Phase 5: Testing, Monitoring & Post-Go-Live Support- Testing:
  Created 60+ end-to-end test cases for consent, DSARs, retention, and breach alerts.
  Conducted System Integration Testing (SIT) across customer systems and data layers.
  Facilitated User Acceptance Testing (UAT) with Legal, Marketing, Compliance.
  Ran security and performance tests to validate robustness and encryption.- Monitoring:
  Deployed Power BI dashboards for SLA monitoring (DSARs, deletion jobs).
  Configured Splunk for breach alerts and activity logging.
  Created ServiceNow escalation workflows for exception cases.- Change Management:
  Delivered training to over 150 users across compliance and IT.
  Produced step-by-step SOPs for handling DSARs, responding to breach alerts, and managing retention
 jobs.
  Recorded tutorials and uploaded to corporate LMS.- Post-Go-Live:
  Hypercare support for 30 days post-launch.
  Monitored KPIs including:
    - DSAR SLA Compliance Rate: 97.4%
    - Consent Logging Accuracy: 100%
    - Retention Job Success Rate: 100%
  Delivered knowledge transition pack to operations team.- Outcome:
  HSBC met GDPR compliance obligations ahead of regulatory audit.
  Increased customer transparency and control.
  Strengthened data governance maturity across the organization
