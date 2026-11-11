\# Lab Environment - osTicket Ticket Lifecycle



\## 1. Overview



This project uses a local osTicket installation to demonstrate practical Service Desk ticket handling workflows.



The environment is designed for individual learning and portfolio demonstration. It is not a production service desk environment.



\## 2. System Environment



| Component | Configuration |

|---|---|

| Operating System | Windows 11 Pro Education |

| Web Server | Apache (XAMPP) |

| Database Server | MySQL (XAMPP) |

| PHP | 8.3.36 |

| Ticketing System | osTicket 1.18.4 |

| Database | osticket\_lab |

| Local URL | http://localhost/osticket/ |

| Staff Panel | http://localhost/osticket/scp/ |

| Deployment Type | Local, single-host environment |



\## 3. Installed Components



The lab uses the following components:



\- XAMPP for the local Apache and MySQL services.

\- PHP for osTicket application execution.

\- MySQL database for ticket and configuration storage.

\- osTicket 1.18.4 as the ticket management platform.

\- A web browser for staff panel access and ticket administration.



\## 4. Service Desk Configuration



The environment includes:



\- Support department for Level I ticket handling.

\- IT Support L2 department for escalated technical requests.

\- Level I Support and Level II Support teams.

\- Configured staff roles and department access.

\- Standard SLA (8 hours).

\- High Priority SLA (4 hours).

\- Default SLA (18 hours).

\- Help Topics for general inquiries, feedback, and problem reporting.



A single staff account is used to demonstrate both Level I and Level II activities. Department transfers and agent reassignment are performed manually as separate actions. This demonstrates workflow configuration and ticket handling, not a multi-agent support operation.



\## 5. Demonstrated Workflows



The lab demonstrates two ticket scenarios.



\### Password Reset / Account Access



\- Ticket registration and prioritization.

\- Initial Level I response.

\- Transfer from Support to IT Support L2.

\- Manual reassignment to Level II Support.

\- Level II follow-up response.

\- Ticket resolution and final state validation.



This scenario demonstrates ticket handling and escalation only. No actual identity verification, password reset, credential change, or account modification was performed.



\### Software Installation Request



\- Ticket registration.

\- Initial Level I response.

\- Internal assessment note.

\- Documentation of outstanding manager approval and license verification.

\- Ticket retained in Open status pending further verification.



No software installation was performed.



\## 6. Evidence Collection



Evidence is stored in the repository under the `evidence` directory.



Each scenario contains:



\- Screenshots of relevant ticket states and actions.

\- An Evidence Report describing the workflow.

\- Final state validation and known limitations.



All requester identities and ticket data used in the demonstrations are synthetic.



\## 7. Environment Limitations



The following limitations apply:



\- The environment runs locally on a single Windows computer.

\- No separate production-like client or server infrastructure is configured.

\- Only one staff account is used to demonstrate L1 and L2 activities.

\- SMTP is not configured; external email delivery and ticket notifications are unavailable.

\- Tickets were created through the staff panel. The Source field was set to Email, but no actual incoming email was received or processed.

\- No external identity provider or Active Directory integration is configured.

\- No real software license inventory or manager approval system is connected.

\- No endpoint software deployment integration is available.



These limitations are documented to distinguish demonstrated functionality from processes that would require additional enterprise systems.



\## 8. Security Considerations



\- The lab uses synthetic requester information.

\- Database access is configured for the osTicket database.

\- Access to the osTicket staff panel is authenticated.

\- The environment is intended for local learning and demonstration only.

\- It must not be exposed to the public internet or used to process real confidential support requests.



\## 9. Project Scope



The objective is to demonstrate practical understanding of:



\- Ticket lifecycle management.

\- Incident and service request handling.

\- Level I support workflows and escalation procedures.

\- Department transfer and manual agent reassignment.

\- SLA awareness.

\- Internal notes and user-facing replies.

\- Documentation and evidence collection.

\- Security and operational limitations of a service desk environment.

