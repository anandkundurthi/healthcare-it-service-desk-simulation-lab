# Healthcare IT Service Desk Simulation Lab

A fictional, documentation-led healthcare IT helpdesk simulation for practicing first-level support intake, hardware and peripheral troubleshooting, Microsoft 365 sign-in support, account-access triage, clinical-application incident handling, escalation, ServiceNow-style incident documentation, Active Directory fundamentals, and an Amazon Connect-style call-flow design.

## Scope and honesty

This is a learning simulation. It does **not** connect to a real hospital, patient record system, Microsoft 365 tenant, Active Directory domain, ServiceNow instance, or Amazon Connect contact center. All people, departments, systems, incidents, and patient-related references are fictional. Do not enter real patient information, employee personal data, passwords, MFA codes, or confidential information.

The Active Directory section is a conceptual/isolated-lab worksheet. The ServiceNow section is a workflow simulation using templates, not a live ServiceNow implementation. The Amazon Connect section is a proposed call-flow design and rehearsal, not a deployed Amazon Connect flow.

## Project modules

1. **Support scenarios** — Windows hardware/peripherals, Microsoft 365 sign-in, account access, and fictional clinical-app cases.
2. **Call scripts** — opening, identity-verification boundaries, issue intake, user updates, escalation and closure.
3. **Active Directory fundamentals** — users, groups, organizational units, least privilege, account-state concepts and safe lab exercises.
4. **ServiceNow workflow simulation** — incident fields, categorization, impact/urgency/priority, SLA checkpoints, work notes, caller updates and escalation.
5. **Amazon Connect call-flow simulation** — routing, queue handoff, fallback and call outcome documentation.
6. **Incident records** — blank templates and fictional completed examples.

## Suggested workflow

For each scenario:
1. Read the scenario and identify the user impact.
2. Ask the intake questions in the call script.
3. Record only fictional details in the incident template.
4. Perform safe first-level checks that are within the stated lab scope.
5. Record what was observed; do not invent test results.
6. Decide whether to resolve, monitor, or escalate.
7. Draft a clear user update and closure/handoff note.

## Repository structure

```text
healthcare-it-service-desk-simulation-lab/
├── README.md
├── scenarios/
│   ├── hardware-peripheral-support.md
│   ├── microsoft-365-sign-in.md
│   ├── account-access.md
│   └── fictional-clinical-application.md
├── call-scripts/
│   ├── inbound-support-call.md
│   └── user-updates-and-escalation.md
├── active-directory-lab/
│   └── fundamentals-and-safe-exercises.md
├── servicenow-simulation/
│   ├── incident-workflow.md
│   ├── incident-field-template.md
│   └── sla-checkpoint-log.md
├── amazon-connect-simulation/
│   ├── call-flow-design.md
│   └── call-flow-rehearsal-log.md
└── incident-records/
    ├── blank-incident-record.md
    └── fictional-sample-incidents.md
```

## Completion tracking

Use `docs/` only if you add your own supporting material. Update the manual validation/rehearsal logs with the date and actual outcome after completing each exercise. Do not describe an exercise as performed until you have rehearsed it and documented your observations.
