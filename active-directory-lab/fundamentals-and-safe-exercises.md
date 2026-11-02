# Active Directory Fundamentals and Safe Lab Exercises

## Purpose
Understand basic Active Directory concepts relevant to first-level support. This guide is a conceptual worksheet; it does not claim that a domain controller or live Active Directory environment has been installed or configured.

## Core concepts
- **Domain:** a logical environment for centrally managing identities and resources.
- **User account:** an identity used to authenticate a person or service.
- **Group:** a collection of accounts used to manage permissions.
- **Organizational Unit (OU):** a container used to organize directory objects and apply delegated administration or policy.
- **Group membership:** one factor that can determine access to resources.
- **Account status:** an account may be enabled, disabled, locked out, or subject to other controls depending on policy.
- **Least privilege:** users should receive only the access needed for their role.

## Safe exercise A — Map a fictional access request
Fictional user: `training.user01`
Fictional department: `Outpatient Admin`
Requested resource: `Training-Schedule-App`
Requested group: `GG-Training-Schedule-Readers`

Tasks:
1. Identify the user, department, resource and requested group.
2. Identify what approval would be needed.
3. Explain why group membership should be verified before access is changed.
4. Write the request as a ticket note.
5. State that the actual permission change must be performed only by an authorized administrator.

## Safe exercise B — Account state triage
For each fictional report, identify what you would ask and which authorized team may need to investigate:
- User reports account locked.
- User reports account disabled.
- User can sign in but cannot open a shared resource.
- User reports an unexpected MFA prompt.

Do not attempt to unlock accounts, reset passwords, change group membership, or bypass security controls in a real environment without explicit authorization and approved procedures.

## Sample ticket note
"User reports access denied to the fictional Training-Schedule-App. Confirmed the issue is limited to one account based on the user's report. No credentials collected. Approval status needs verification. Routed to Identity & Access Team for authorized review."

## Knowledge check
1. What is the difference between authentication and authorization?
2. Why are groups used for access management?
3. What is an OU?
4. What does least privilege mean?
5. Why should a service desk analyst never request a user's password or MFA code?
