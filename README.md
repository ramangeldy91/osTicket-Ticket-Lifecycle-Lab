\# osTicket Ticket Lifecycle Lab



\## Project Overview



This project demonstrates practical Service Desk ticket lifecycle management using a locally deployed osTicket 1.18.4 environment.



The lab focuses on realistic Level I support workflows, ticket documentation, internal communication, SLA awareness, and escalation procedures.



It includes two practical scenarios based on synthetic support requests.



\## Objectives



\- Practice ticket creation and lifecycle management.

\- Handle user-facing replies and internal notes.

\- Understand ticket priorities, Help Topics, and SLA assignment.

\- Demonstrate department transfers and agent reassignment.

\- Apply appropriate escalation and resolution procedures.

\- Document actions, outcomes, and operational limitations.



\## Lab Environment



| Component | Configuration |

|---|---|

| Operating System | Windows 11 Pro Education |

| Web Server | Apache (XAMPP) |

| Database | MySQL |

| PHP | 8.3.36 |

| Ticketing Platform | osTicket 1.18.4 |

| Deployment | Local, single-host lab |



See \[Lab Environment](documentation/Lab-Environment.md) for configuration details and limitations.



\## Practical Scenarios



\### 01 - Password Reset / Account Access



\*\*Scenario type:\*\* Incident / Account Access Request



Demonstrated workflow:



\- Ticket registration and prioritization.

\- Initial Level I response.

\- Transfer from Support to IT Support L2.

\- Manual reassignment to Level II Support.

\- Level II response.

\- Ticket resolution.



Evidence: \[Password Reset / Account Access](evidence/Password-Reset-Account-Access/)



Workflow documentation: \[01 – Password Reset / Account Access](scenarios/01-Password-Reset-Account-Access.md)



\### 02 - Software Installation Request



\*\*Scenario type:\*\* Service Request



Demonstrated workflow:



\- Software request registration.

\- Initial Level I response.

\- Internal assessment and documentation.

\- Identification of outstanding manager approval and license verification.

\- Retention of the ticket in Open status pending further verification.



No installation was performed because the lab does not include a real license inventory or approval system.



Evidence: \[Software Installation Request](evidence/Software-Installation-Request/)



Workflow documentation: \[02 – Software Installation Request](scenarios/02-Software-Installation-Request.md)



\## Skills Demonstrated



\- Service Desk ticket management.

\- Incident and service request handling.

\- L1 troubleshooting and escalation awareness.

\- Ticket prioritization and SLA awareness.

\- Department and agent assignment.

\- User communication and internal documentation.

\- Ticket status management.

\- Evidence collection and technical reporting.

\- Security and software licensing awareness.



\## Tools and Technologies



\- osTicket 1.18.4

\- XAMPP

\- Apache

\- MySQL

\- PHP

\- Windows 11

\- PowerShell

\- Markdown

\- Git and GitHub



\## Evidence and Validation



Each practical scenario includes screenshots and an Evidence Report documenting:



\- Ticket details and relevant configuration.

\- Actions performed.

\- Workflow outcome.

\- Validation and known limitations.



All requester identities and ticket information are synthetic.



\## Lab Limitations



This is a personal local lab, not a production Service Desk environment.



\- One staff account is used to demonstrate both L1 and L2 activities.

\- SMTP and external email delivery are not configured.

\- No external identity provider integration is configured.

\- No real software license inventory or manager approval system is connected.

\- No endpoint software deployment integration is available.



Department transfers and agent reassignment are performed manually where required.



These limitations are documented to distinguish demonstrated actions from functionality that would require additional enterprise integrations.



\## Repository Structure



```text

osTicket-Ticket-Lifecycle-Lab/

│

├── documentation/

│   └── Lab-Environment.md

│

├── scenarios/

│   ├── 01-Password-Reset-Account-Access.md

│   └── 02-Software-Installation-Request.md

│

└── evidence/

&#x20;   ├── Password-Reset-Account-Access/

&#x20;   │   ├── screenshots

&#x20;   │   └── Evidence-Report.md

&#x20;   │

&#x20;   └── Software-Installation-Request/

&#x20;       ├── screenshots

&#x20;       └── Evidence-Report.md

```



\## Project Status



The two practical ticket scenarios have been completed and documented. The repository is being prepared for final validation and publication.

