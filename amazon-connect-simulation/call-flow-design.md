# Amazon Connect-Style Inbound Call-Flow Simulation

## Scope
This is a conceptual call-flow design and rehearsal. It is not deployed in Amazon Connect and does not connect to a phone number, queue, contact center, or live customer environment.

## Proposed flow
1. **Inbound contact received**
2. **Welcome prompt**
   - "Welcome to the IT Service Desk training line."
3. **Language selection**
   - Option 1: English
   - Option 2: Telugu (route to a simulated language-capable queue; no real queue configured)
4. **Reason for contact**
   - Option 1: Computer / hardware
   - Option 2: Network / connectivity
   - Option 3: Microsoft 365 / account access
   - Option 4: Application support
   - Option 0: Operator / general support
5. **Queue routing (simulated)**
   - Hardware → Desktop Support
   - Network → Network Support
   - Microsoft 365 / account → Identity & Access Support
   - Application → Application Support
   - General → Service Desk L1
6. **Queue unavailable / no response**
   - Offer a simulated callback or advise the caller to use the approved support portal.
   - Create a handoff note; do not imply a real callback was scheduled.
7. **Agent intake**
   - Use the inbound call script.
   - Capture impact, urgency, symptoms and affected scope.
8. **Outcome**
   - Resolved at L1 / ticket created / transferred to specialist / caller disconnected / follow-up required.

## Routing and safety principles
- Do not request passwords, MFA codes or patient information.
- Use only fictional caller details in rehearsal.
- Provide a route to a human support analyst for unclear or urgent requests.
- In a real healthcare organization, clinical urgency and downtime must follow local approved procedures.
