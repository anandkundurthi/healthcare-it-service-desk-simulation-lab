# Scenario: Account Access and Permission Request

## Scenario
A fictional employee cannot access a shared departmental application. The employee says a colleague can access it.

## Intake questions
- What application or resource is unavailable?
- What exact message appears?
- When did access last work?
- Is this a new starter, role change, or existing access issue?
- Has the manager or data owner approved the requested access?
- Is the issue limited to one user?

## First-level handling
1. Distinguish an authentication problem from an authorization/permission problem.
2. Capture the resource name and error text without collecting credentials.
3. Check whether the request has the required approval.
4. Verify the correct support ownership and route to the identity/access team when permissions must be changed.
5. Do not grant access, add group membership, or reset another person's password unless explicitly authorized and operating under approved procedures.

## Concepts
- Authentication: establishing who the user is.
- Authorization: determining what the authenticated user is allowed to access.
- Least privilege: granting only the access required for the job.

## Escalation
Escalate permission changes, privileged access, suspected compromise, or requests outside first-line authorization.
