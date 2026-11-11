\# Password Reset / Account Access - Ticket Workflow



\## 1. Purpose



This workflow describes how a Level I Service Desk agent handles a user report of account access failure and determines when escalation to Level II Support is appropriate.



\## 2. Scenario



A user reports that they cannot access their account because the password is rejected and requests assistance with account recovery.



\## 3. Initial Ticket Registration



The Level I agent should:



1\. Register the incident in the ticketing system.

2\. Verify the requester's identity using the organization's approved verification procedure.

3\. Record the affected account and a clear description of the symptoms.

4\. Select the appropriate Help Topic and department.

5\. Set the ticket priority according to business impact and urgency.

6\. Apply the appropriate SLA.

7\. Assign the ticket to Level I Support.



\## 4. Level I Initial Assessment



The Level I agent should:



1\. Acknowledge the user's request.

2\. Clarify the exact error message and when the issue started.

3\. Determine whether the issue affects one user or multiple users.

4\. Check for known service or authentication incidents, if access to such information is available.

5\. Follow the organization's identity verification and password reset procedures.

6\. Never request or record the user's current password.



If the issue can be resolved within L1 permissions, the agent should perform the approved recovery procedure and document the result.



\## 5. Escalation to Level II



Escalation is appropriate when:



\- The account remains inaccessible after approved L1 checks.

\- The issue appears to involve directory services or authentication infrastructure.

\- The agent lacks the permissions or tools required for further investigation.

\- The issue may affect multiple users or require specialist investigation.



The L1 agent should:



1\. Document the troubleshooting steps already performed.

2\. Record relevant error messages and observations.

3\. Transfer the ticket to the appropriate support department.

4\. Assign the ticket to the responsible Level II team or agent.

5\. Inform the user that the issue has been escalated.



Department transfer and agent assignment should be verified separately.



\## 6. Level II Handling



Level II Support should:



1\. Review the ticket history and L1 findings.

2\. Perform authorized technical investigation.

3\. Identify the cause or determine the appropriate recovery action.

4\. Document the actions taken and the outcome.

5\. Provide an update to the requester.



\## 7. Resolution and Closure



Before resolving the ticket:



1\. Confirm that the user can access the account, or that the agreed recovery instructions have been provided.

2\. Document the resolution clearly.

3\. Update the ticket status to Resolved.

4\. Follow the organization's closure and user confirmation policy.



A ticket should not be marked Resolved merely because it was transferred or escalated.



\## 8. Security and Handling Requirements



\- Follow the organization's identity verification procedure before account changes.

\- Never request passwords or MFA codes from users.

\- Use only approved password reset and account recovery tools.

\- Apply least privilege.

\- Document actions without exposing credentials or sensitive authentication data.

\- Escalate suspected account compromise through the appropriate security process.



\## 9. Lab Demonstration



This workflow was demonstrated in a local osTicket lab using synthetic requester and ticket data.



The demonstration included:



\- Ticket creation and prioritization.

\- Initial L1 response.

\- Transfer from Support to IT Support L2.

\- Manual assignment to Level II Support.

\- L2 response.

\- Ticket resolution.



The lab used a single agent account with access to separate support departments and teams. Department transfer and agent reassignment were performed as separate manual actions.



The demonstration validates ticket lifecycle handling and documentation. It does not demonstrate an actual password reset against an identity provider or production directory service.

