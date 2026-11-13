\# osTicket Ticket Lifecycle Lab



\## Project Overview



This project demonstrates practical Service Desk ticket lifecycle management using a locally deployed osTicket 1.18.4 environment.



The lab focuses on Level I support workflows, ticket documentation, user communication, internal notes, SLA awareness, and escalation procedures.



It includes two practical scenarios based on synthetic support requests, with documented actions, screenshots, and validation reports.



\## Objectives



\- Practice ticket creation and lifecycle management.

\- Handle user-facing replies and internal notes.

\- Understand ticket priorities, Help Topics, and SLA assignment.

\- Demonstrate department transfers and manual agent reassignment.

\- Apply appropriate escalation and ticket resolution procedures.

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



\### 01 - Account Access Request (Ticket Handling and Escalation)



\*\*Scenario type:\*\* Account Access Incident - Ticket Handling Demonstration



Demonstrated workflow:



\- Ticket registration and prioritization.

\- Initial Level I response.

\- Transfer from Support to IT Support L2.

\- Manual reassignment to Level II Support.

\- Level II follow-up response.

\- Ticket resolution and final state validation.



The scenario demonstrates ticket handling and escalation. No actual identity verification, password reset, credential change, or account modification was performed.



Evidence: \[Account Access Request Evidence](evidence/Password-Reset-Account-Access/)



Workflow documentation: \[01 - Account Access Request (Ticket Handling and Escalation)](scenarios/01-Password-Reset-Account-Access.md)



\### 02 - Software Installation Request



\*\*Scenario type:\*\* Service Request



Demonstrated workflow:



\- Software request registration.

\- Initial Level I response.

\- Internal assessment and documentation.

\- Identification of outstanding manager approval and license verification.

\- Retention of the ticket in Open status pending further verification.



No installation was performed because the lab does not include a real license inventory, manager approval system, or endpoint deployment integration.



Evidence: \[Software Installation Request](evidence/Software-Installation-Request/)



Workflow documentation: \[02 - Software Installation Request](scenarios/02-Software-Installation-Request.md)



\## Skills Demonstrated



\- Service Desk ticket management.

\- Incident and service request handling.

\- Ticket prioritization and SLA awareness.

\- Department transfer and manual agent reassignment.

\- User communication and internal documentation.

\- Ticket status and lifecycle management.

\- Escalation awareness and workflow documentation.

\- Evidence collection and technical reporting.

\- Software approval and licensing awareness.



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

\- Actions actually performed.

\- Workflow outcome.

\- Final ticket state and validation.

\- Known environment limitations.



All requester identities and ticket information are synthetic.



\## Lab Limitations



This is a personal local lab, not a production Service Desk environment.



\- One staff account is used to demonstrate both L1 and L2 activities.

\- SMTP and external email delivery are not configured.

\- Tickets were created through the staff panel. The Source field was set to Email, but no actual incoming email was received or processed.

\- Department transfers and agent reassignment are performed manually.

\- No external identity provider integration is configured.

\- No real software license inventory or manager approval system is connected.

\- No endpoint software deployment integration is available.

\- No actual password reset or identity verification was performed in the account access scenario.



These limitations are documented to distinguish demonstrated actions from functionality that would require additional enterprise integrations.



## Repository Structure

```text
osTicket-Ticket-Lifecycle-Lab/
|-- README.md
|-- documentation/
|   +-- Lab-Environment.md
|-- evidence/
|   |-- Password-Reset-Account-Access/
|   |   |-- 01 Ticket-Overview.png
|   |   |-- 02 L1-Response.png
|   |   |-- 03 L1-to-L2 Transfer - L2 Assignment - L2 Response.png
|   |   |-- 04 Ticket-Resolved.png
|   |   +-- Evidence-Report.md
|   +-- Software-Installation-Request/
|       |-- 01-L1-Initial-Response.png
|       |-- 02-L1-Internal-Note.png
|       +-- Evidence-Report.md
+-- scenarios/
    |-- 01-Password-Reset-Account-Access.md
    +-- 02-Software-Installation-Request.md
```

## Project Status



The two practical ticket-handling scenarios have been completed, documented, and published.



The repository includes workflow documentation, screenshots, and Evidence Reports. All demonstrations were performed in a local single-host lab environment.
