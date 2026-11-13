# Software Installation Request - Ticket Workflow



## 1. Purpose



This workflow describes how Level I Service Desk handles requests for software installation while ensuring that licensing, authorization, and organizational requirements are verified before deployment.



## 2. Scenario



A user requests Microsoft Visio to create and edit process flowcharts and diagrams for daily work.



## 3. Request Registration



The Level I agent should:



1. Register the request in the ticketing system.

2. Record the requested software and business justification.

3. Identify the user's device and operating system, if required by the organization's process.

4. Select the appropriate Help Topic and department.

5. Set priority according to business impact and urgency.

6. Apply the appropriate SLA.

7. Assign the request to Level I Support.



## 4. Initial L1 Assessment



The Level I agent should:



1. Acknowledge the request.

2. Confirm that the application is required for the user's job responsibilities.

3. Check whether the software is included in the organization's approved software catalog.

4. Determine whether manager or application-owner approval is required.

5. Verify license availability through the authorized license management process.

6. Record findings in the ticket.



The agent must not promise installation before the required checks are completed.



## 5. Approval and Licensing Verification



Before installation:



- Confirm the required approval according to organizational policy.

- Verify that a valid license is available and can be assigned to the requester.

- Check software compatibility with the user's device and operating system.

- Confirm that installation is permitted under endpoint security policies.



If approval or license verification is outstanding, keep the request pending and document the outstanding action.



## 6. Escalation and Assignment



If L1 cannot complete the required checks:



1. Document what has already been verified.

2. Identify the responsible team, such as Software Asset Management, Application Support, or the manager's approval process.

3. Route the request according to the organization's escalation procedure.

4. Record the new owner or responsible team.

5. Inform the requester about the pending approval or verification.



A software request should not automatically be escalated to technical L2 if the outstanding action belongs to another business function.



## 7. Installation and Validation



Once approval and licensing requirements are satisfied:



1. Confirm the target device and deployment method.

2. Perform installation using an approved deployment tool or authorized procedure.

3. Verify that the application launches successfully.

4. Confirm that the appropriate license is assigned.

5. Update the ticket with the installation and validation results.



## 8. Resolution and Closure



Before resolving the request:



1. Confirm that the requested software is installed and operational, or document the approved alternative or rejection.

2. Record the outcome and relevant actions.

3. Notify the requester.

4. Set the ticket to Resolved.

5. Follow the organization's closure policy.



A request awaiting approval or licensing verification must not be marked Resolved.



## 9. Security and Compliance Requirements



- Install only approved software.

- Do not bypass licensing or approval requirements.

- Use authorized deployment tools and administrative privileges.

- Follow endpoint security and software asset management policies.

- Record approvals and license assignments in the appropriate systems.

- Do not store license keys or credentials in ticket comments.



## 10. Lab Demonstration

This workflow was demonstrated in a local osTicket lab using synthetic requester and ticket data.

### Actual Ticket Configuration

| Field | Value |
|---|---|
| Ticket ID | #522515 |
| Requester | Sarah Johnson |
| Subject | Software Installation Request - Microsoft Visio |
| Priority | Normal |
| Help Topic | General Inquiry |
| Department | Support |
| Assigned Agent | Rauan Admin |
| Assigned Team | Level I Support |
| SLA Plan | Standard SLA (8-hour grace period) |
| Source | Email |
| Final Status | Open |



The ticket remains Open because manager approval and license availability have not been confirmed.

### L1 Assessment Summary



**L1 Response Summary:**

Requested confirmation of manager approval and whether Microsoft Visio is required for the user's job responsibilities.



**Internal Note Summary:**

- Manager approval: Not confirmed.

- License availability: Not verified.

- Installation status: Not performed.

- Next action: Confirm approval and verify license availability before proceeding.


The practical demonstration included:



- Software installation request registration through the osTicket staff panel.

- L1 initial response requesting confirmation of manager approval and the application's business necessity.

- Internal assessment note documenting outstanding approval and license verification.

- Retention of the ticket in Open status while verification remains pending.



The ticket's Source field was set to Email, but no actual incoming email was received or processed.



No requester response to the L1 clarification questions was recorded during the demonstration.



The lab does not include a real software inventory, license management system, manager approval workflow, or endpoint deployment integration.



No actual Microsoft Visio installation was performed. The ticket was intentionally left Open because the required approval and license availability could not be verified.



## 11. Planned Next Steps



If the requester provides the required information, the Level I agent would:



1. Record manager approval in the ticket.

2. Verify Microsoft Visio license availability through the authorized process.

3. Confirm device compatibility and installation requirements.

4. Route the request to the responsible deployment team.

5. Verify successful installation and application launch.

6. Notify the requester and resolve the ticket after successful validation.



These are planned actions only. They were not performed in the lab demonstration.

