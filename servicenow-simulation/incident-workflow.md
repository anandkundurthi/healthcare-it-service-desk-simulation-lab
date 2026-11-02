# ServiceNow-Style Incident Workflow Simulation

## Scope
This is a paper/spreadsheet workflow simulation inspired by common incident-record fields. It is not a live ServiceNow instance, integration, or certification.

## Workflow
1. **Log:** capture a concise short description and clear description.
2. **Categorize:** select the closest category and subcategory available in the fictional workflow.
3. **Assess:** record impact and urgency using the lab's definitions.
4. **Prioritize:** use the provided simplified practice matrix; real organizations define their own matrix.
5. **Assign:** route to the correct first-line or specialist team.
6. **Investigate:** add factual work notes with actions and observations.
7. **Communicate:** record caller-facing updates separately from internal work notes.
8. **Resolve or escalate:** document verified resolution or a complete handoff.
9. **Close:** record confirmation and closure details according to the fictional workflow.

## Example incident fields
- Number: `HSD-TRAIN-001`
- Caller: fictional user
- Category: Application
- Subcategory: Clinical training application
- Impact: Low / Medium / High
- Urgency: Low / Medium / High
- Priority: derived from practice matrix
- State: New / In Progress / On Hold / Resolved / Closed
- Assignment group: Service Desk L1 / Application Support / Identity & Access
- Short description
- Description
- Work notes (internal)
- Additional comments (user-facing)
- Resolution code and resolution notes
- SLA checkpoint log

## Work notes vs additional comments
- Work notes: technical/internal record of checks, findings and handoff.
- Additional comments: clear updates intended for the requester.

Never put passwords, MFA codes, patient information or other sensitive data in either field.
